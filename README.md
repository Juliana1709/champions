# CHAMPIONS

Este repositorio aloja la solucion de la actividad 1 relacionada con el diseño y operaciones CRUD 
en base de datos NOSQL.

**DESCRIPCION DEL EJERCICIO**

El presente ejercicio re crea la estructuracion de un campeonato de futbol 5 en el colegio YZX
el cual es estructurado en dos grupos **A** y **B** los cuales contendran una cantidad de equipos que deberan jugar
entre si.

**Reglas del juego**

1.Los equipos de cada grupo jugaran entre si

2.El equipo con más partidos ganados en el grupo sera candidato a discutir el 1er puesto

3.El equipo que pierda la disputa por el primer puesto queda como subcampeon

4.El segundo equipo con más puntaje seran cantidatos para discutir el 3er puesto

**Estructuracion de la informacion**

1. La informacion esta alojada en la base de datos champions
2. La distribucion de la informacion se da en 6 colecciones:
   - jugadores
   - equipos
   - entrenadores
   - arbitros
   - encuentro_deportivo
   - posiciones
   - resultados
3.dentro del archivo datos_champions.txt se encuentran los comandos de mongo db para la creacion de
la base de datos, el uso de esta, la creacion de cada una de las colecciones y el insert de cada uno de los documentos.

4.Dentro del archivo metamodelo_champions.png se encuentra la estructuracion dentro del metamodelo para mayor conocmiento de la logica.



