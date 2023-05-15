# Reto10
# 1)Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.
     def promedio():
        n=int(input("ingrese el numero de valores que quiere en el vector"))#Pide el tamaño que va a tener el vector
        lista=[]
        suma=0
        for i in range(n):
            numero=float(input("ingrese el elemento"))#Ingresa todos los valores que van a estar dentro del vector
            lista.append(numero)
        suma=sum(lista)#Suma de todos los caracteres del vector
        print(lista)
        return (suma/n)#El promedio de los valores dentro del vector

    if __name__ == "__main__":
        promedio_lista=promedio()#Se llama a la funcion que calcula el promedio
        print("el promedio de los valores dentro de la lista es "+str(promedio_lista))
        
# 2)Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.
     def producto_punto(lista1, lista2):
         if len(lista1)!=len(lista2): #Se revisa que las listas tengan el mismo tamaño
             return 0
         producto_punto = 0#Se inicializa el valor del producto punto en 0
         for i in range(len(lista1)):#Se itera sobre las dos listas al mismo tiempo
            producto_punto+=lista1[i]*lista2[i]#Se calcula el producto de los elementos de las dos listas y se suman
         return producto_punto


     if __name__ == "__main__":
         lista1 = [] # Se crea una lista vacia
         lista2 = [] # Se crea una lista vacia
         n = int(input("Ingrese el tamaño de la listas : "))#Pide el tamaño que va a tener el vector
         for i in range(n):#Ingresa todos los valores que van a estar dentro del vector1
             i = float(input("Valores de la lista 1 :")) 
             lista1.append(i)#Se agrega cada valor a la lista 1
         for j in range(n):#Ingresa todos los valores que van a estar dentro del vector2
             j = float(input("Valores de la lista 2 : "))
             lista2.append(j)#Se agrega cada valor a la lista 2
         produccto_punto_listas = producto_punto(lista1, lista2)#Se llama a la función producto punto
         print(lista1)
         print(lista2)
         print("El producto punto de los vectores 1 y 2 es " + str(produccto_punto_listas))#Se imprime el pruducto punto entre los dos vectores
# 3)Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo.
         n=int(input("ingrese el numero de valores que quiere en el vector"))#Pide el tamaño que va a tener el vector
         lista=[]
         for i in range(n):
             numero=float(input("ingrese el elemento"))#Ingresa todos los valores que van a estar dentro del vector
             lista.append(numero)
         print(lista)
         cero=lista.count(0)#Se analisa la cantidad de 0 que existen dentro del vector
         for i in range(n):#Se recorre toda la lista sacando los 0 de la izquierda y poniendolos en el lado derecho o final del vector
             lista.remove(0)
             lista.append(0)
         print("en el vector hay "+str(cero)+" ceros")
         print(lista)
# 4)Revisar que son los algoritmos de sorting, entender bubble-sort (enlace a implementación).
 Revisado :D
# Meme random
![image](https://github.com/julopezpa/Reto9/assets/124606636/b57336b4-1cef-4e46-b0f7-0ec4dbd2ddae)
