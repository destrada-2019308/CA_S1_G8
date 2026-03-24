
---
# 1. INTRODUCCIÓN

Vivimos en una era donde la mayor parte de nuestra vida ocurre en espacios digitales: nos comunicamos, estudiamos, realizamos transacciones bancarias, almacenamos recuerdos y construimos identidades en plataformas conectadas a Internet. Sin embargo, pocas veces nos detenemos a reflexionar sobre los riesgos que esto conlleva y, menos aún, sobre las acciones concretas que podemos tomar para protegernos.

El presente informe documenta el proceso y los resultados de una capacitación grupal titulada **"Ciberseguridad y Protección Personal en Internet"**, desarrollada en el marco del curso de Comunicación Asertiva de la Facultad de Ingeniería en Ciencias y Sistemas de la Universidad San Carlos de Guatemala. La capacitación estuvo dirigida a estudiantes de primer año de la carrera, con una duración de 60 minutos y la participación de seis expositores.

La elección del tema no es casual. Los estudiantes de Ingeniería en Sistemas ocupan una posición única: son, al mismo tiempo, usuarios de tecnología expuestos a amenazas digitales, y futuros creadores de software que tendrán en sus manos la seguridad de miles de personas. Esa doble responsabilidad hace que la ciberseguridad no sea un tema optativo, sino una competencia fundamental desde el inicio de la carrera.

La capacitación abordó cinco grandes bloques temáticos: los fundamentos de la ciberseguridad y la tríada CIA, la ingeniería social y sus técnicas más comunes, la protección de contraseñas e identidad digital, los hábitos y herramientas de prevención, y la seguridad en el desarrollo de software. La sesión cerró con una actividad de validación del aprendizaje que midió la comprensión del público de forma dinámica y participativa.

Este informe recoge la investigación realizada, el análisis reflexivo del desempeño del grupo mediante la herramienta FODA, la aplicación de principios de comunicación asertiva durante el proceso, y todos los materiales utilizados en la conferencia.

---

# 2. OBJETIVOS

## 2.1 Objetivo General

Capacitar a los estudiantes de primer año de Ingeniería en Sistemas de la USAC en los fundamentos de la ciberseguridad y la protección personal en internet, promoviendo hábitos digitales seguros y una conciencia crítica sobre las amenazas del entorno digital, mediante una conferencia grupal estructurada y participativa.

## 2.2 Objetivos Específicos

- **Identificar** las principales amenazas de ciberseguridad a las que están expuestos los usuarios en su vida cotidiana y en su futura vida profesional como ingenieros.
- **Reconocer** las técnicas de ingeniería social más utilizadas por atacantes, especialmente el phishing y sus variantes, para evitar caer en ellas.
- **Aplicar** buenas prácticas para la creación y gestión de contraseñas seguras, incluyendo el uso de gestores de contraseñas y la autenticación de dos factores (2FA).
- **Adoptar** hábitos y herramientas de prevención que permitan a los usuarios mantener sus dispositivos, cuentas y datos protegidos en el día a día.
- **Comprender** el impacto de la seguridad en el proceso de desarrollo de software, reconociendo vulnerabilidades comunes documentadas en el OWASP Top 10.
- **Validar** el aprendizaje del público asistente mediante una actividad práctica de análisis de situaciones reales de seguridad e inseguridad digital.
- **Desarrollar** habilidades de comunicación asertiva dentro del equipo durante la planificación, coordinación y ejecución de la capacitación.

---

# 3. DESCRIPCIÓN GENERAL DEL TEMA Y SUBTEMAS

## 3.1 ¿Qué es la Ciberseguridad?

### Definición

La **ciberseguridad** es el conjunto de prácticas, tecnologías y procesos diseñados para proteger sistemas, redes y datos de ataques, daños o accesos no autorizados. No es un tema exclusivo de expertos ni de grandes empresas: afecta a cualquier persona que use tecnología conectada a Internet, desde quien revisa su correo en el teléfono hasta el ingeniero que desarrolla aplicaciones para millones de usuarios.

Para los estudiantes de Ingeniería en Sistemas, este tema adquiere una dimensión adicional. Como futuros constructores de software, administradores de redes y diseñadores de arquitecturas digitales, en sus manos estará, en parte, la seguridad de otras personas. Un error en una línea de código puede exponer los datos de miles de usuarios; una contraseña débil en un servidor puede abrir la puerta a un atacante.

### La Tríada CIA: Los Tres Pilares de la Ciberseguridad

La ciberseguridad descansa sobre tres principios fundamentales conocidos como la **Tríada CIA**:

| Pilar | Descripción |
|-------|-------------|
| **Confidencialidad** | Solo las personas autorizadas pueden acceder a la información. |
| **Integridad** | La información no debe ser alterada sin autorización. |
| **Disponibilidad** | Los sistemas y datos deben estar accesibles cuando se necesiten. |

Cuando cualquiera de estos tres pilares falla, se produce un **incidente de seguridad**. Por ejemplo, un ransomware compromete la disponibilidad; una filtración de datos compromete la confidencialidad; y la manipulación de registros compromete la integridad.

### Tipos de Amenazas

Las amenazas en ciberseguridad pueden clasificarse en cuatro categorías:

- **Amenazas externas:** hackers, grupos organizados de ciberdelincuentes, actores estatales.
- **Amenazas internas:** empleados descuidados, negligentes o con malas intenciones.
- **Amenazas pasivas:** espionaje, interceptación de datos, vigilancia no autorizada.
- **Amenazas activas:** modificación, destrucción o robo directo de información.

### ¿Por Qué Aprenderlo Desde Primer Año?

La seguridad no es una capa que se agrega al final de un proyecto; es una mentalidad que debe estar presente desde el primer día. Cuanto antes se incorporen estos conceptos a la formación de un ingeniero, menor será la probabilidad de que en su vida profesional cometa errores que comprometan la seguridad de terceros.

---

### Diego Flores — Introducción, Rompehielos y ¿Qué es la Ciberseguridad?

| | Aspectos Positivos | Aspectos a Mejorar |
|-|-------------------|-------------------|
| **Interno** | **FORTALEZAS:** La dinámica del rompehielos "¿Quién ha caído?" generó participación inmediata y creó una atmósfera de apertura desde el primer minuto. La explicación de la Tríada CIA fue clara y accesible para audiencias no técnicas. Buena proyección de voz y seguridad al presentar. | **DEBILIDADES:** El tiempo disponible para el subtema 1 fue reducido (5 minutos) tras la introducción, lo que limitó la profundidad de la explicación sobre tipos de amenazas. La transición entre el rompehielos y el contenido técnico podría haberse planificado con mayor fluidez. |
| **Externo** | **OPORTUNIDADES:** La apertura participativa captó la atención del auditorio para toda la sesión, estableciendo el tono positivo que favoreció la receptividad hacia los expositores siguientes. | **AMENAZAS:** El rompehielos dependía de la disposición del público a participar; en grupos más reservados podría no haber funcionado igual. La amplitud del concepto de ciberseguridad en 5 minutos puede generar expectativas que no todos los subtemas alcancen a satisfacer. |

---
## 3.5 Ciberseguridad en el Desarrollo de Software — Expositor 5 - Daniel Estuardo Chicoj Bolaños

### La Responsabilidad del Desarrollador

Los estudiantes de Ingeniería en Sistemas también son **futuros creadores de software**, y eso implica una responsabilidad adicional: el código que escriban puede afectar la seguridad de miles de personas. Un error de validación, una contraseña almacenada en texto plano o una librería desactualizada pueden ser la puerta de entrada a un ataque masivo.

### Desarrollo Seguro de Software (Security by Design)

El **desarrollo seguro de software** es la práctica de integrar la seguridad en cada etapa del ciclo de vida del desarrollo (SDLC), en lugar de tratarla como algo que se agrega al final. Este enfoque se conoce como **Security by Design** o **Shift Left Security**: mover las consideraciones de seguridad hacia el inicio del proceso, donde corregir errores es más fácil y menos costoso.

### OWASP Top 10: Las Vulnerabilidades Más Críticas

La organización **OWASP** publica periódicamente el Top 10 de vulnerabilidades más críticas en aplicaciones web:

**1. Inyección SQL (SQL Injection)**

Ocurre cuando un atacante inserta código SQL malicioso en una entrada del sistema para manipular la base de datos.

*Ejemplo:* En un formulario de login sin validación, escribir `' OR '1'='1` puede conceder acceso sin contraseña válida.

*Prevención:* Usar consultas preparadas (prepared statements) y nunca construir consultas SQL concatenando cadenas de texto directamente.

**2. Cross-Site Scripting (XSS)**

El atacante inyecta código JavaScript malicioso en una página web. Cuando otros usuarios la visitan, el script se ejecuta en su navegador y puede robar cookies, sesiones o redirigirlos a sitios maliciosos.

*Prevención:* Escapar y sanitizar toda entrada del usuario antes de mostrarla. Implementar Content Security Policy (CSP).

**3. Autenticación y Gestión de Sesiones Inseguras**

Mecanismos de login débiles: contraseñas sin hashear, sesiones que no expiran, tokens predecibles o transmisión de credenciales sin cifrado.

*Prevención:* Hashear contraseñas con **bcrypt** o **Argon2**, implementar expiración de sesiones, usar HTTPS en toda la aplicación.

**4. Exposición de Datos Sensibles**

Almacenar o transmitir datos sin cifrado adecuado: contraseñas en texto plano, datos transmitidos por HTTP en lugar de HTTPS.

*Prevención:* Cifrar datos sensibles en reposo y en tránsito. Nunca almacenar contraseñas en texto plano.

**5. Control de Acceso Roto (Broken Access Control)**

Usuarios que acceden a recursos o funciones para los que no tienen permiso (por ejemplo, un usuario normal que accede al panel de administración cambiando la URL).

*Prevención:* Validar permisos en el servidor para cada solicitud; nunca confiar en el cliente para controlar el acceso.

**6. Componentes con Vulnerabilidades Conocidas**

Usar librerías, frameworks o dependencias desactualizadas que tienen vulnerabilidades documentadas.

*Prevención:* Mantener actualizadas todas las dependencias. Usar herramientas como `npm audit`, OWASP Dependency-Check o Snyk.

### Buenas Prácticas de Seguridad en el Desarrollo

- **Nunca confiar en la entrada del usuario:** Toda entrada debe validarse y sanitizarse del lado del servidor.
- **Principio de mínimo privilegio:** Cada componente debe tener solo los permisos estrictamente necesarios.
- **No escribir sistemas de cifrado propios:** Usar librerías criptográficas ya probadas y auditadas.
- **Guardar secretos de forma segura:** Las claves API, tokens y contraseñas nunca deben estar en el código fuente. Usar variables de entorno o gestores de secretos.
- **Usar HTTPS siempre:** Cualquier aplicación web debe cifrar la comunicación entre el navegador y el servidor.
- **Manejar errores correctamente:** Los mensajes de error no deben revelar información sensible del sistema.

### DevSecOps: Seguridad Integrada en el Ciclo de Desarrollo

El concepto de **DevSecOps** integra la seguridad dentro del flujo de trabajo de desarrollo, haciendo que sea responsabilidad de todos los involucrados, no solo de un equipo especializado.

| Herramienta | Tipo | Función |
|-------------|------|---------|
| **SonarQube** | SAST | Analiza el código fuente en busca de vulnerabilidades sin ejecutarlo |
| **OWASP ZAP** | DAST | Prueba la aplicación en ejecución buscando vulnerabilidades |
| **Snyk** | Gestión de dependencias | Detecta vulnerabilidades en dependencias y contenedores |

La seguridad en el software no es una característica que se añade al final: es una mentalidad que se cultiva desde el primer proyecto.

---
### Expositor 5 — Ciberseguridad en el Desarrollo de Software - Daniel Estuardo Chicoj Bolaños

| | Aspectos Positivos | Aspectos a Mejorar |
|-|-------------------|-------------------|
| **Interno** | **FORTALEZAS:** Este bloque diferencia la capacitación de otras genéricas, al conectar el tema directamente con la identidad profesional del público. El ejemplo de inyección SQL con código real hizo tangible una vulnerabilidad que de otro modo sería abstracta. La mención de DevSecOps posiciona al expositor con visión de industria actual. | **DEBILIDADES:** El OWASP Top 10 es muy extenso para 10 minutos; algunas vulnerabilidades quedaron explicadas superficialmente. El concepto de DevSecOps, siendo más avanzado, pudo haber quedado poco claro para estudiantes de primer año. |
| **Externo** | **OPORTUNIDADES:** Al ser primer año, este es el mejor momento para sembrar una mentalidad de seguridad que acompañe al estudiante durante toda su carrera. Este subtema puede ser el más recordado por su relevancia profesional directa. | **AMENAZAS:** Los estudiantes de primer año aún no tienen experiencia en desarrollo, lo que puede dificultar la identificación con escenarios como "validar entradas del usuario" o "usar consultas preparadas". |

---
