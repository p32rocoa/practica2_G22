### **Modificar alumno**

**ID:** 002 <br>
**Breve descripción:** Da la posibilidad de modificar los datos de un alumno.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ El alumno debe existir en el sistema.
+ El profesor debe conocer uno de los datos identificativos del alumno (DNI, apellidos).

**Flujo principal:**

1. El caso de uso comienza cuando el sistema necesita modificar los datos de un alumno.
2. El sistema recoge los datos que el profesor introduce para encontrar al alumno.
3. El sistema muestra los datos que pueden ser modificados y los dispone al cambio.

**Postcondiciones:**

+ El sistema guarda los nuevos datos del alumno.

**Flujos alternativos:**

2.a. Si el alumno no existe, se muestra un mensaje de error.<br>
2.b. Si los apellidos buscados coinciden entre varios alumnos, se pedirá el DNI.<br>
3.a Cuando la modificación intenta realizar algo no permitido, se muestra un mensaje de error.
