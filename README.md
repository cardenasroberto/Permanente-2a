# Permanente-2a
<>Este programa es un sistema de almacenamiento de datos que pueden camibar de destino siendo este una 
almacén e inventario, el programa funciona de la siguiente manera

-En las primeras lineas envia un saludo para luego segui al menu
-----------------------------
MENÚ:
1. Ver objetos en Almacén
2. Dejar objeto en almacén
3. Retirar objeto del almacén
4. Ver inventario
5. Salir
-----------------------------
-luego se definie el menu imprimiendo strings que son opciones para luego usar condicionales
que sirven para llamar a las siguientes definiciones 
-Definimos el ver objetos en almacén:

def ver_objeto_almacen():
    print()
    print("En el almacén queda: ", objetos)
    print()
   
-Luego definimos el dejar objetos en almacén que sirve para que lo objetos de inventario se muevan a almacen
-Definimos el retirar objetos del almacén 
    if retiro == 1:
        inventario.append(objetos.pop(0))
  Al ejecutar esta linea lo que hace el programa es retirar el primer objeto de la lista
  almacén y luego la agrega mediante el inventario.append a el inventario
 -Por ultimo definimos el ver inventario para saber que objetos están en la lista
 
 Tienes en el inventario:  ['lápiz']
 
 -Para terminar de ejecutar el codigo ponemos 5 y se ejecutará la definicion de salir
 a partir del bucle while
