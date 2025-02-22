# COMPARACIONES Y DECISIONES EN JAVA SCRIPT

## Explicación

### HTML

En la hoja de HTML viene impresa las indicaciones tal cuál en el repositorio usando solo los elementos:

- h1
- h3
- p
- ul > li

### let

1. Se dió la calificación de 5 alumnos (Juan, Sahara, Cesar, Roxana y Archivaldo) declarandolas con **let** bajo el nombre *calificacionNombreAlumno*.
2. Se declaro la variable con limites de 0 y 100 con **if**.
3. Se utilizaron operadores de comparación.
4. Se utilizaron operadores lógicos.

Los mensajes que se dierón según la calificación (una caja por cada alumno):
- if (calificacionNombreAlumno >=0 && calificacionArchivaldo<=100){
- if(calificacionNombreAlumno >= 90 && calificacionNombreAlumno <= 100){console.log("NombreAlumno tu calificación es de " + calificacionNombreAlumno + " puntos. Excelente. Sigue así.")}
- else if (calificacionNombreAlumno >= 75 && calificacionNombreAlumno <= 89){console.log("NombreAlumno tu calificación es de " + calificacionNombreAlumno + " puntos. Bien. Esfurzate un poquito más para ser excelente.")}
- else if (calificacionNombreAlumno >= 60 && calificacionNombreAlumno <= 74){console.log("NombreAlumno tu calificación es de " + calificacionNombreAlumno + " puntos. Suficiente. No te conformes, puedes dar más.")}
- else{console.log("Juan tu calificación es de " + calificacionNombreAlumno + " puntos. Insuficiente, no apruebas.")}
-}else{("Error. La nota debe estar entre 0 y 100, no se admite el valor " + calificacionNombreAlumno + ".")}