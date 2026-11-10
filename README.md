```text
amac-web/
├── index.html
├── vacante.html
├── login.html
├── registro-candidato.html
├── registro-empresa.html
├── mis-solicitudes.html
├── empresa-vacantes.html
├── solicitudes-recibidas.html
├── css/
│   ├── variables.css    ← colores, fuentes, espaciados (de Figma)
│   ├── base.css         ← reset, body, tipografía, enlaces, foco
│   ├── layout.css       ← header, footer, contenedor, grids
│   └── componentes.css  ← botones, tarjetas, formularios, etiquetas de estatus
├── img/
└── README.md
```

## Uso

Abre `index.html` en un navegador para recorrer el prototipo. Los formularios
son demostrativos y no envían información a un servidor; sus campos incluyen
validación nativa, etiquetas accesibles y controles de teclado.

## Vistas incluidas

- Listado y detalle de vacantes.
- Inicio de sesión y registro de candidatos y empresas.
- Seguimiento de solicitudes del candidato.
- Panel de empresa con vacantes y solicitudes recibidas.
- Ayuda AMAC visible en el pie de cada página.

## Integrantes

- Ernesto Vega Bortoni 644175: estructura inicial, contenido de las seis páginas obligatorias, estilos base y correcciones de accesibilidad en formularios y pie de página.

## Colores y tipografía

Variables de `css/variables.css`:

- `--color-primario` y `--color-texto`: `#202945`.
- `--color-fondo`: `#f5f6f8`.
- `--color-superficie`: `#ffffff`.
- `--color-borde`: `#aab2c0`.
- `--color-enlace`: `#174ea6`.
- `--color-exito`: `#176b45`.
- `--color-peligro`: `#9b1c1c`.
- `--fuente-base`: Work Sans, Arial, sans-serif. Sin descargar fuentes externas.
- `--texto-base`: `1.125rem`; `--texto-h1`: `1.75rem`; `--texto-h2`: `1.25rem`.

## Componentes reutilizables

- `.boton`, `.boton-secundario` y `.boton-peligro`: botones.
- `.tarjeta`: vacantes y solicitudes.
- `.formulario` y `.grupo-campos`: formularios.
- `.estado`, `.estado-aceptada` y `.estado-rechazada`: estados de solicitudes.
- `.filtros`: buscador y filtros de vacantes.
