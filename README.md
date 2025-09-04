# Temario-de-App-Web
Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web


## 1. Introducción al desarrollo web
El desarrollo web consiste en la creación de sitios y aplicaciones accesibles mediante navegadores. Involucra tareas de diseño, programación, y administración de recursos digitales.

### Historia y evolución del desarrollo web
- **1990s:** Nace la World Wide Web con páginas estáticas en HTML. El contenido era fijo y la interacción limitada.
- **2000s:** Surgen CSS y JavaScript, permitiendo mayor dinamismo y estilos. Aparecen lenguajes de servidor como PHP y bases de datos como MySQL, dando lugar a sitios dinámicos.
- **2005:** AJAX permite actualizar partes de la página sin recargar todo el sitio, mejorando la experiencia del usuario.
- **2010 en adelante:** Popularización de frameworks modernos (React, Angular, Vue). Se crean aplicaciones de página única (SPA) y apps progresivas (PWA), acercando la experiencia web a la de aplicaciones nativas.

### Tipos de aplicaciones web
- **Estáticas:** Páginas cuyo contenido no cambia, ideales para sitios informativos o portafolios.
- **Dinámicas:** El contenido varía según la interacción del usuario o datos externos. Ejemplo: tiendas en línea, redes sociales.
- **SPA (Single Page Application):** Una sola página HTML que se actualiza dinámicamente según la navegación del usuario, ofreciendo una experiencia fluida.
- **PWA (Progressive Web Application):** Aplicaciones web que funcionan como apps móviles: pueden instalarse, funcionar offline y enviar notificaciones.


## 2. Arquitectura de aplicaciones web
La arquitectura define cómo se organizan los componentes y cómo interactúan entre sí.

### Cliente-Servidor
- **Cliente:** Es el navegador o dispositivo que solicita información.
- **Servidor:** Es quien procesa la solicitud, accede a los datos y responde al cliente.

### Arquitectura de tres capas
1. **Presentación:** Interfaz que ve el usuario (HTML, CSS, JavaScript).
2. **Lógica:** Procesos y reglas de negocio (PHP, JavaScript del servidor).
3. **Datos:** Almacenamiento y gestión de información (MySQL, bases de datos).

Esta separación facilita la escalabilidad y el mantenimiento de aplicaciones web.

### REST y API-first design
- **REST (Representational State Transfer):** Estilo de arquitectura para diseñar servicios web que permiten la comunicación entre aplicaciones usando HTTP y recursos identificados por URLs.
- **API-first design:** Enfoque donde primero se diseña la API (Interfaz de Programación de Aplicaciones), asegurando que todas las partes del sistema puedan comunicarse eficientemente y facilitando el desarrollo de clientes y servidores independientes.


## 3. Lenguajes y tecnologías fundamentales
- **HTML:** Lenguaje de marcado para estructurar páginas web.
- **CSS:** Hojas de estilo para definir la apariencia visual.
- **JavaScript:** Lenguaje de programación para la interactividad en el navegador.
- **PHP:** Lenguaje de servidor popular para el desarrollo de aplicaciones dinámicas.
- **MySQL:** Sistema de gestión de bases de datos relacional, usado para almacenar y consultar datos.


## 4. Control de versiones
El control de versiones permite gestionar los cambios en el código y colaborar eficientemente.

### Git y GitHub
- **Git:** Sistema de control de versiones distribuido. Permite registrar cambios, revertir errores y colaborar en proyectos.
- **GitHub:** Plataforma web para alojar repositorios Git, facilitar la colaboración y compartir proyectos.

### Flujo de trabajo con ramas
- **Branching:** Crear ramas para desarrollar nuevas funcionalidades o corregir errores sin afectar la rama principal.
- **Merge:** Unir los cambios de una rama al proyecto principal.
- **Pull requests:** Solicitar la integración de cambios realizados en una rama, permitiendo revisiones y comentarios antes de fusionar el código.


Con estos fundamentos, se establece la base para el desarrollo profesional de aplicaciones web modernas y colaborativas.
<img width="198" height="111" alt="image" src="https://github.com/user-attachments/assets/92111caa-7455-4b54-95f1-76328173b21c" />



Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web


## 1. Diseño e implementación del frontend
El **frontend** es la parte visual y de interacción de una aplicación web, lo que ven y utilizan los usuarios.

### Maquetación / Wireframe / Mockup
- **Maquetación:** Proceso de estructurar los elementos visuales de la interfaz utilizando HTML y CSS. Se define la disposición y el diseño de los componentes.
- **Wireframe:** Esquema básico y sin detalles visuales que representa la estructura y distribución de los elementos en la página.
- **Mockup:** Representación más detallada y visual del diseño final, incluyendo estilos, colores y tipografía.

Estos pasos ayudan a planificar la interfaz antes de comenzar la programación.

### API
El frontend suele interactuar con el backend mediante **APIs** (Interfaz de Programación de Aplicaciones), enviando y recibiendo datos en formatos como JSON para mostrar información dinámica y permitir funcionalidades interactivas.


## 2. Diseño e implementación del backend
El **backend** es la parte encargada de la lógica, procesamiento y gestión de datos de la aplicación.

### Servidor
El servidor ejecuta el código backend, recibe y procesa solicitudes de los clientes, y responde con datos o acciones.

### Manejo de peticiones y respuestas HTTP
- El backend recibe **peticiones HTTP** (GET, POST, PUT, DELETE, etc.) desde el frontend o aplicaciones externas.
- Procesa la información, realiza operaciones (consultas, validaciones, cálculos) y envía una **respuesta** (generalmente en formato JSON o HTML).

### Conexión a bases de datos
El backend se conecta a sistemas de almacenamiento para guardar y recuperar datos. Ejemplos:

- **MySQL:** Base de datos relacional, muy usada en aplicaciones web.
- **PostgreSQL:** Base de datos relacional avanzada, soporta funciones complejas.
- **MongoDB:** Base de datos NoSQL orientada a documentos, flexible y escalable.

---

## 3. Bases de datos
Las bases de datos almacenan la información de la aplicación y permiten su gestión eficiente.

### Modelado de datos y relaciones
- Definir las entidades (tablas o colecciones) y sus atributos.
- Establecer relaciones entre entidades (uno a uno, uno a muchos, muchos a muchos).

### ORM (Object Relational Mapping)
- Herramienta que permite manipular la base de datos usando objetos y código (por ejemplo, Sequelize para Node.js, Eloquent para Laravel).
- Facilita la interacción con la base de datos sin escribir consultas SQL manualmente.

### CRUD desde el backend
El backend implementa las operaciones básicas sobre los datos:

- **Create:** Crear nuevos registros.
- **Read:** Leer o consultar información.
- **Update:** Modificar registros existentes.
- **Delete:** Eliminar registros.

---

## 4. Seguridad básica en aplicaciones web
Garantizar la protección de los datos y la integridad de la aplicación es fundamental.

### Validación de formularios
- Comprobar que los datos ingresados por el usuario cumplen con los requisitos antes de procesarlos.
- Evita errores y ataques como inyección de código.

### Autenticación y autorización
- **Autenticación:** Verifica la identidad del usuario (login, contraseñas, tokens).
- **Autorización:** Controla los permisos de acceso a recursos y funcionalidades según el usuario.


Este propósito de aprendizaje te permite entender y desarrollar todos los componentes principales de una aplicación web, asegurando su correcto funcionamiento y seguridad.
<img width="366" height="247" alt="image" src="https://github.com/user-attachments/assets/b1ebb16e-dd4a-41db-b7fc-1c976922f32b" />



Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional


## 1. Integración de frontend y backend

La integración consiste en conectar la interfaz visual (frontend) con la lógica y los datos gestionados en el backend, logrando una aplicación funcional y dinámica.

### Interfaz de usuario Frontend
- El frontend ofrece la experiencia visual e interactiva al usuario.
- Se construye con tecnologías como HTML, CSS y JavaScript, y frameworks como React, Angular o Vue.js.
- Debe ser intuitivo, responsivo y funcional para facilitar el uso de la aplicación.

### Manejo de API
- El frontend se comunica con el backend mediante API (Interfaz de Programación de Aplicaciones).
- Las APIs, generalmente REST, permiten enviar y recibir datos usando solicitudes HTTP (GET, POST, PUT, DELETE).
- La correcta integración asegura que la información se muestra y actualiza dinámicamente según la interacción del usuario.

### Proceso de Solicitud y Respuesta de Backend
- El backend recibe solicitudes del frontend, procesa la lógica y accede a la base de datos si es necesario.
- Envía respuestas estructuradas (habitualmente en formato JSON) al frontend.
- Este ciclo garantiza la interacción fluida entre ambas partes y la actualización constante de la aplicación.


## 2. Almacenamiento en Servidor
El almacenamiento en servidor permite que la aplicación esté disponible en internet y que los datos sean gestionados de forma segura y eficiente.

### Tipos de servidores
- **Servidor compartido:** Recursos compartidos entre varios usuarios, ideal para sitios pequeños.
- **Servidor dedicado:** Recursos exclusivos para un solo usuario o empresa, adecuado para aplicaciones con alta demanda.
- **Servidor virtual (VPS):** Recursos virtualizados, combinan ventajas de dedicados y compartidos.
- **Servidor en la nube:** Escalabilidad y flexibilidad, pago por uso (ejemplo: AWS, Azure, Google Cloud).

### Servidores y servicios de hosting
- **Hosting tradicional:** Espacio en servidores para alojar archivos y datos de la web.
- **Hosting especializado:** Servicios orientados a tecnologías específicas (Node.js, PHP, WordPress, etc.).
- **Servicios gestionados:** El proveedor se ocupa de la administración, seguridad y actualizaciones.

### Proveedores de Servicios de Almacenamiento
- **Amazon Web Services (AWS):** Ofrece servidores, bases de datos, almacenamiento de archivos, etc.
- **Microsoft Azure:** Soluciones en la nube para aplicaciones, bases de datos y almacenamiento.
- **Google Cloud Platform:** Servidores, almacenamiento y herramientas para despliegue.
- **Heroku, Netlify, Vercel:** Plataformas que simplifican el despliegue de aplicaciones web modernas.



## 3. Optimización y rendimiento
Mejorar la eficiencia y velocidad de la aplicación asegura una mejor experiencia para los usuarios y un uso óptimo de los recursos.

### Optimización de recursos (imágenes, scripts)
- **Imágenes:** Comprimir y ajustar el tamaño para reducir tiempos de carga.
- **Scripts:** Minimizar y combinar archivos JavaScript y CSS para disminuir el tráfico y acelerar la carga.
- **Carga diferida (lazy loading):** Cargar recursos solo cuando son necesarios.

### Despliegue de aplicaciones web
- Preparar la aplicación para producción: compilar, empaquetar y configurar variables de entorno.
- Subir la aplicación al servidor o plataforma de hosting.
- Asegurar que el entorno de producción esté seguro y optimizado.

### CI/CD básico
- **CI (Integración Continua):** Automatiza la integración de cambios en el código y realiza pruebas.
- **CD (Despliegue Continuo):** Automatiza el despliegue de la aplicación a servidores de producción.
- Herramientas: GitHub Actions, Jenkins, GitLab CI, CircleCI.

### Documentación del proyecto
- Documentar el código, procesos de despliegue, uso de APIs y dependencias.
- Incluir manuales de instalación, uso y mantenimiento para facilitar la colaboración y el crecimiento del proyecto.



Con estos conocimientos, podrás implementar y desplegar aplicaciones web funcionales, optimizadas y listas para el entorno real.
<img width="219" height="111" alt="image" src="https://github.com/user-attachments/assets/49b915ed-f136-4283-bc46-4ee9c0be17f8" />

