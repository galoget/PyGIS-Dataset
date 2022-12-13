# PyGIS-Dataset
Evaluación Curso Python GIS.

## Parte 1:
- Deberán utilizar el archivo GEOJSON proporcionado y OJO deben leer el GEOJSON del servidor web directamente (enlace arriba), NO lo deben descargar a su computador y NO usarlo como archivo local.
- Deberán convertir el GEOJSON a diccionario en Python.
- Procesar el diccionario para hacer un CSV.
- Si desean, pueden descargar valores como "type", "geometry" del GEOJSON al CSV, esto en caso de que les sea complicado darle formato al CSV, la parte más importante del dataset son las "properties", donde está toda la información geográfica y también descriptiva de cada institución educativa.
- Escribir la data en un archivo CSV (schools-list.csv).
- En todo el código, agregar excepciones según corresponda para evitar que el programa muera por cualquier tipo de error que pueda suceder en su ejecución.

## Parte 2:
- Continuando con todo lo avanzado en la Parte 1, deberán resolver ciertas inquietudes planteadas a continuación.
- Generar un archivo de salida de nombre reporte.txt respondiendo a las siguientes preguntas:
  + Cuántas escuelas están en fase Primaria ("Phase":"Primary")
  + Cuántas escuelas están en fase Secundaria ("Phase":"Secondary")
  + Cuántas escuelas están en fase 16 plus ("Phase":"16 plus")
  + Cuántos alumnos en lista en total existen ("Number of pupils on roll")
  + Cuántas escuelas tienen enfermería y cuántas no ("Nursery")
  + Cuántas escuelas fueron censadas en mayo 2022 ("Census date")
  + Cuál es el promedio de todas las latitudes del Dataset ("Latitude")
  + Cuál es el promedio de todas las longitudes del Dataset ("Longitude")

## Notas:
1. La prueba está diseñada para evaluar aspectos clave y no complicarles mucho la resolución, por lo que no debería tomarles más de 2 horas de realización (considerando alguien nuevo en el tema), para más experimentados el tiempo más rápido sería de unos 20-30 minutos.

2. Las preguntas deben ser respondidas de manera automática a través del código en Python, es decir los cálculos deben ser automatizados para funcionar en base a cualquier dataset proporcionado.

3. La evaluación incluye todo el contenido visto en el Curso. No se incluye nada nuevo o no cubierto en clases.

4. Para cualquier pregunta o inquietud, comunicarse por interno a través del Grupo o mensaje privado.

5. Detalles de la entrega de la Evaluación fueron publicados en el grupo. Leer a detalle las instrucciones.
