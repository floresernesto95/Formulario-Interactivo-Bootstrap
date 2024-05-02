# Formulario Interactivo con Bootstrap

Este proyecto es un **Formulario Interactivo** construido con **HTML5, CSS3 y JavaScript**, utilizando el marco de trabajo **Bootstrap 5.3** para una experiencia de usuario elegante y adaptable. Aquí está su funcionalidad y características clave:

- **Diseño y Usabilidad:**
  - El formulario cuenta con un diseño limpio y moderno, organizado en un contenedor Bootstrap con una disposición de fila de 3 columnas, para una estructura visualmente coherente.
  - Campos de entrada esenciales como "Nombre", "Apellido" y "Nivel Educativo" están disponibles, con validaciones implementadas en JavaScript para asegurar que la información ingresada es válida.

- **Validación y Accesibilidad:**
  - El formulario valida automáticamente los campos requeridos, alertando al usuario si algún campo no cumple con los criterios especificados, asegurando la integridad de la entrada de datos.
  - Las etiquetas HTML vinculadas a los campos de entrada mejoran la accesibilidad, permitiendo a los usuarios de lectores de pantalla navegar por el formulario de manera efectiva.

- **Dropdowns Dinámicos:**
  - Los menús desplegables "País" y "Provincia" están integrados con una funcionalidad JavaScript para cargar provincias de acuerdo con el país seleccionado, proporcionando una experiencia interactiva.
  - Las opciones de provincia se actualizan en tiempo real, mejorando la eficiencia y precisión de la selección de datos.

- **Envío y Procesamiento:**
  - La función de JavaScript `sendForm()` maneja la lógica de envío del formulario, previniendo el envío si no se cumplen los criterios de validación.
  - Los datos son enviados a la página "message.html", siguiendo una estructura GET, facilitando su manejo y visualización posterior.

- **Tecnologías Clave:**
  - **Bootstrap 5.3** para estilos y componentes UI.
  - **JavaScript** para manejo de eventos, validación y manipulación DOM.
  - **HTML5 y CSS3** para estructura y presentación del documento.
