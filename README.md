# PROYECTO 02 — Landing Page del Museo Presley Norton

**ESCUELA SUPERIOR POLITÉCNICA DEL LITORAL**
**FACULTAD DE INGENIERÍA EN ELECTRICIDAD Y COMPUTACIÓN**

| | |
|---|---|
| **Fecha** | 16 de octubre de 2026 |
| **Materia** | Diseño de aplicaciones web y móviles |
| **Integrantes** | William Pacalla · David Olvera |
| **Repositorio** | https://github.com/williamp11/museo-website |

## Contenido

1. [Análisis](#análisis)
2. [Planificación](#planificación)
3. [Diseño](#diseño)
4. [Implementación](#implementación)
5. [Despliegue](#despliegue)
6. [Bibliografía](#bibliografía)

---

## Análisis

### 1. Actividad seleccionada

**Actividad:** visita al Museo Presley Norton de Guayaquil.

**¿En qué consiste la actividad?**
Consiste en recorrer un museo cultural y arqueológico de entrada gratuita. Los visitantes observan una colección de más de 8.000 piezas de cerámica, hueso y piedra de la costa ecuatoriana, entre ellas las figurinas de la cultura Valdivia, organizadas por periodos históricos (Formativo, Desarrollo Regional e Integración).

**¿Dónde se desarrolla?**
En el centro de Guayaquil (Av. 9 de Octubre y Carchi), dentro de la Villa Rosa Herlinda, una casona de estilo andaluz construida en la década de 1940 y considerada patrimonio arquitectónico de la ciudad.

**¿A qué personas o grupos de la comunidad involucra?**
A visitantes de distintas edades (estudiantes, familias, adultos mayores, turistas y ciudadanos en general), al personal del museo (guías y administrativos) y a investigadores o estudiantes interesados en historia, arqueología y arquitectura.

**¿Por qué resulta relevante o interesante para la comunidad?**
Porque permite conocer y valorar la historia y la identidad cultural de la región, es gratuito y por eso accesible a toda la población, y reúne patrimonio arqueológico y arquitectónico en un solo lugar. Además, se puede medir y mejorar con datos reales: cuántas personas lo visitan, qué opinan y qué dificultades encuentran.

### 2. Datos recopilados

Los datos se obtuvieron mediante una **entrevista estructurada** a visitantes del museo, aplicada el miércoles 7 de octubre de 2026.

| Bloque de la entrevista | Tipo de dato | Qué se obtiene |
|---|---|---|
| Datos generales | Categórico | Rango de edad, relación con la actividad, tiempo de relación con el museo |
| Preguntas cerradas (6) | Cuantitativo | Frecuencia de visitas, beneficio para la comunidad, recomendación, accesibilidad, calificación de la experiencia, medio por el que conoció el museo |
| Preguntas abiertas (4) | Cualitativo | Lo que más disfrutan, aspectos positivos, dificultades y propuestas de mejora |
| Registro del entrevistador | Cualitativo | Conclusión breve sobre necesidades e intereses de cada persona |

**Consideración ética:** se informó el propósito académico, se pidió consentimiento y no se publican nombres, fotografías ni datos personales.

### 3. Organización del contenido de la landing page

La landing page es una página única con navegación por anclajes. Está organizada en las siguientes secciones:

| # | Sección (ancla) | Propósito | Datos que presenta | Componente de Spectral |
|---|---|---|---|---|
| 1 | **Header y navegación** (`#header`, `#menu`) | Permitir moverse por el sitio de forma rápida e intuitiva | Nombre del museo y menú con cinco enlaces: Inicio, Sobre el Museo, Colecciones Destacadas, Visita y Horarios y Contáctanos | Encabezado con botón de menú que abre un panel lateral |
| 2 | **Banner / Inicio** (`#banner`) | Captar la atención y dar una bienvenida institucional clara | Título «Museo Presley Norton», frase de presentación («Patrimonio arqueológico, histórico y cultural de Guayaquil»), fotografía de portada y botones «Visítanos» y «Conoce Más» | Banner principal con imagen de fondo |
| 3 | **Sobre el Museo** (`#one`) | Contextualizar el origen, el valor histórico y la sede del museo | Espacio de acceso gratuito, Villa Rosa Herlinda (estilo andaluz, años 40), más de 8.000 objetos de cerámica, piedra y hueso de las culturas de la costa ecuatoriana | Bloque de texto centrado (`wrapper style1`) |
| 4 | **Colecciones Destacadas** (`#two`) | Mostrar de forma visual las principales muestras y ambientes del museo | Tres bloques con foto y texto: Patrimonio Arquitectónico (Villa Rosa Herlinda), Figurinas de la Cultura Valdivia e Inicio y Desarrollo de la Cerámica | Filas alternas de imagen y texto (spotlights) |
| 5 | **Visita y Horarios** (`#three`) | Dar la información práctica para la visita presencial | Entrada gratuita, horario de martes a domingo de 09:00 a 17:00 y ubicación (Av. 9 de Octubre y Carchi, Guayaquil) | Bloque de texto centrado (`wrapper style4`) |
| 6 | **Contacto** (`#contact`) | Ofrecer vías de comunicación directa para consultas e instituciones | Correo electrónico y teléfono de la administración del museo | Bloque de texto centrado (`wrapper style3`) |
| 7 | **Footer** | Cerrar el sitio con la información institucional y los créditos | Nombre del museo, Ministerio de Cultura y Patrimonio del Ecuador, dirección, derechos de autor y crédito a HTML5 UP | Pie de página |

### 4. Público objetivo

- **Visitantes y ciudadanía:** buscan información práctica (horarios, ubicación, entrada gratuita) y conocer qué ofrece el museo.
- **Personal del museo y comunidad interesada:** pueden usar los resultados de la entrevista para mejorar la experiencia del visitante.
- **Docente y compañeros:** necesitan entender rápido qué se hizo y qué se encontró.

---

## Planificación

### Comparación de plantillas de HTML5 UP

Se compararon tres plantillas gratuitas, todas con licencia Creative Commons Attribution 3.0: **Spectral**, **Massively** y **Editorial**. El criterio fue qué tan bien se adaptan a una landing page institucional, sobria y fácil de leer en cualquier dispositivo.

| Criterio | **Spectral** (seleccionada) | **Massively** | **Editorial** |
|---|---|---|---|
| **Estructura** | Una sola página con secciones que se recorren de arriba hacia abajo: banner grande y bloques alternados de imagen y texto; incluye páginas adicionales de contenido genérico y de elementos | Diseño orientado a artículos, con una imagen de fondo gigante y publicaciones en secuencia | Estilo blog o revista, con barra lateral y publicaciones en tarjetas |
| **Navegación** | Menú de estilo móvil (botón de hamburguesa que abre un panel) más enlaces internos por anclajes (`#id`) con desplazamiento suave | Barra superior con menú desplegable; navega entre publicaciones | Barra lateral que se oculta o se fija, con menú tipo acordeón |
| **Diseño** | Grande, moderno y en bloques; contraste entre secciones oscuras y claras y poco texto por bloque | Texto extenso sobre fondos grandes, con efecto parallax y animaciones al hacer scroll | Limpio y de tipo editorial, pensado para mucha lectura |
| **Adaptabilidad** | Totalmente responsiva (usa flexbox) | Responsiva; los efectos de scroll dependen de JavaScript y requieren más cuidado en celular | Responsiva; la barra lateral cambia de comportamiento en pantallas pequeñas |
| **Facilidad de personalización** | Alta: bloques repetibles, elementos ya estilizados y Sass opcional (se puede editar solo con CSS) | Media: los efectos y el fondo grande dificultan los cambios | Media: la barra lateral y el menú añaden complejidad |
| **Encaje con el evento** | Muy alto: presenta la información del museo en bloques claros y visuales | Medio: más orientada a narrar que a mostrar datos | Medio-alto: buena para mucho texto, pero el contenido del museo es breve |

*La comparación se basa en la descripción oficial de cada plantilla y en sus demos.*

### Justificación de la elección: **Spectral**

1. **Es una landing page.** El proyecto necesita una sola página que presente el museo de forma rápida, y Spectral está pensada para eso: banner de entrada y secciones que se recorren de arriba hacia abajo.
2. **Se ajusta a la información del evento.** El contenido del museo es visual y se divide en bloques cortos (el museo, las colecciones, la visita), y los bloques alternados de imagen y texto lo presentan de forma natural.
3. **Facilita la lectura institucional.** Permite intercalar texto informativo con fotografías de las colecciones y mantiene un menú de hamburguesa que no distrae, con una estética sobria y profesional.
4. **Navegación sencilla.** Los anclajes internos con desplazamiento suave y el menú de estilo móvil funcionan igual en cualquier dispositivo.
5. **Menos riesgo que Massively.** Evita el parallax y los efectos pesados de scroll, que pueden dificultar la lectura.
6. **Más simple que Editorial.** El contenido del museo es breve y no necesita barra lateral ni estructura de revista.
7. **Fácil de personalizar.** Sus bloques se repiten y se editan con facilidad, lo que permitió adaptarla rápido a la información del museo.

---

## Diseño

- **Formato:** landing page de una sola página con navegación por anclajes.
- **Estilo visual:** sobrio, institucional y limpio. Se eliminaron los íconos innecesarios de la plantilla para concentrar la atención en el valor histórico del contenido.
- **Fotografía:** imágenes de la Villa Rosa Herlinda (`villa.jpg`), de las vitrinas con figurinas Valdivia (`valdivia.png`) y de cerámica ancestral (`ceramica.jpg`), más una imagen de portada (`banner.jpg`) con una capa oscura semitransparente que mejora la lectura del texto. La fotografía histórica de la villa lleva la marca de agua «Guayaquil, Estampas y Costumbres de mi Tierra».
- **Paleta y tipografía:** se conservan los colores y la tipografía de Spectral (turquesa, gris azulado oscuro y morado en los bloques, rojo en los botones), que mantienen un buen contraste entre texto y fondo.
- **Accesibilidad:** idioma de la página declarado (`lang="es"`), texto alternativo descriptivo en todas las imágenes, jerarquía de títulos, estructura con `<main>` y zoom permitido en celulares.
- **Usabilidad:** menú claro con cinco opciones, textos cortos en lenguaje sencillo, botones visibles («Visítanos» y «Conoce Más») y lectura cómoda en celular.

---

## Implementación

**Tecnologías:** HTML5, CSS3 y JavaScript con jQuery (incluido en la plantilla).

- **HTML5 semántico:** se usan las etiquetas `<header>`, `<nav>`, `<main>`, `<section>` y `<footer>`. La página declara su idioma, tiene un título y una descripción propios y no bloquea el zoom.
- **Anclajes internos:** `#banner`, `#one`, `#two`, `#three` y `#contact`, con desplazamiento suave.
- **CSS:** estilos en `assets/css/main.css`; el banner usa `images/banner.jpg` con una capa oscura del 50 %, y los bloques usan las clases `wrapper style1` a `style4` de la plantilla.
- **JavaScript:** `assets/js/main.js` gestiona el menú lateral, el desplazamiento suave y las animaciones de carga, con jQuery, Scrollex, Scrolly y Breakpoints.

**Estructura del repositorio:**

```
museo-website/
├── index.html          # landing page del museo
├── generic.html        # página genérica de la plantilla
├── elements.html       # elementos de la plantilla
├── assets/
│   ├── css/            # main.css, noscript.css, Font Awesome
│   ├── js/             # jQuery, scrollex, scrolly, main.js, util.js
│   ├── sass/           # fuentes Sass (opcional)
│   └── webfonts/       # íconos
├── images/             # banner, villa, valdivia, ceramica
├── LICENSE.txt
├── README.txt          # README original de HTML5 UP
└── README.md           # esta documentación
```

---

## Despliegue

- **Control de versiones:** el proyecto está alojado en GitHub: https://github.com/williamp11/museo-website
- **Publicación:** GitHub Pages. Sitio publicado: (https://williamp11.github.io/museo-website/)

---

## Bibliografía

- HTML5 UP. (s. f.). *Spectral*. https://html5up.net/spectral
- HTML5 UP. (s. f.). *Massively*. https://html5up.net/massively
- HTML5 UP. (s. f.). *Editorial*. https://html5up.net/editorial
- HTML5 UP. (s. f.). *Licencia (CCA 3.0)*. https://html5up.net/license
- Wikipedia. (s. f.). *Museo Presley Norton*. https://es.wikipedia.org/wiki/Museo_Presley_Norton
- Red de Museos del Ecuador. (s. f.). *Museo Presley Norton*. https://museos.culturaypatrimonio.gob.ec/redmuseos/index.php/museos/itemlocales/itemmuseopresley
- Diario Expreso. (s. f.). *La arqueología costeña se muestra en antigua casa*. https://www.expreso.ec/actualidad/arqueologia-costena-muestra-antigua-casa-74986.html
- W3C. (2023). *Web Content Accessibility Guidelines (WCAG) 2.2*. https://www.w3.org/TR/WCAG22/

---

*Plantilla del sitio: Spectral, diseñada por HTML5 UP (https://html5up.net), bajo licencia Creative Commons Attribution 3.0. Íconos: Font Awesome. Scripts: jQuery y Scrollex.*
