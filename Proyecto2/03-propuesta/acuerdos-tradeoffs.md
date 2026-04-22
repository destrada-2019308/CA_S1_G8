# Trade-offs dichos en la junta directiva técnica

Durante la negociación se identificaron y aceptaron explícitamente los siguientes cuatro trade-offs:

---

## Trade-off 1: Tiempo vs. Calidad

**Decisión:** Se eligió un tiempo de entrega de 4 semanas en lugar de las 6 semanas que propuso inicialmente el Tech Lead.

**Consecuencia aceptada:** La arquitectura será funcional pero no perfectamente escalable. Si en el futuro el negocio crece mucho, puede que necesitemos reestructurar partes del sistema. Para el volumen actual de negocio, la solución es suficiente.

> *"Estamos eligiendo cuatro semanas en lugar de seis. Eso significa que la arquitectura va a ser funcional pero no perfectamente escalable."* — Tech Lead

---

## Trade-off 2: Alcance vs. Tiempo

**Decisión:** Se dejaron fuera de la primera fase el módulo de reportes financieros y el módulo de control de garantías para poder cumplir con las cuatro semanas.

**Consecuencia aceptada:** El cliente no tendrá visibilidad completa de sus ganancias ni control de garantías desde el inicio. Estos requerimientos quedan documentados para una segunda fase.

> *"Estamos dejando fuera el módulo de reportes financieros y el de garantías para cumplir con las cuatro semanas. Eso significa que el cliente no va a tener visibilidad completa de sus ganancias desde el inicio."* — QA / Auditor

---

## Trade-off 3: Funcionalidad vs. Simplicidad

**Decisión:** Para que el sistema sea fácil de usar para alguien sin experiencia técnica, se simplificaron algunas funciones.

**Consecuencia aceptada:** Los reportes van a ser básicos, sin gráficas complejas ni análisis avanzados. Solo listas y totales simples, priorizando la claridad y facilidad de uso sobre la profundidad analítica.

> *"Los reportes van a ser básicos, sin gráficas complejas ni análisis avanzados. Solo listas y totales simples."* — Desarrollador

---

## Trade-off 4: Control de datos vs. Velocidad de desarrollo

**Decisión:** Se utilizó Firebase como base de datos en la nube en lugar de implementar un servidor propio del cliente.

**Consecuencia aceptada:** Los datos van a estar alojados en servidores de Google (Firebase) y no en una infraestructura controlada directamente por el cliente. A cambio, se reduce significativamente el tiempo de desarrollo y se obtienen respaldos automáticos.

> *"Estamos usando Firebase como base de datos porque reduce el tiempo de desarrollo, pero eso significa que los datos van a estar en servidores de Google y no en un servidor propio del cliente."* — QA / Auditor

---

## Resumen

| # | Trade-off | Decisión | Consecuencia |
|---|-----------|----------|--------------|
| 1 | Tiempo vs. Calidad | 4 semanas (vs 6) | Arquitectura funcional pero no perfectamente escalable |
| 2 | Alcance vs. Tiempo | Excluir garantías y reportes | Cliente sin visibilidad de ganancias en fase 1 |
| 3 | Funcionalidad vs. Simplicidad | Reportes básicos | Sin gráficas ni análisis avanzados |
| 4 | Control vs. Velocidad | Firebase (nube) | Datos en servidores de Google |
