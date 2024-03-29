# Programación de las Clasificatorias Sudamericanas para el Mundial de la FIFA 2018 mediante programación entera.

## Introducción

En todas las Copas del Mundo desde 1998 hasta 2014, la CONMEBOL (Confederación Sudamericana de Fútbol) utilizó un sistema de doble round robin espejado para el torneo clasificatorio. El torneo está dividido
en 18 jornadas y bajo este formato, un equipo se enfrentaba a cada rival una vez en las primeras 9 jornadas en un orden definido, y luego nuevamente en las últimas 9 jornadas en el mismo orden pero con el local-visitante invertido. Cada una de las jornadas consta de 5 partidos en los que cada equipo participa exactamente una vez. Por ende, en total el torneo cuenta con 90 encuentros.

La decisión de hacer el fixture de esta manera llevó a muchas injusticias y quejas de las distintas federaciones que componen la CONMEBOL, por lo que en este proyecto vamos a estar analizando distintas variantes, tratando de obtener soluciones que se ajusten a todas las restricciones requeridas.

Nuestro objetivo con este trabajo es definir el fixture de las eliminatorias sudamericanas de fútbol para el mundial de futbol 2018. Para hacer esto vamos a hacer uso de programación lineal.

## Informe

En el informe, además de presentar todos los posibles fixtures, hemos explicado cómo están definidas las variables que utilizamos, junto con sus respectivas restricciones, para explorar diferentes configuraciones de 
fixtures, tales como el esquema francés, inglés, entre otros. Una vez obtenidas todas las configuraciones, procedimos a sortear los países asignando un número a cada uno, y completamos los fixtures en cada esquema, asegurándonos de no mostrar favoritismo hacia ningún país en particular.

Además, en consideración a las variantes previamente realizadas y atendiendo a las preocupaciones expresadas por las federaciones de los países, quienes han señalado que jugar contra Argentina y Brasil en fechas consecutivas desmotiva a los jugadores debido a la casi inevitable derrota, hemos incorporado una restricción adicional para evitar esta situación. Por consiguiente, se han generado nuevos fixtures teniendo en cuenta esta restricción.

## Código y Uso

El proyecto contiene el código necesario para resolver el problema de programación lineal y generar un nuevo fixture para las eliminatorias sudamericanas en formato ZPL, con cada variación formulada. Para obtener la solución, simplemente se requiere ejecutar el archivo deseado en SCIP u otro framework de programación lineal entera.

