# SerFlex · Paquete 07: Gráficos de instrucciones

**Este grupo se ha preparado a partir de la guía ilustrada original, sin regenerar ni modificar sus personajes ni su contenido.**

Se incluyen paneles completos como referencias visuales y recortes detallados de teclas, botones táctiles, poses y ejemplos interactivos. La fuente es una única composición ilustrada: varios fragmentos incluyen partes del fondo o de la cartela original y **no son sprites limpios de fondo completamente transparente**.

## Organización
- `01_paneles_referencia`: láminas con texto ya incrustado; usarlas como referencia o ayuda visual estática, no como formulario interactivo.
- `02_teclas_teclado`: A, D, flechas, W, espacio, E y Esc.
- `03_controles_tactiles`: dirección, salto, interactuar y pausa.
- `04_demostraciones`: Milo corriendo y saltando, máquina interactiva, tres pasos y banderín.
- `05_iconos_instrucciones`: iconos destacados.

## Uso correcto con Canva Code
1. El panel «Instrucciones» definitivo debe tener textos en HTML/CSS, no incrustados en los PNG.
2. Las teclas y botones extraídos son gráficos, no eventos activos: conectar controles mediante HTML/JavaScript.
3. Las demostraciones pueden usarse como ilustraciones en ventanas de ayuda; no usarlas como sprites de la física del juego. Para eso utilizar los sprites de Milo del grupo 01.
4. Los paneles completos contienen textos de ejemplo, y puede haber repeticiones o errores de legibilidad. No duplicar textos visibles encima.
5. Las imágenes recortadas con margen del fondo original no deben prometerse como PNG con fondo perfectamente transparente. Si se necesitan sprites puros, conviene partir de los grupos 01 y 04 previamente separados, o generar las teclas con CSS.
6. Mantener el foco del teclado en el juego y asegurar controles móviles mediante botones HTML funcionales.
