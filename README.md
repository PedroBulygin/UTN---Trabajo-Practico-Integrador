Gestión de Datos de Países en Python

Descripción del Programa

Este programa es un sistema de gestión de datos de países implementado en Python. Permite al usuario interactuar con una lista de países almacenada en un archivo CSV (`paises.csv`), realizando diversas operaciones como agregar nuevos países, actualizar datos existentes, buscar, filtrar y ordenar la información.

El programa carga los datos al inicio y los guarda automáticamente en el archivo CSV cada vez que se realizan modificaciones (agregar o actualizar). Si el archivo CSV no existe, el programa lo crea automáticamente con un conjunto de datos de ejemplo para comenzar a trabajar.

Funcionalidades principales:

* CRUD Básico: Agregar nuevos países (Create) y Actualizar datos existentes (Update).
* Consultas: Buscar países por nombre, filtrar por continente, rango de población o rango de superficie.
* Análisis: Ordenar la lista por nombre, población o superficie, y mostrar estadísticas clave (país más/menos poblado, promedios, conteo por continente).

---

Instrucciones de Uso

Interacción con el Menú

El programa mostrará el menú principal. Deberás ingresar el número de la opción deseada y presionar Enter.

GESTIÓN DE DATOS DE PAÍSES
Agregar nuevo país

Actualizar datos de un país

Buscar país por nombre

Filtrar por continente

Filtrar por rango de población

Filtrar por rango de superficie

Ordenar países

Mostrar estadísticas

Salir


Notas importantes sobre las entradas:

* Campos de texto: Las búsquedas por nombre y continente no distinguen entre mayúsculas y minúsculas.
* Campos numéricos: La población y la superficie deben ingresarse como números enteros válidos. El programa realiza validaciones para asegurar que estos campos no estén vacíos y sean numéricos.
* Opción 7 (Ordenar): Se requiere ingresar el campo de ordenamiento (`nombre`, `poblacion` o `superficie`) y si el orden es descendente (`s` para Sí o `n` para No).

---

Ejemplos de Entradas y Salidas

Ejemplo 1: Agregar un Nuevo País (Opción 1)

Entradas del Usuario:

Seleccione una opción: 1 AGREGAR NUEVO PAÍS

Nombre: Chile Población: 19678363 Superficie: 756102 Continente: América


Salida del Programa:

Chile ha sido agregado correctamente.


Ejemplo 2: Filtrar por Continente (Opción 4)

Entradas del Usuario:

Seleccione una opción: 4 Ingrese el continente: america


Salida del Programa (basada en los datos de ejemplo y el país agregado):

Nombre Población Superficie Continente
Argentina 45376763 2780400 América Brasil 213993437 8515767 América Chile 19678363 756102 América


Ejemplo 3: Mostrar Estadísticas (Opción 8)

Entradas del Usuario:

Seleccione una opción: 8


Salida del Programa (basada en los datos de ejemplo y el país agregado):

ESTADÍSTICAS: País con mayor población: Brasil - 213993437 País con menor población: Chile - 19678363 Promedio de población: 75549025 Promedio de superficie: 3107573 Cantidad de países por continente: América: 3 Asia: 1 Europa: 1

Participacion de los Alumnos

Pedro Bulygin
Federico Casares