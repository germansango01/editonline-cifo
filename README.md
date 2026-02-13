# 📄 Proyecto EDITOLINE — Editorial de la Frontera Literaria

---

## 🌵 EDITOLINE
**Proyecto de maquetación avanzada** que fusiona la estética *Western Clásica* con principios de diseño moderno, desarrollado íntegramente con HTML5 y CSS3 sin dependencias de JavaScript.

---

## 📌 Descripción
EDITOLINE es una plataforma web para autores noveles que utiliza un enfoque **Mobile First**. El sitio demuestra el potencial del CSS moderno para gestionar layouts complejos, tipografías fluidas y estados interactivos, manteniendo una identidad visual coherente inspirada en los antiguos diarios y carteles del oeste americano.

### 🎨 Concepto: "Western Moderno"
* **Identidad:** Uso de tipografías display (`Rye`) y de lectura (`Lora`) para evocar elegancia rústica.
* **Interfaz:** Bordes redondeados (`12px`), paleta de colores tierra (`#a34b2d`, `#f2ede4`) y sombras de elevación para una experiencia táctil y moderna.

---

## 🎯 Objetivos del Proyecto
- **Maquetación Semántica:** Estructura limpia utilizando etiquetas HTML5 para mejorar el SEO y la accesibilidad.
- **Layout Híbrido:** Uso de **CSS Grid** para la arquitectura global y **Flexbox** para componentes dinámicos.
- **Interactividad CSS:** Microinteracciones en botones, tarjetas y carteles "Wanted" mediante transformaciones y transiciones.
- **Navegación Avanzada:** Implementación de un **Sticky Sidebar** funcional en la sección de blog.

---

## 🛠 Tecnologías Utilizadas
- **HTML5:** Marcado semántico avanzado (`<main>`, `<article>`, `<aside>`, `<nav>`).
- **CSS3 Avanzado:**
  - **Custom Properties:** Gestión centralizada de colores, espaciado y sombras.
  - **Tipografía Dinámica:** Uso de `clamp()` para una escalabilidad perfecta entre dispositivos.
  - **Sticky Positioning:** Navegación lateral persistente en artículos largos.
  - **Filtros y Efectos:** Uso de `sepia()`, `linear-gradient()` y `background-attachment: fixed`.

---

## 📂 Estructura del Sitio
* **Inicio (`index.html`):** Landing page con Hero dinámico y sección de contacto.
* **Catálogo (`catalago.html`):** Sistema de rejilla para libros con filtros visuales.
* **Nuestra Esencia (`nosotros.html`):** Presentación de autores mediante "Wanted Posters" interactivos.
* **Blog (`blog.html`):** Listado de noticias con layout de dos columnas y sidebar fijo.
* **Artículo (`articulo.html`):** Detalle de lectura optimizado con efecto visual de fondo fijo.

---

## 🎨 Decisiones Técnicas Relevantes



1. **Lógica del Sidebar Sticky:** Para que el sidebar se mantuviera pegado al hacer scroll en el blog, se aplicó `align-items: flex-start` al contenedor flex. Esto evita que el sidebar se estire hasta el fondo, permitiendo que `position: sticky` tenga "aire" para desplazarse dentro del contenedor padre.

2. **Tipografía Fluida:**
   Se definió una escala tipográfica basada en variables:
   `--font-h1: clamp(2.8rem, 2rem + 5vw, 5.5rem);`
   Esto garantiza que el título sea impactante en escritorio pero legible y proporcionado en móviles sin necesidad de múltiples Media Queries.

3. **Wanted Posters (Hover Effects):**
   En la sección de autores, se utilizó una combinación de `filter: sepia(1)` y `transform: rotate()` que se "limpian" al hacer hover, recreando la sensación de encontrar un cartel antiguo que cobra vida al interactuar con él.

---

## 📊 Validación
- **HTML5:** Validado con W3C Service. ✔️
- **CSS3:** Validado, sin redundancias y con variables centralizadas. ✔️
- **Responsive:** Mobile First verificado en dispositivos desde 320px hasta 1920px. ✔️

---

## 🚀 Mejoras Futuras
- **Dark Mode:** Variante "Midnight Canyon" basada en variables de color.
- **Filtros Funcionales:** Implementación de lógica de búsqueda con JS o filtrado por checkboxes.
- **Accesibilidad:** Mejorar el etiquetado ARIA para lectores de pantalla.

---

## 👨‍💻 Autor
**Germán Contreras** *Curso de Desarrollo Web* *CIFO La Violeta | 2026*

---