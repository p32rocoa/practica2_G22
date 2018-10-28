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
