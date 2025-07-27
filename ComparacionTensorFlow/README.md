## Comparación entre CNN yTransformers
Las CNN son convenientes para datos con mediana a pequeña resolucion son buenas mientras que los Transformers han demostrado gran eficacia en base de datos grandes.<br>

Las ventajas de un CNN: Mejor generalización con pocos datos. Menor necesidad de cómputo y memoria. <br>
Trabaja con operaciones locales(convolucionales), lo  que significa que requieren menos recursos y menos operaciones para procesar una imagen.
Ventajas del Transformer (ViT):Captura relaciones globales en la imagen. Modelo más flexible y paralelo. Da resultados superiores en tareas grandes y diversas, si se dispone de mucho dato y potencia computacional.<br>


## Resultados con la base de datos BdMnist <br>
# CNN <br>
Test loss: 0.025131383910775185<br>
Test accuracy: 99.10%
# Transformador
Test accuracy:98.4%
## Resultados con la base de datos Cifar <br>
# CNN <br>
Test loss: 0.024599900469183922<br>
Test accuracy: 0.9922000169754028<br>
# Transformador
Test accuracy: 34.72%<br>
Test top 5 accuracy: 65.04%<br>
## Conclusiones
MNIST: Ambos modelos funcionan excelente, pero las CNN mantienen una ligera ventaja.

CIFAR: Las CNN dominan claramente. Si el Transformador no fue adaptado especialmente para visión por computador (ViT, DeiT, etc.), es normal que su rendimiento sea mucho menor.

Asimismo la CNN es eficiente para pocos datos, menor necesidad de cómputo y memoria. Mientras que el transformador entiende el contexto de la imagen,grado de paralelización durante el entrenamiento y no depende de la estructura espacial fija de la imagen.
