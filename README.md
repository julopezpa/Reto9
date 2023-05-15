# Reto9
1) Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.

  def promedio():
    n=int(input("ingrese el numero de valores que quiere en el vector"))
    lista=[]
    suma=0
    for i in range(n):
        numero=float(input("ingrese el elemento"))
        lista.append(numero)
    suma=sum(lista)Reto10(punto1).py
    print(lista)
    return (suma/n)

if __name__ == "__main__":
    promedio_lista=promedio()
    print("el promedio de los valores dentro de la lista es "+str(promedio_lista))
    
    file:///C:/Users/POWER/Documents/Reto10(punto1).py
