## Comparación entre CNN yTransformers
Las CNN son convenientes para datos con mediana a pequeña resolucion son buenas mientras que los Transformers han demostrado gran eficacia en base de datos grandes.<br>

Las ventajas de un CNN: Mejor generalización con pocos datos. Menor necesidad de cómputo y memoria. <br>
Trabaja con operaciones locales(convolucionales), lo  que significa que requieren menos recursos y menos operaciones para procesar una imagen.
Ventajas del Transformer (ViT):Captura relaciones globales en la imagen. Modelo más flexible y paralelo. Da resultados superiores en tareas grandes y diversas, si se dispone de mucho dato y potencia computacional.<br>


## Resultados con la base de datos BdMnist <br>
# CNN <br>
Test loss: 0.025131383910775185<br>
Test accuracy: 99.10%
# Transofrmador
Test accuracy:98.4%


En conclución el CNN es eficiente para pocos datos, menor necesidad de cómputo y memoria. Mientras que el transformador entiende el contexto de la imagen,grado de paralelización durante el entrenamiento y no depende de la estructura espacial fija de la imagen.
