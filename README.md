# E1_Repositorio
Evidencia de Programación avanzada 
# NOTECE QUE EL CODIGO ESTA ELABORADO EN PHYTON, PARA REMARCAR INSTRUCCIONES AQUI, DE SE HA USAD0 ESTE CARACTER (#) PARA HACER REFERENCIA A COMENTARIOS EN EL CODIGO.

# Para esta evidencia se presentaran distintos codigos que se vieron durante la fase, como por ejemplo, codigos de funciones de phyton, bucles, RegEx.

# 1.- En un rango de 1-101 numeros, imprimir los numeros pares.
for i in range(1,101):
    if((i%2)==0):
        print(i)
        
        
# 2.- Imprimase la frase mientras esta sea igual.
while True:
    n=input("please enter hello:")
    if n == "hello":
        break
print("fin")


# 3.1 3.- Mostrar un menú con tres opciones: 1- comenzar programa, 2- imprimir listado, 3-finalizar programa.
# A continuación, el usuario debe poder seleccionar una opción (1, 2 ó 3). Si elige una opción incorrecta, informarle del error.
# El menú se debe volver a mostrar luego de ejecutada cada opción, permitiendo volver a elegir.
# Si elige las opciones 1 ó 2 se imprimirá un texto. Si elige la opción 3, se interrumpirá la impresión del menú y el programa finalizará.
suma=0
opcion=0
print("A continuacion se presenatn 3 opciones, las cuales para escoger debera introducir su numero")
print("1- comenzar programa, 2- imprimir listado, 3-finalizar programa. ")
while True:
    opcion=int(input("Introduzca el numero de opcion: "))
    suma+=opcion
    if opcion == 1
    
    
# 4.- Para el siguiente ejercicio utilizar Phyton RegEx (*)
import re
txt = "blanca cantaba, bailaba y disfrutaba del momento"
x = re.findall("aba*", txt)
print(x)
if x:
  print("Encontrado")
else:
  print("No encontrado")
    
    
# 4.1  Para el siguiente ejercicio utilizar Phyton RegEx ([A-Z]).
import re
txt = "En primavera, las florecen florecen"
x = re.findall("[A-Z]", txt)
print(x)
if x:
  print("Encontrado")
else:
  print("No encontrado")
  
  
# 4.2 Validacion de correo.
import re
correo=(input("Correo: "))
if re.match('^[(a-z0-9\_\-\.)]+@[(a-z0-9\_\-\.)]+\.[(a-z)]{2,15}$',correo.lower()):
 print("Correo correcto")
else:
 print("Correo incorrecto")
 

# 5.- Realiza una función llamada relacion(a, b) que a partir de dos números cumpla lo siguiente:
# • Si el primer número es mayor que el segundo, debe devolver 1.
# • Si el primer número es menor que el segundo, debe devolver -1.
# • Si ambos números son iguales, debe devolver un 0.
# Comprueba la relación entre los números: '5 y 10', '10 y 5' y '5 y 5'.

def relacion(a, b):
 if a > b:
     return 1
 elif a < b:
     return -1
 else:
     return 0
print( relacion(5, 10) )
print( relacion(10, 5) )
print( relacion(5, 5) )


# 5.1 -Realiza una función separar(lista) que tome una lista de números enteros y devuelva dos listas
# ordenadas. La primera con los números pares y la segunda con los números impares.
# Para ordenar una lista automáticamente puedes utilizar el método. sort()

numeros = [-12, 84, 13, 20, -33, 101, 9]
def separar(lista):
 lista.sort()
 pares = []
 impares = []
 for n in lista:
    if n%2 == 0:
        pares.append(n)
    else:
     impares.append(n)
     return pares, impares
pares, impares = separar(numeros)
print(pares)
print(impares)



ANA CRISTINA CAVAZOS OYERVIDEZ
