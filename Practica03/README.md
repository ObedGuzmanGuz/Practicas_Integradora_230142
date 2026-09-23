# Boceto de Modelo Canvas con Archify

**Actividad:** Spotify — Modelo de negocio Canvas  
**Valor:** 10 firmas

## Objetivo

Presentar un análisis académico del modelo de negocio de Spotify con los nueve bloques del Business Model Canvas. No es un Canvas oficial publicado por Spotify. La interfaz permite explorar cada bloque y consultar sus fundamentos, aplicación, ejemplo y relaciones.

## Aplicación elegida

Spotify es una plataforma de audio digital. Es multiplataforma porque permite acceder al servicio en aplicaciones móviles y de escritorio, reproductor web y dispositivos compatibles como televisores y consolas. La disponibilidad concreta varía según el dispositivo y el mercado; las fuentes consultadas se indican en [docs/fuentes.md](docs/fuentes.md).

El Business Model Canvas organiza en nueve bloques la lógica con la que una organización crea, entrega y captura valor. En este boceto se diferencia la información documentada de las interpretaciones del análisis.

## Herramientas y alcance

- **Archify:** se utilizó para generar y validar un diagrama complementario del ecosistema de Spotify (`archify/spotify-ecosystem.html`). Archify en este entorno genera diagramas visuales de arquitectura/relaciones y no una cuadrícula Canvas interactiva con desarrollos A–F por bloque.
- **Codex:** implementó la cuadrícula tradicional, el diseño adaptable, las fichas interactivas, la vista desarrollada continua, la impresión y la documentación. Todo el contenido de bloques reside en una sola estructura de datos de `index.html` y se reutiliza en tarjetas, fichas y vista completa.
- **Tecnologías:** HTML, CSS y JavaScript nativos, sin dependencias ni servidor.

## Cómo abrir y usar

Abre `index.html` directamente en un navegador moderno. También puede publicarse como sitio estático conservando la estructura relativa de carpetas.

- En computadora, deja el cursor sobre un bloque unos 300 ms para una vista previa amplia; haz clic para fijarla. Pulsa **Esc** o el botón de cierre para cerrar.
- Con teclado, recorre las tarjetas con Tab y abre con Intro o Espacio. La ficha fijada mantiene el foco y lo devuelve al bloque al cerrarse.
- En teléfono o pantalla estrecha, toca una tarjeta; la ficha usa una ventana adaptada al viewport.
- **Ver contenido completo** presenta los nueve apartados en secuencia; **Volver al Canvas** regresa al tablero.
- **Imprimir / Guardar como PDF** abre el diálogo de impresión del navegador. Los estilos imprimen las nueve fichas completas y ocultan controles.

## Contenido y evidencia

La carpeta [docs](docs/) documenta el prompt de partida, las observaciones y ajustes, el prompt mejorado y las fuentes consultadas el 23 de septiembre de 2026. Las capturas reales de revisión están en [evidencias](evidencias/): el Canvas completo, la ficha abierta, la vista móvil y `primer-boceto.png`, que conserva el primer planteamiento visual para comparar la revisión. La composición generada con Archify se conserva junto con el JSON y el recibo de su revisión visual en [archify](archify/).

## Revisión ejecutada

En Chrome con DevTools se comprobó la generación de nueve tarjetas; cada tarjeta mostró tres ideas y cada ficha incluyó tres preguntas, cinco o seis puntos de aplicación, ejemplo, relación y referencias. Se abrió y cerró la vista fijada con Escape, se confirmó el retorno de foco y se observó que hover abre sin mover el foco, mantiene el panel al llegar a él y cierra al salir. La vista continua contiene nueve bloques y 63 secciones (A–F más referencias). A 390 px el documento no presentó desbordamiento horizontal. La consola de Chrome no reportó excepciones durante estas comprobaciones.

La activación física con Enter y el diálogo de impresión del navegador quedan pendientes de prueba manual; las tarjetas son botones nativos y los estilos de impresión están incluidos. El recibo de Archify conserva su revisión visual del diagrama en cuatro viewport.

## Estructura

```text
index.html
README.md
docs/
  prompt-inicial.md
  revision.md
  prompt-mejorado.md
  fuentes.md
archify/
  spotify-ecosystem.html
  spotify-ecosystem.architecture.json
  spotify-ecosystem.visual-check.*
evidencias/
  canvas-completo.png
  bloque-propuesta-abierto.png
  vista-movil.png
```
