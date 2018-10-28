### **Insertar alumnos**

**ID:** 005 <br>
**Breve descripción:** Inserta a un alumno nuevo en el programa.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ El alumno no debe existir en el sistema.
+ El profesor debe conocer los datos obligatorios para insertar un alumno nuevo.

**Flujo principal:**

1. El caso comienza cuando el sistema necesita insertar un nuevo alumno.
2. El sistema recoge los datos que el profesor introduce en una nueva entrada.

**Postcondiciones:**

+ Se inserta el nuevo alumno en la base de datos del programa.

**Flujos alternativos:**

1.a Si el alumno ya se encuentra registrado, se muestra un mensaje de error.
