### **Ver alumnos**
**ID:** 001 <br>
**Breve descripción:** Muestra a un alumno inscrito en el programa.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**
+ El alumno debe existir en el sistema
+ El profesor debe conocer uno de los datos identificativos del alumno, (DNI, apellidos)

**Flujo principal:**
+ El caso comienza cuando el sistema necesita mostrar un alumno
+ El sistema recoge los datos que el profesor introduce para encontrar al alumno

**Postcondiciones:**
+ Se encuentra alumno y se imprimen los datos en un archivo markdown.

**Flujos alternativos:**
+ El alumno no se encuentra o no existe y se muestra un mensaje de error
