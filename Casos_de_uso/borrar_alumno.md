### **Borrar alumno**

**ID:** 004 <br>
**Breve descripción:** Borra a un alumno inscrito en el programa.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ El alumno debe existir en el sistema.
+ El profesor debe conocer uno de los datos identificativos del alumno (DNI, apellidos).

**Flujo principal:**

1. El caso de uso comienza cuando el sistema necesita borrar al alumno que el profesor especifique.
2. El sistema recoge los datos que el profesor introduce para encontrar al alumno y, posteriormente, borrarlo.

**Postcondiciones:**

+ Se encuentra al alumno y se borra del sistema.

**Flujos alternativos:**

2.a. Si el alumno no existe, se muestra un mensaje de error.<br>
2.b. Si los apellidos buscados coinciden entre varios alumnos, se pedirá el DNI.<br>
