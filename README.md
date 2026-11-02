# Hoja de Respuestas PAES

Aplicación web (un solo archivo, `index.html`) para responder ensayos PAES en una hoja de respuestas digital, cargar la clave y obtener la corrección por eje temático con un plan de mejora.

## Uso
Abre `index.html` en el navegador (o publícalo con GitHub Pages).

1. **Hoja**: elige la prueba (Competencia Lectora, M1, M2, Historia, Ciencias o personalizada) y marca tus respuestas. `?` marca dudas. Incluye cronómetro con el tiempo oficial.
2. **Clave**: sube un `.csv`/`.txt` o pega la clave. Formato por línea: `número;clave;eje;contenido` (ej.: `1;B;Números;Porcentaje`). También acepta solo la secuencia de letras (`BDACB…`) o pares `1-B 2-D`; los ejes se pueden asignar por rango.
3. **Enviar respuestas**: resultados, desempeño por eje, contenidos a repasar, consejos y estrategia.
4. **Historial**: evolución por prueba y eje.

Los datos se guardan en el navegador (localStorage) del dispositivo.
