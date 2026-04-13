# Documento Post-Mortem

## Resumen del incidente
El día de la implementación del sistema web de gestión para 
la vidriería, el servidor dejó de responder luego de que el 
dueño intentó registrar varios clientes al mismo tiempo. 
Esto provocó la pérdida de datos ingresados durante esa 
sesión y dejó el sistema inaccesible por varias horas. 
El incidente ocurrió el primer día de uso real del sistema 
afectando directamente la operación del negocio.

---

## Línea de tiempo

| Hora | Evento |
|---|---|
| 08:00 AM | El dueño comienza a usar el sistema por primera vez |
| 08:30 AM | Se registran los primeros 5 clientes sin problemas |
| 09:00 AM | El dueño intenta registrar 10 clientes seguidos rápidamente |
| 09:05 AM | El sistema comienza a responder lento |
| 09:10 AM | El servidor deja de responder completamente |
| 09:15 AM | El equipo recibe aviso del problema |
| 09:30 AM | Se identifica que el servidor se saturó por múltiples peticiones simultáneas |
| 10:00 AM | Se reinicia el servidor manualmente |
| 10:15 AM | El sistema vuelve a estar disponible pero sin los datos ingresados desde las 08:30 AM |
| 11:00 AM | Se confirma que el backup automático no estaba configurado correctamente |

---

## Impacto

**Usuarios afectados:**
- El dueño de la vidriería perdió los datos de 5 clientes 
  que había ingresado
- Los clientes cuyos datos se perdieron tuvieron que ser 
  contactados nuevamente para reingresarlos

**Efectos directos:**
- Pérdida de datos de clientes ingresados durante la sesión
- Sistema inaccesible durante aproximadamente 1 hora
- Desconfianza del dueño hacia el sistema

**Efectos indirectos:**
- Retraso en la operación normal del negocio
- Tiempo adicional del equipo para resolver el incidente
- El dueño consideró volver a usar su método manual

---

## Causa raíz

Se aplicó la técnica de los 5 porqués:

**¿Por qué se cayó el sistema?**
Porque el servidor se saturó con múltiples peticiones simultáneas.

**¿Por qué se saturó el servidor?**
Porque no se configuró un límite de peticiones por usuario.

**¿Por qué no se configuró ese límite?**
Porque durante el desarrollo no se realizaron pruebas de 
carga ni de estrés al sistema.

**¿Por qué no se hicieron pruebas de carga?**
Porque el equipo priorizó entregar el sistema rápido y no 
planificó una fase de pruebas adecuada.

**¿Por qué no se planificó una fase de pruebas?**
Porque no se consideró que un usuario sin experiencia 
técnica podría usar el sistema de forma intensiva 
desde el primer día.

**Causa raíz identificada:**
La falta de pruebas de rendimiento y la ausencia de 
configuración correcta del backup automático antes 
de poner el sistema en producción.

---

## Acciones tomadas para solucionarlo

| Acción | Responsable | Resultado |
|---|---|---|
| Reinicio manual del servidor | Desarrollador | Sistema disponible nuevamente |
| Revisión de configuración del backup | Tech Lead | Se identificó que el backup no estaba activo |
| Activación manual del backup | Desarrollador | Backup configurado correctamente |
| Reingreso manual de datos perdidos | QA / Auditor | Datos recuperados con ayuda del dueño |
| Comunicación al dueño del negocio | Scrum Master | El dueño fue informado y tranquilizado |

---

## Acciones a futuro

| Acción | Descripción |
|---|---|
| Pruebas de carga | Realizar pruebas de rendimiento antes de entregar el sistema |
| Backup automático | Verificar que el backup esté activo antes de poner en producción |
| Límite de peticiones | Configurar un límite de peticiones por usuario para evitar saturación |
| Manual de usuario | Crear una guía simple para que el dueño use el sistema correctamente |
| Monitoreo del servidor | Implementar alertas automáticas cuando el servidor esté al límite |
| Fase de pruebas | Incluir una semana de pruebas con el usuario antes de la entrega final |
