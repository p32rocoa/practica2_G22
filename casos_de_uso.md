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

---

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

---

### **Listar alumnos**

**ID:** 003 <br>
**Breve descripción:** Muestra toda la lista de alumnos.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ Debe existir al menos un alumno en el sistema.

**Flujo principal:**

1. El caso comienza cuando el sistema necesita mostrar la lista de alumnos.
2. El sistema pide al profesor en qué orden los quiere mostrar.

**Postcondiciones:**

+ Se ordenan los alumnos y se muestran en orden.

**Flujos alternativos:**

2.a. No existe ningún alumno en la aplicación y se muestra un mensaje de error.

---

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

---

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

---

### **Mostrar grupo**

**ID:** 006 <br>
**Breve descripción:** Muestra todos los datos de un grupo.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ Debe existir al menos un grupo en la base de datos.
+ Debe existir al menos un alumno dentro del grupo a mostrar.

**Flujo principal:**

1. El caso de uso comienza cuando el sistema necesita mostrar los datos de un grupo.
2. El sistema muestra los grupos existentes y los muestra por pantalla.
3. El profesor elige qué grupo mostrar.

**Postcondiciones:**

+ Se muestran los alumnos del grupo y quién es el líder.

**Flujos alternativos:**

2.a Si el sistema no contiene ningún grupo, se muestra un mensaje de error.

---

### **Guardar cambios**

**ID:** 007 <br>
**Breve descripción:** Guarda los cambios realizados en el programa.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ Debe existir algún cambio en la base de datos.

**Flujo principal:**

1. El profesor activa el botón de guardado.

**Postcondiciones:**

+ Los cambios se guardan en la base de datos.

**Flujos alternativos:**

1.a. No hay cambios en la base de datos y el programa no hace nada.

---

### **Reiniciar alumnos**

**ID:** 008 <br>
**Breve descripción:** Elimina a todos los alumnos de la base de datos del programa.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ Debe existir algún alumno en la base de datos.

**Flujo principal:**

1. El profesor activa el botón de borrado.

**Postcondiciones:**

+ Los alumnos son borrados y la base de datos se guarda vacía.

**Flujos alternativos:**

1.a. No hay alumnos en la base de datos y se muestra un mensaje de error.

---
