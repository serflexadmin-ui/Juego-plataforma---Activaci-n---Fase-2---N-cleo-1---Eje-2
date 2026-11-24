# Paquete 10 · Puntos de control y efectos de logro

Contiene PNG individuales extraídos de la lámina original, un inventario JSON y una vista previa.

## Implementación
- `01_checkpoints`: tres estados del banderín (inactivo, activado, completado).
- `02_sellos_logro`: cinco insignias reutilizables.
- `03_compuertas`: versión cerrada y abierta; la colisión debe controlarse por código.
- `04_cofres`: cerrado y abierto; enlazar su estado al progreso.
- `05_engranajes_estado`: tres versiones para estados del juego.
- `06_efectos`: superposiciones transparentes para animaciones breves sin crear variantes adicionales.

### Advertencias de calidad
Los halos brillantes proceden de una imagen generada y conservan zonas semitransparentes. Puede haber pequeños residuos de color en algunos bordes, especialmente en los efectos. En Canva Code, no uses las imágenes para determinar colisiones ni posiciones. Los PNG son recursos visuales; los cambios de estado se controlan en JavaScript. No repitas las etiquetas en HTML salvo que sean necesarias.
