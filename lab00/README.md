## Análisis de código

***Función main***

### ¿QUÉ? 
Determina, dado un valor y un los elementos de un arreglo ingresados por consola, 
si el valor es **mayor/igual** o **menor/igual** a todos los elementos del arreglo y 
**si está** y **en qué posición** de dicho arreglo, en una estructura con los 4 requerimientos

### ¿CÓMO?
1. Solicitar el tamaño y los elementos del arreglo
2. Solicitar el valor 
3. Comparar ese valor con el primer elemento del arreglo
4. Actualizar los valores de la estructura
5. Volver al punto 3 y así hasta completar el arreglo
6. Imprimir por pantalla la estructura


### IMPLEMENTACIÓN (pseudocódigo)
**Main:** Pasos 1 y 2 y llamado a la función **check bound** donde se implementan 
los pasos 3,4 y 5. Main finaliza con paso 6

1. 
print "enter the size for the array"
fscanf (stdin, "&d", length)
int a[ARRAY_SIZE] ???? //Definir el arreglo de tamaño length

print "enter four elements for the array, in order"
for i=1 to 4 do
    fscanf (stdin, "%d", &arr[i])
od

2.
print "enter the value to compare"
    fscanf (stdin, "%d", value)

**check_bound**
3. cualquier cosa y dejate de hinchar la pija y ahora guarda 

