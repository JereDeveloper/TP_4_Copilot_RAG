# Mecanismos de control

Los valores son metas o propuestas de medición. Todavía no hay resultados medidos.

| Indicador | Meta propuesta | Cómo medirlo | Frecuencia y responsable |
|---|---|---|---|
| Latencia p95 | Menor a 1,5 segundos | Tiempo desde que se recibe la consulta hasta que aparece la sugerencia | Diaria durante el piloto / IT |
| Respuestas fundamentadas | Igual o mayor a 98% | Auditoría de respuestas correctas respaldadas por una fuente vigente | Semanal / Calidad y Conocimiento |
| Consultas simultáneas | Prueba de hasta 500 consultas | Prueba de carga y registro de latencia y errores | En cada versión / QA |
| Reducción del TMO | Al menos 25% a los tres meses | Comparar el TMO observado con una línea base comparable | Mensual / Operaciones |
| Vigencia de las fuentes | 100% como objetivo propuesto | Revisar que las fuentes recuperadas estén vigentes | Semanal / Conocimiento |
| Disponibilidad | 99,5% mensual como propuesta inicial | Minutos disponibles sobre minutos planificados | Mensual / IT |

## Acciones ante desvíos

- Si hay problemas de latencia o disponibilidad, activar el procedimiento manual.
- Si se detecta una fuente obsoleta o incorrecta, retirarla y volver a auditar antes de liberar el contenido.
- Registrar las mediciones antes de afirmar que una meta se alcanzó.
