# Fixture para Clasificatorias de la CONMEBOL

Este repositorio contiene un proyecto que aborda la problemática del fixture de las eliminatorias sudamericanas de fútbol para el torneo mundial. Desde 1998 hasta 2014, la CONMEBOL utilizó un sistema de doble round robin espejado para el torneo clasificatorio, generando ciertas injusticias y quejas por parte de las federaciones miembro. En este proyecto, se propone analizar y encontrar soluciones que se ajusten a las restricciones requeridas.

## Introducción

En cada edición de la Copa del Mundo entre 1998 y 2014, la CONMEBOL utilizó un sistema de doble round robin espejado para las eliminatorias, dividido en 18 jornadas con un total de 90 partidos. Este formato generó críticas y quejas debido a su injusticia percibida. Por lo tanto, este proyecto tiene como objetivo definir un nuevo fixture para las eliminatorias sudamericanas utilizando programación lineal.

## Base de la formulación

El proyecto se basa en la formulación de variables y restricciones para modelar el problema. Se define un conjunto de equipos I y un conjunto de rondas K. Las variables binarias X~ijk~ representan si el equipo i juega como local contra el equipo j en la ronda k.

Se establecen restricciones como el doble round robin, la compacidad y el balance en las secuencias de local-visitante. La función objetivo busca minimizar el número total de descansos como visitante en las rondas dobles para todos los equipos.

## Código y Uso

El proyecto incluye el código necesario para resolver el problema de programación lineal y generar un nuevo fixture para las eliminatorias sudamericanas. Se proporciona documentación detallada sobre cómo ejecutar el código y cómo interpretar los resultados.

## Resultados

Los resultados obtenidos muestran un nuevo fixture que cumple con las restricciones establecidas y busca minimizar las injusticias percibidas en el formato anterior. Se discuten las implicaciones y posibles mejoras para futuras ediciones de las eliminatorias sudamericanas.

## Contribuciones

Se anima a la comunidad a contribuir con ideas, sugerencias y mejoras al proyecto. Se pueden abrir problemas para discutir posibles mejoras en el código o en el enfoque del problema, así como también enviar solicitudes de extracción con nuevas funcionalidades o correcciones de errores.

## Autores

Este proyecto fue desarrollado por [Nombre del Equipo/Desarrolladores] como parte de [Proyecto/Asignatura/Investigación], bajo la supervisión de [Supervisor/Profesor]. Se agradece a [Institución/Universidad] por el apoyo brindado.
