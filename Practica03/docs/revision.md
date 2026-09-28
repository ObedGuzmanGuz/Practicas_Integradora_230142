# Revisión del primer resultado y mejoras

**Fecha de revisión:** 23 de septiembre de 2026.

## Observaciones del primer resultado

La primera propuesta visual servía como un boceto de tarjetas, pero al compararla con los requisitos se identificaron carencias concretas:

1. Las tarjetas presentaban ideas breves sin desarrollar las seis partes solicitadas (definición, contenido esperado, preguntas, aplicación, ejemplo y relación).
2. No había una ficha amplia que permitiera leer el contenido íntegro, ni estado fijado mediante clic, cierre con Escape o flujo de foco para teclado.
3. La composición inicial de tarjetas no daba suficiente énfasis a la propuesta de valor y no representaba con fidelidad las posiciones tradicionales del Canvas.
4. Faltaban la vista continua, los estilos de impresión, las distinciones entre hechos e interpretaciones y las fuentes concretas.
5. El primer control visual del diagrama auxiliar de Archify detectó un desbordamiento vertical de 16 px en el viewport 1440 × 900. Se corrigió su viewBox y el recibo final de Archify registró estado “pass” en cuatro tamaños de viewport.
6. La primera captura estrecha mostró a la vez “Abrir ficha” y “Tocar para abrir”. Se ajustó la hoja de estilos para que en pantallas pequeñas aparezca solo la indicación táctil.

## Cambios aplicados

- Se reemplazó el boceto de tarjetas por la cuadrícula tradicional de nueve bloques, con la propuesta de valor ocupando el centro y dos filas.
- Se incorporó una estructura de datos única con los mismos seis apartados para cada bloque; la vista previa, la ficha y el dossier se generan desde esos datos.
- Se añadieron fichas anchas con desplazamiento, hover demorado, apertura fijada, controles de cierre y Escape, comportamiento táctil, administración de foco y movimiento reducido.
- Se hicieron explícitos los hechos respaldados y las inferencias del análisis; se precisó que artistas y creadores pueden participar del ecosistema sin ser automáticamente clientes que pagan.
- Se añadieron diseño para pantalla estrecha, vista desarrollada continua, retorno al Canvas, impresión y enlaces de referencia.
- Se agregó el contexto de la actividad: “Boceto de Modelo Canvas con Archify” y “10 firmas”.

## Evidencia y límites de la revisión

Las imágenes `canvas-completo.png`, `bloque-propuesta-abierto.png` y `vista-movil.png` corresponden a capturas de la versión final en Chrome. La comprobación con Chrome DevTools registró nueve tarjetas y 38 vínculos de referencia; en cada bloque halló tres ideas preliminares, tres preguntas, entre cinco y seis puntos de aplicación, ejemplo, relación y fuentes. La vista continua produjo nueve apartados y 63 secciones (seis partes A–F y la sección de referencias por bloque). El hover abrió la vista transitoria en 300 ms sin cambiar el foco; desplazarse al panel la mantuvo abierta y salir la cerró. Escape cerró la ficha fijada y devolvió el foco al bloque. No se reportaron excepciones de JavaScript. A 390 px de ancho, el documento midió 390 px sin desbordamiento horizontal.

La activación Enter mediante eventos de teclado sintéticos de DevTools no llegó a activar la tarjeta; el navegador sí expone cada tarjeta como botón nativo enfocable, pero esa activación física con teclado queda pendiente de una comprobación manual. Tampoco se ejecutó el diálogo físico de impresión/PDF; la vista y las reglas CSS de impresión están implementadas. El diagrama Archify es un complemento visual del ecosistema, no la interfaz del Canvas. Esta actividad es un análisis académico, no una publicación oficial de Spotify.
