## Ingeniería del Software
## 2º Curso. Grado en Ingeniería Informática
## Escuela Politécnica Superior (Universidad de córdoba)
## Práctica 2. Análisis de requisitos
### Grupo 22

---
---

### **Extracción de requisitos**
<br>
#### **Partes interesadas:**
- Profesores

#### **Datos a almacenar de los alumnos:**

  - DNI
  - E-mail corporativo
  - Nombre
  - Apellidos
  - Fecha de nacimiento
  - Domicilio
  - Teléfono
  - Curso más alto matriculado
  - Grupo al que pertenece
  - Rol dentro del grupo (Representante de este o no)

#### **Requisitos funcionales:**

  + **RF-1:** La aplicación permitirá almacenar alumnos.


  + **RF-2:** Se podrán insertar nuevos alumnos.
    - **RF-2.1:** No se permitirá la inserción de un alumno con un DNI o e-mail ya existente.


  + **RF-3:** Será posible buscar a un alumno mediante su DNI o apellidos.
    - **RF-3.1:** Si existe más de un alumno con esos apellidos, se pedirá el DNI.


  + **RF-4:** Se permitirá la modificación de los datos de los alumnos, especificando su respectivo DNI o apellidos previamente.
    - **RF-4.1:** Si existe más de un alumno con esos apellidos, se pedirá el DNI.


  + **RF-5:** será posible el borrado de alumnos mediante su DNI o apellidos.
    - **RF-5.1:** Si existe más de un alumno con esos apellidos, se pedirá el DNI.


  + **RF-6:** Se podrá listar a todos los alumnos.
    - **RF-6.1:** Será posible listarlos ordenados alfabéticamente por nombres y apellidos. (Orden ascendente o descendente)
    - **RF-6.2:** Será posible listarlos ordenados numéricamente por su DNI. (Orden ascendente o descendente)
    - **RF-6.3:** Podrán ser listados ordenados por el curso más alto en el que estén matriculados. (Orden ascendente o descendente)


  + **RF-7:** Se podrá mostrar a un único alumno mediante sus apellidos o DNI.
    - **RF-7.1:** Si existe más de un alumno con esos apellidos, se pedirá el DNI.


  + **RF-8:** Será posible la búsqueda de un conjunto de alumnos mediante su grupo.
    - **RF-8.1:** Podrá haber una opción para buscar solo al líder de dicho grupo.


  + **RF-9:** Se podrá mostrar a todos los alumnos pertenecientes a un grupo.
    - **RF-9.1:** Podrá haber una opción para mostrar solo al líder del grupo.


  + **RF-10:** Habrá una opción que permita borrar a todos los alumnos almacenados.
