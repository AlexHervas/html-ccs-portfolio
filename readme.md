# Práctica de Fundamentos Web, HTML y CSS.
## Portfolio Personal

Este proyecto consiste en la creación de un **portfolio personal** (o de un personaje de ficción) utilizando exclusivamente **HTML5 y CSS3**, sin el uso de librerías o frameworks externos. El objetivo es construir un sitio web responsivo que se adapte a diferentes dispositivos y resoluciones, utilizando únicamente técnicas nativas de CSS como **media queries**, **transiciones**, **animaciones** y **validación de formularios**.

## Consideraciones Generales
- **Sin librerías o frameworks externos**: No se permite el uso de frameworks como Bootstrap o similares.
- **CSS personalizado**: Se debe crear una o más hojas de estilo CSS para definir el diseño de la web.
- **Compatibilidad**: La web debe visualizarse correctamente en los navegadores actuales (Google Chrome, Mozilla Firefox, Microsoft Edge).
- **Sin JavaScript**: No se permite el uso de JavaScript para la funcionalidad o interactividad.

## Requisitos del Proyecto

### 1. **Header y Barra de Navegación**
- El sitio debe incluir un **header** con una barra de navegación que enlace a las diferentes secciones del portfolio.
- Los enlaces deben incluir un efecto `hover` con **transición suave**. 
- En la versión móvil, la barra de navegación no es necesaria.

### 2. **Sección de Descripción Personal**
- Incluir una sección con una **descripción** personal y una lista de **habilidades** visualizadas como **barras de progreso animadas** usando CSS.

### 3. **Banner con Imagen de Fondo**
- El portfolio debe tener un **banner** con una imagen de fondo que cambie en función del tamaño de la pantalla (responsive).
- Se utilizarán **media queries** para cambiar la imagen en pantallas móviles.

### 4. **Formulario de Contacto**
- El formulario debe contener los siguientes campos con validación HTML:
  - **Nombre** (requerido)
  - **Apellidos** (requerido)
  - **Teléfono** (requerido)
  - **Pregunta "¿Cómo me conociste?"** con opciones de radio (requerido):
    - Universidad
    - Keepcoding Kick-off
    - Colegio
    - En GitHub
  - **Tag de GitHub** (validado con una expresión regular `^@[^\s]+` - @username)
  - **Mensaje adicional** (máx. 180 caracteres, requerido)
  - Checkbox para la suscripción a la newsletter.
  - Botones de **guardado** y **reset**.

### 5. **Footer**
- Incluir un footer con **links** a las redes sociales (links a recursos externos).

### 6. **Página de Video**
- Crear una página adicional que contenga un **video** que se reproduzca automáticamente al cargar la página, con una animación de **fadeIn**.

### 7. **Página de Proyectos**
- Crear una página que muestre los **proyectos personales** en un formato de **grid**, con un diseño responsivo.

## Opcionales
- **Menú burger** con solo CSS utilizando un input checkbox.
- **Despliegue** en **GitHub Pages**.
- Páginas de error personalizadas para:
  - **404** (página no encontrada)
  - **500** (error del servidor)

## Detalles de Implementación
- Se debe respetar la semántica del contenido, utilizando correctamente las etiquetas HTML5.
- La web debe ser **Mobile First**, priorizando el diseño para dispositivos móviles antes de las pantallas más grandes.
- Las **animaciones e interactividad** deben implementarse únicamente con CSS.
- La entrega se realizará a través de GitHub, y se valorará positivamente un buen uso de commits.

## Instrucciones para la Evaluación
Para facilitar la evaluación, incluir este **README** con toda la información detallada y, opcionalmente, desplegar la web en GitHub Pages.