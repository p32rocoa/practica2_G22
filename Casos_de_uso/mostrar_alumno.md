### **Mostrar alumno**

**ID:** 001 <br>
**Breve descripción:** Muestra a un alumno inscrito en el programa.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ El alumno debe existir en el sistema.
+ El profesor debe conocer, al menos, uno de los datos identificativos del alumno (DNI, apellidos).

**Flujo principal:**

1. El caso de uso comienza cuando el sistema necesita mostrar un alumno.
2. El sistema recoge los datos que el profesor introduce para encontrar al alumno.

**Postcondiciones:**

+ Se encuentra alumno y se imprimen los datos en un archivo Markdown.

**Flujos alternativos:**

 2.a. Si el alumno no existe, se muestra un mensaje de error.<br>
 2.b. Si los apellidos buscados coinciden entre varios alumnos, se pedirá el DNI.
