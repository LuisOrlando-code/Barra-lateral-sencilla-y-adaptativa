# Sidebar #1

Barra lateral (sidebar) responsiva y animada, construida con HTML y CSS puro, con un botón tipo "burger" que expande y contrae el menú mostrando íconos y etiquetas de navegación.

## Demo

Al hacer clic en el botón de menú (☰), la barra lateral se expande de 75px a 240px, revelando el logo y las etiquetas de texto de cada sección con una transición suave.

## Características

- Expansión/contracción animada mediante una sola clase (`open`) en `<body>`.
- Íconos vectoriales con [Boxicons](https://boxicons.com/).
- Tipografía [Ubuntu](https://fonts.google.com/specimen/Ubuntu) vía Google Fonts.
- Separadores visuales (`has-border`) para agrupar secciones del menú.
- Efectos de hover en botones e ícono del menú.
- Sin dependencias de JavaScript externas (vanilla JS).

## Estructura del proyecto

```
├── index.html   # Estructura del sidebar y lógica de toggle
├── style.css    # Estilos y animaciones
└── README.md
```

## Uso

1. Clona o descarga los archivos.
2. Agrega tu propio `logo.png` en la raíz del proyecto (se muestra únicamente cuando el sidebar está expandido).
3. Abre `index.html` en tu navegador.

No requiere instalación ni build step.

## Tecnologías

- HTML5
- CSS3 (transiciones, `box-sizing`, `rgba`)
- JavaScript (vanilla)
- [Boxicons](https://boxicons.com/) v2.1.4 (CDN)
- Google Fonts (Ubuntu, Open Sans, PT Sans)

## Personalización

- **Secciones del menú:** edita los `<button>` dentro de `.sidebar-menu` en `index.html`, cambiando el ícono (`class` del `<i>`, ver catálogo en [boxicons.com](https://boxicons.com/)) y el texto del `<span>`.
- **Ancho expandido:** modifica `body.open .sidebar { width: 240px; }` en `style.css`.
- **Color de fondo:** cambia `background: #3949ab;` en `.sidebar`.
- **Velocidad de animación:** ajusta los valores `0.4s` en las reglas `transition`.

## Notas

Este README documenta la versión corregida del componente: se solucionaron errores en el enlace del CDN de Boxicons, un atributo `class` mal escrito, una propiedad CSS inválida (`text-replace`) y un typo en `padding-bottom`, además de asignarse un ícono distinto a cada sección del menú.

## Pagina
