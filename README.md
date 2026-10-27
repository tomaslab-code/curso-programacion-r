# Pronosticar el éxito en la NFL

Proyecto del curso "Programar con criterio en la era de la IA".
Pregunta: ¿qué características de un jugador, conocidas en el draft,
permiten pronosticar su éxito profesional?

Autor/a: Tomás Zerón Solís

## Datos
- Archivo: nfl_data.csv del repositorio phcs971/nfl-draft-dataset
  (licencia MIT), leído desde una URL fijada a la versión 54730ea.
- Contenido: filas=14,163 y columnas=59
- Base de análisis: Todos los jugadores elegidos en el draft entre 2000 y 2014

## Variables principales
- Éxito observado:  El valor de carrera (career_av) o haber ido al Pro Bowl, lo que paso en la carrera del jugador
- Predictores: Lo que sabemos del jugador cuando hacemos el pronóstico. Estatura, peso, tiempo en 40 yardas, posición. En el Combine o el día del draft

## Decisiones de limpieza
1. eliminar los registros incompletos
2. evitar sesgos y garantizar resultados confiables

## Carpetas
- sesion-1/ a sesion-5/: trabajos de cada sesión
