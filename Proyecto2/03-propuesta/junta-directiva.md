# Simulación de Junta Directiva Técnica

## Descripción de la simulación

La siguiente es una simulación de una junta directiva técnica del equipo de desarrollo de software, realizada en el marco de una fase de toma de requerimientos con dos negocios reales: una vidriería y un taller de herrería.

En esta simulación participan cinco roles clave:

- **Scrum Master:** Modera la reunión, facilita los acuerdos y mantiene el control de la sesión.
- **Product Manager:** Vela por la entrega en tiempo y el valor para el negocio.
- **Tech Lead:** Garantiza la solidez técnica, escalabilidad y calidad del sistema.
- **QA / Auditor:** Asegura que el producto funcione correctamente y cumpla con estándares de calidad.
- **Cliente / Stakeholder:** Representa al dueño de los negocios, expone sus necesidades y limitaciones.

El objetivo de la junta es analizar los hallazgos obtenidos durante las entrevistas, definir la solución tecnológica a implementar, establecer el alcance, los tiempos de entrega y documentar los acuerdos y trade-offs aceptados por todos los involucrados.

---

## Resumen de la junta

**Duración estimada:** 40 - 45 minutos

**Fecha:** 19 de abril

---

### Problema identificado

En la vidriería se detectaron tres problemas principales: falta de control de clientes, ausencia de registro formal de pedidos y nula visibilidad sobre ganancias o pérdidas. En el taller de herrería, los problemas incluyen manejo de inventario de memoria, aceptación de trabajos sin verificar disponibilidad de materiales y fechas de entrega poco confiables.

El cliente reporta una pérdida estimada de 5 clientes por mes, con un impacto aproximado de Q300 a Q400 por cliente.

---

### Decisión de solución

Se acuerda desarrollar un sistema web responsive con tres módulos funcionales:

- **Clientes**
- **Pedidos**
- **Inventario**

Adicionalmente, incluirá autenticación básica de un solo usuario y backup automático mediante Firebase.

---

### Plan de trabajo

| Semana | Actividad |
|--------|-----------|
| Semana 1 | Diseño y arquitectura |
| Semana 2 | Desarrollo |
| Semana 3 | Desarrollo |
| Semana 4 | Pruebas y correcciones menores |

**Tiempo total de entrega:** 4 semanas

---

### Requerimientos excluidos (para segunda fase)

- Módulo de reportes financieros (ganancias por mes)
- Módulo de control de garantías

---

### Trade-offs aceptados

1. **Tiempo vs. Calidad:** 4 semanas en lugar de 6, aceptando una arquitectura funcional pero no perfectamente escalable.
2. **Alcance vs. Tiempo:** Exclusión de módulos de garantías y reportes financieros para cumplir con el plazo.
3. **Funcionalidad vs. Simplicidad:** Reportes básicos sin gráficas complejas ni análisis avanzados.
4. **Control vs. Velocidad:** Uso de Firebase (nube de Google) en lugar de servidor propio para reducir tiempos de desarrollo.

---

### Acuerdos formales

1. Se desarrollará el sistema en 4 semanas con los tres módulos base, autenticación básica y backup en Firebase.
2. Los requerimientos quedan congelados a partir de hoy. Cualquier nuevo requerimiento se documenta para una segunda fase.
3. Se aceptan explícitamente los cuatro trade-offs documentados.

---

### Resultado final

La junta concluye con todos los roles de acuerdo, el cliente satisfecho dentro de sus limitaciones, y un plan concreto, documentado y firmado en el acta. El Scrum Master cierra la sesión agradeciendo la participación y el profesionalismo del equipo.
