# Proyecto4
Proyecto 4 del curso de Modelos Probabilísticos de Señales y Sistemas
B61325 - Alexander Calderón Torres

## Comentario sobre la solución
Para la realización de la primera parte, sobre la modulación 16-QAM, se optó por realizar lo que se describe a continuación. En primer lugar, se modificó la función *modulador* dada, y a partir de ella se generaron dos nuevas funciones: *modulador_I* y *modulador_Q*. La tarea que realizan ambas funciones es la de generar dos señales, desfasadas en 90 grados, de manera tal que se logren transmitir los bits correctamente.

Sin embargo, a la hora de realizar esto se encontraron algunas dificultades, como la de realizar divisiones de los bits originales a transmitir para que cada función trabajara con los bits correspondientes, generando esto la necesidad de posteriormente recombinar las señales de manera adecuada para pasar posteriormente a la etapa de demodulación. Sin embargo, entre estos pasos se debieron cometer algunos errores de implementación, dado que el resultado final de la simulación no coincide con la imagen original.