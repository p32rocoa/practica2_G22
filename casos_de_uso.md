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

---
### **Modificar alumnos**
**ID:** 002 <br>
**Breve descripción:** Da la posibilidad de modificar los datos de un alumno

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**
+ El alumno debe existir en el sistema
+ El profesor debe conocer uno de los datos identificativos del alumno, (DNI, apellidos)

**Flujo principal:**
+ El caso comienza cuando el sistema necesita mostrar un alumno
+ El sistema recoge los datos que el profesor introduce para encontrar al alumno
+ El sistema muestra los datos editables y los dispone al cambio

**Postcondiciones:**
+ EL sistema guarda los nuevos datos del alumno

**Flujos alternativos:**
+ El alumno no se encuentra o no existe y se muestra un mensaje de error
+ Se repiten datos irrepetibles y se muestra un mensaje de error

---
### **Listar alumnos**
**ID:** 003 <br>
**Breve descripción:** Muestra toda la lista de alumnos

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**
+ Debe existir al menos un alumno en el sistema

**Flujo principal:**
+ El caso comienza cuando el sistema necesita mostrar la lista de alumnos
+ El sistema pide al proesor en qué orden los quiere mostrar

**Postcondiciones:**
+ Se ordenan los alumnos y se muestran en orden

**Flujos alternativos:**
+ No existe ningún alumno en la aplicación y se muestra un mensaje de error

---
### **Borrar alumnos**
**ID:** 004 <br>
**Breve descripción:** Borra un alumno insciro en el programa

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**
+ El alumno debe existir en el sistema
+ El profesor debe conocer uno de los datos identificativos del alumno, (DNI, apellidos)

**Flujo principal:**
+ El caso comienza cuando el sistema necesita borrar el alumno que el profesor especifique
+ El sistema recoge los datos que el profesor introduce para encontrar al alumno y posteriormente borrarlo

**Postcondiciones:**
+ Se encuentra alumno y se borra del sistema

**Flujos alternativos:**
+ El alumno no se encuentra o no existe y se muestra un mensaje de error
+ Al especificar los apellidos del alumno, hay más de uno con los mismos y se da a elegir por DNI.

---
### **Insertar alumnos**
**ID:** 005 <br>
**Breve descripción:** Inserta a un alumno nuevo en el programa
**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**
+ El alumno no debe existir en el sistema
+ El profesor debe conocer los datos obligatorios para insertar un alumno nuevo

**Flujo principal:**
+ El caso comienza cuando el sistema necesita insertar un nuevo alumno
+ El sistema recoge los datos que el profesor introduce en una nueva entrada.

**Postcondiciones:**
+ Se inserta el nuevo alumno en la base de datos del programa

**Flujos alternativos:**
+ El alumno ya se encuentra registrado se muestra un mensaje de error

---
### **Mostrar grupo**
**ID:** 006 <br>
**Breve descripción:** Muestra todos los datos de un grupo
**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**
+ Debe existir al menos un grupo en la base de datos
+ Debe existir al menos un alumno dentro del grupo a mostrar

**Flujo principal:**
+ El caso comienza cuando el sistema necesita mostrar los datos de un grupo
+ El sistema muestra los grupos existentes y los muestra por pantalla
+ El profesor elige qué grupo mostrar

**Postcondiciones:**
+ Se muestran los alumnos del grupo y quién es el lider

**Flujos alternativos:**
+ El sistema no contiene ningún grupo se muestra un mensaje de error

---
### **Guardar cambios**
**ID:** 007 <br>
**Breve descripción:** Guarda los cambios realizados en el programa
**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**
+ Debe existir algún cambio en la base de datos

**Flujo principal:**
+ El profesor activa el botón de guardado

**Postcondiciones:**
+ Los cambios se guardan el la base de datos

**Flujos alternativos:**
+ No hay cambios en la base de datos y el programa no hace nada

---
