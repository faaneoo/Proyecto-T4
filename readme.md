# Portafolio Profesional - Desarrollo Web

**Alumno:** Rafael de la Torre  
**Asignatura:** Desarrollo de Interfaces Web  
**Tecnologías:** HTML5, CSS3 (Sin JavaScript)

---

## Descripción del Proyecto

Este proyecto consiste en la elaboración de un portafolio personal responsive utilizando únicamente estándares web nativos (**HTML y CSS**), sin el uso de frameworks (como Bootstrap) ni lenguajes de programación (como JavaScript).

El objetivo es demostrar el dominio de CSS moderno, incluyendo **animaciones basadas en scroll**, transiciones de vista, maquetación con Grid/Flexbox y optimización de recursos gráficos.

### Enlace al despliegue (Demo)

Puedes ver el proyecto en funcionamiento aquí:
**[https://proyecto-t4.vercel.app]**

---

## Características Técnicas Destacadas

Cumpliendo con la rúbrica del proyecto, se han implementado las siguientes funcionalidades:

- **Modo Claro/Oscuro Automático:** Uso de variables CSS (`:root`) y la media query `@media (prefers-color-scheme: dark)` para adaptar el tema según la configuración del sistema del usuario.
- **Animaciones Avanzadas (Scroll-Driven):** Las tarjetas de proyectos aparecen y escalan suavemente al entrar en el viewport utilizando `animation-timeline: view()`.
- **Objeto 3D CSS:** Un cubo giratorio en la sección Hero creado exclusivamente con `transform-style: preserve-3d` y keyframes.
- **Imágenes Optimizadas:** Uso de la etiqueta `<picture>` para servir formatos de nueva generación (`.avif`, `.webp`) con fallback a `.png`.
- **Diseño Responsive:** Adaptable desde móviles hasta pantallas ultra-panorámicas.

---

## Capturas de Pantalla

### Versión Escritorio

_Vista general de la estructura y distribución en pantallas grandes._

_(Nota: Si no carga la imagen, asegúrate de que el archivo 'desktop.png' está en la carpeta 'capturas')_

### Versión Móvil

_Adaptación de columnas, menú y tamaños de fuente para dispositivos móviles._

---

## Estructura del Proyecto

El código se ha organizado buscando la eficiencia y la semántica:

```text
/portafolio
│
├── index.html        # Estructura semántica (Header, Hero, Grid, Form)
├── estilos.css       # Estilos, variables, animaciones y responsive
├── README.md         # Documentación del proyecto
│
├── /images           # Recursos gráficos (iconos SVG, imágenes optimizadas)
│   ├── FotoPersonal.png
│   ├── Frontend.avif
│   ├── icon-html.svg
│   └── ...
│
└── /capturas         # Imágenes para este documento README
    ├── desktop.png
    └── mobile.png
```
