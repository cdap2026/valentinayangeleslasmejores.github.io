# Las proteínas y su conformación

Página web de un solo archivo (`proteinas-conformacion.html`) para estudiar las proteínas y sus niveles de estructura, con un cuestionario final de 20 preguntas.

## Contenido

1. Del aminoácido al polipéptido y el enlace peptídico.
2. Los cuatro niveles de estructura (primaria, secundaria, terciaria y cuaternaria), con esquema interactivo.
3. Enlaces e interacciones que mantienen la forma de la proteína.
4. Proteínas globulares y fibrosas.
5. Desnaturalización y chaperonas.
6. Cuestionario de 20 preguntas con retroalimentación.

## Cómo usarla

- Abre `proteinas-conformacion.html` en cualquier navegador. No necesita internet ni instalación.
- Funciona en computador, tableta y celular.
- Para compartirla, envía el archivo o súbelo a una plataforma que admita HTML.

## Cuestionario

- 20 preguntas de selección múltiple con única respuesta.
- **Opciones mezcladas:** en cada carga de la página la respuesta correcta queda 5 veces en cada letra (A, B, C y D), en orden aleatorio. Así no se repite la misma letra y cada estudiante ve una versión distinta.
- Al calificar se marcan las respuestas correctas e incorrectas y se muestra una explicación breve por pregunta.
- La nota se calcula sobre 5.0 (`correctas / 20 × 5`).
- Rangos de desempeño: Superior 4.6–5.0, Alto 4.0–4.5, Básico 3.0–3.9, Bajo por debajo de 3.0.
- El botón **Nuevo intento** vuelve a mezclar las opciones.

## Cómo editar

- **Preguntas:** están en el arreglo `Q` dentro de la etiqueta `<script>`. Cada una tiene el formato `[pregunta, correcta, distractor1, distractor2, distractor3, explicación]`. La respuesta correcta siempre se escribe en la segunda posición; el código la reubica al cargar.
- **Rangos de desempeño:** se ajustan en la línea que calcula `lv` dentro de la función del botón *Calificar*.
- **Colores:** variables `--n` (azul marino), `--g` (dorado) y `--c` (celeste) al inicio del estilo.

## Nota

Los resultados no se guardan ni se envían a ningún servidor. Si se necesita registro, el estudiante puede escribir su nombre y enviar una captura del resultado.
