# Galería Interactiva — Unidad 4: JavaScript Básico

Este proyecto consiste en una Galería Interactiva de Tarjetas desarrollada con JavaScript puro (Vanilla JS), sin librerías externas. El objetivo es aplicar métodos de selección y manipulación del DOM, el modelo de eventos y características modernas de ES6.

## 🚀 Descripción del Proyecto

La aplicación permite gestionar una colección de tarjetas categorizadas (Tecnología, Ciencia y Arte). Los usuarios pueden agregar nuevas tarjetas mediante un formulario, eliminarlas de forma individual y filtrar la visualización según su categoría. Además, incluye un sistema de retroalimentación visual que cuenta las tarjetas visibles y notifica cuando la galería está vacía.

### Características Principales:

- Creación Dinámica: Generación de elementos HTML article con createElement y appendChild.
- Delegación de Eventos: Gestión de acciones de eliminación mediante un único listener en el contenedor padre.
- Sistema de Filtros: Filtrado en tiempo real utilizando classList y atributos de datos (dataset).
- Estado de Aplicación: Uso de un array de objetos para representar las tarjetas existentes.

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica con header, section, main e inputs de formulario.
- **CSS3:** Estilos personalizados para tarjetas, badges y estados de visibilidad.
- **JavaScript (ES6+):**
  - Arrow functions y Template Literals.
  - Desestructuración de objetos.
  - Métodos de Array como filter y forEach.

## 🚀 Instrucciones de Ejecución

Para visualizar este proyecto de forma local:

1. Clone el repositorio en su máquina local.
2. Abra la carpeta raíz con **Visual Studio Code**.
3. Localice el archivo `index.html`.
4. Haga clic derecho y seleccione **"Open with Live Server"**.
