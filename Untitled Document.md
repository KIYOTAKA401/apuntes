#EJERCICIO 1
""" 
while True:
 print("\nMi Calculadora")
 print("1. Suma")
 print("2. Resta")
 print("3. Multiplicación")
 print("4. División")
 print("5. Salir")
 opcion = input("Selecciona una opción: ")
 if opcion == '5':
    print("¡Hasta luego!")
    break
 elif opcion<'1' or opcion > '5':
    print("opcion no valida")
 else:
   num1 = float(input("Ingresa el primer número: "))
   num2 = float(input("Ingresa el segundo número: "))
   
   if opcion == '1':
      print("Resultado:", num1 + num2)
   elif opcion == '2':
      print("Resultado:", num1 - num2)
   elif opcion == '3':
      print("Resultado:", num1 * num2)
   elif opcion == '4':
      if num2 != 0:
         print("Resultado: ", num1 / num2)
      else:
         print("No se puede dividir entre cero")
   else:
      print("¡Gracias por usar Mi Calculadora!")

 """
#Ejercicio 2

""" class MiCalculadora:
 def __init__(self):
    pass
 def suma(self, a, b):
    return a + b
 def resta(self, a, b):
    return a - b
 def multiplicacion(self, a, b):
    return a * b
 def division(self, a, b):
    if b != 0:
        return a / b
    else:
        return "No se puede dividir entre cero" 
calculadora = MiCalculadora()
while True:
 print("\nMi Calculadora")
 print("1. Suma")
 print("2. Resta")
 print("3. Multiplicación")
 print("4. División")
 print("5. Salir")
 opcion = input("Selecciona una opción: ")
 if opcion == '5':
    print("¡Gracias por usar Mi Calculadora!")
    break
 elif opcion < '1' or opcion > '5':
        print("Opción no válida")
 else:
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
 if opcion == '1':
    print("Resultado:", calculadora.suma(num1, num2))
 elif opcion == '2':
    print("Resultado:", calculadora.resta(num1, num2))
 elif opcion == '3':
    print("Resultado:", calculadora.multiplicacion(num1, num2))
 elif opcion == '4':
    if num2 != 0:
        print("Resultado:", calculadora.division(num1, num2))
    else:
        print("No se puede dividir entre cero")
 """

 #Ejercicio 3
""" 
def suma(a, b):
 return a + b
def resta(a, b):
 return a - b
def multiplicacion(a, b):
 return a * b
def division(a, b):
 return a / b

def mi_calculadora(opcion, num1, num2):
 if opcion == '1':
    return suma(num1, num2)
 elif opcion == '2':
    return resta(num1, num2)
 elif opcion == '3':
    return multiplicacion(num1, num2)
 elif opcion == '4' and num2 != 0:
    return division(num1, num2)
 else:
    return "Opción no válida"
while True:
 print("\nMi Calculadora")
 print("1. Suma")
 print("2. Resta")
 print("3. Multiplicación")
 print("4. División")
 print("5. Salir")
 opcion = input("Selecciona una opción: ")
 if opcion == '5':
    print("¡Gracias por usar Mi Calculadora!")
    break
 elif opcion < '1' or opcion > '5':
    print("Opción no válida")
 else:
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
    resultado = mi_calculadora(opcion, num1, num2)
 print("Resultado:", resultado) """


#Ejercicio 4
""" 
def suma(a, b):
 return a + b
def resta(a, b):
 return a - b
def multiplicacion(a, b):
 return a * b
def division(a, b):
 return a / b if b != 0 else "No se puede dividir entre cero"
def mi_calculadora(opcion, num1, num2):
 return (
 suma(num1, num2) if opcion == '1'
 else resta(num1, num2) if opcion == '2'
 else multiplicacion(num1, num2) if opcion == '3'
 else division(num1, num2) if opcion == '4' and num2 != 0
 else "Opción no válida"
 )
while True:
 print("\nMi Calculadora")
 print("1. Suma")
 print("2. Resta")
 print("3. Multiplicación")
 print("4. División")
 print("5. Salir")
 opcion = input("Selecciona una opción: ")
 if opcion == '5':
    print("¡Gracias por usar Mi Calculadora!")
    break
 elif opcion < '1' or opcion > '5':
    print("Opción no válida")
 else:
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
    resultado = mi_calculadora(opcion, num1, num2)
    print("Resultado:", resultado)

 """

#Ejercicio 5
""" 
def suma(a, b):
 return a + b
def resta(a, b):
 return a - b
def multiplicacion(a, b):
 return a * b
def division(a, b):
 return a / b if b != 0 else "No se puede dividir entre cero"
def mi_calculadora(opcion, num1, num2):
 return (
 suma(num1, num2) if opcion == '1'
 else resta(num1, num2) if opcion == '2'
 else multiplicacion(num1, num2) if opcion == '3'
 else division(num1, num2) if opcion == '4' and num2 != 0
 else "Opción no válida"
 )
def mostrar_menu():
 print("\nMi Calculadora")
 print("1. Suma")
 print("2. Resta")
 print("3. Multiplicación")
 print("4. División")
 print("5. Salir")
while True:
 mostrar_menu()
 opcion = input("Selecciona una opción: ")
 if opcion == '5':
    print("¡Gracias por usar Mi Calculadora!")
    break
 elif opcion < '1' or opcion > '5':
    print("Opción no válida")
 else:
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
    resultado = mi_calculadora(opcion, num1, num2)
    print("Resultado:", resultado)
 """

#Ejercicio 6
""" 
def suma(a, b):
 return a + b
def resta(a, b):
 return a - b
def multiplicacion(a, b):
 return a * b
def division(a, b):
 return a / b if b != 0 else "No se puede dividir entre cero"
def operar(func, a, b):
 return func(a, b)
def mostrar_menu():
 print("\nMi Calculadora")
 print("1. Suma")
 print("2. Resta")
 print("3. Multiplicación")
 print("4. División")
 print("5. Salir")
while True:
 mostrar_menu()
 opcion = input("Selecciona una opción: ")
 if opcion == '5':
    print("¡Gracias por usar Mi Calculadora!")
    break
 elif opcion < '1' or opcion > '5':
    print("Opción no válida")
 else:
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
 if opcion == '1':
    resultado = operar(suma, num1, num2)
 elif opcion == '2':
    resultado = operar(resta, num1, num2)
 elif opcion == '3':
    resultado = operar(multiplicacion, num1, num2)
 elif opcion == '4':
    resultado = operar(division, num1, num2)
 print("Resultado:", resultado)
 """


#Ejercicio 7

""" 
def operacion(op, a, b):
 if op == 'suma':
    return a + b
 elif op == 'resta':
    return a - b
 elif op == 'multiplicacion':
    return a * b
 elif op == 'division':
    return a / b if b != 0 else "No se puede dividir entre cero"
 else:
    return "Operación no válida"
def mostrar_menu():
 print("\nMi Calculadora")
 print("1. Suma")
 print("2. Resta")
 print("3. Multiplicación")
 print("4. División")
 print("5. Salir")
while True:
 mostrar_menu()
 opcion = input("Selecciona una opción: ")
 if opcion == '5':
    print("¡Gracias por usar Mi Calculadora!")
    break
 elif opcion < '1' or opcion > '5':
    print("Opción no válida")
 else:
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
 if opcion in ['1', '2', '3', '4']:
    operacion_seleccionada = {
 '1': 'suma',
 '2': 'resta',
 '3': 'multiplicacion',
 '4': 'division'
 }[opcion]
 resultado = operacion(operacion_seleccionada, num1,
num2)
 print("Resultado:", resultado)

 """
 print("pedro".capitalize())
 
 Estos programas de Python son calculadoras que permiten al usuario realizar operaciones matemáticas básicas (suma, resta, multiplicación, y división) seleccionando una opción del menú. El programa solicita dos números al usuario y realiza la operación correspondiente según la opción elegida. Si se selecciona la opción de "Salir," el programa finaliza. Cada versión del programa implementa esta funcionalidad de calculadora de manera ligeramente diferente, utilizando distintas estructuras de código, desde un enfoque basado en funciones hasta el uso de clases y métodos para encapsular las operaciones matemáticas.



def suma(a:int|float, b:int|float)->int|float:
    return a+b

res=suma(3,5.3)
print(res)

Este programa de Python define una función llamada "suma" que toma dos argumentos, "a" y "b", que pueden ser enteros o números de punto flotante, y devuelve la suma de estos dos números como resultado. Luego, se llama a esta función con los valores 3 y 5.3 como argumentos, y el resultado se almacena en la variable "res". Finalmente, se imprime el valor de "res", que en este caso sería 8.3, ya que 3 + 5.3 es igual a 8.3. En resumen, este programa calcula y muestra la suma de dos números, incluso si son enteros o números de punto flotante.



#Algoritmo que calcula la suma de los primeros N numeros pares

N=input("Ingresa un numero: ")
N=int(N)
#lista del 1 a N
lista=list(range(1,N+1))
#multiplicar los numeros de la lista por 2
lista2=[i*2 for i in lista]
#suma de los numeros de la lista
suma=sum(lista2)
#imprimir la suma
print(suma)

Este programa de Python calcula la suma de los primeros N números pares. Aquí está el desglose de lo que hace:

El programa solicita al usuario que ingrese un número N.

Luego, crea una lista llamada "lista" que contiene todos los números desde 1 hasta N inclusive.

Después, crea una nueva lista llamada "lista2" utilizando una comprensión de lista. En esta nueva lista, cada número de la lista original es multiplicado por 2, lo que genera una lista con los primeros N números pares.

Luego, calcula la suma de los números en la lista "lista2" y la almacena en la variable "suma".

Finalmente, imprime el valor de "suma", que es la suma de los primeros N números pares.

En resumen, este programa toma un número N ingresado por el usuario, genera los primeros N números pares y calcula su suma, mostrando el resultado.



st.sidebar.title("calculadora ICI")

def operacion_suma():

    name = st.text_input("Nombre: ")
    n1= st.number_input("Numero 1")
    n2= st.number_input("Numero 2")

    if st.button("Sumar"):
        st.success(f"Hola {name}")
        st.write(f"{n1} + {n2} = {n1+n2}")
def operacion_resta():

    name = st.text_input("Nombre: ")
    n1= st.number_input("Numero 1")
    n2= st.number_input("Numero 2")

    if st.button("Restar"):
        st.success(f"Hola {name}")
        st.write(f"{n1} - {n2} = {n1-n2}")
def operacion_multiplicacion():
    name= st.text_input("Nombre: ")
    n1= st.number_input("Numero 1")
    n2= st.number_input("Numero 2")
    if st.button("Multiplicar"):
        st.success(f"Hola {name}")
        st.write(f"{n1} * {n2} = {n1*n2}")
def operacion_division():
    name= st.text_input("Nombre: ")
    n1= st.number_input("Numero 1")
    n2= st.number_input("Numero 2")
    if st.button("Dividir"):
        st.success(f"Hola {name}")
        st.write(f"{n1} / {n2} = {n1/n2}")
def opcion_acercade():
    st.write("Derechos Reservados  ")
    st.write("UCOL-FIME_ICI")

opcion = st.sidebar.selectbox("Opciones", [
    "Suma", "Resta", "Multiplicacion", "Division", "Acerca de"
    ])


match opcion:
    case "Suma":
        st.write("Esta es la opcion de suma... ")
        operacion_suma()
    case "Resta":
        st.write("Esta es la opcion de resta... ")
        operacion_resta()
    case "Multiplicacion":
        st.write("Esta es la opcion de multiplicacion... ")
        operacion_multiplicacion()
    case "Division":
        st.write("Esta es la opcion de division... ")
        operacion_division()
    case "Acerca de":
        opcion_acercade()

#en python no hay constructores se llaman inicializadores

Este programa de Python crea una calculadora web utilizando la biblioteca Streamlit. Aquí hay un resumen de lo que hace:

El programa comienza por establecer un título en la barra lateral de la aplicación web: "calculadora ICI".

Luego, define varias funciones para realizar operaciones matemáticas como suma, resta, multiplicación y división. Estas funciones toman entrada de usuario para dos números y muestran el resultado cuando se hace clic en los botones correspondientes.

También hay una función llamada "opcion_acercade" que muestra información de derechos reservados y la afiliación.

A continuación, se crea una caja de selección en la barra lateral llamada "Opciones" que permite al usuario elegir entre las operaciones matemáticas y la opción "Acerca de".

Se utiliza una estructura "match" para determinar qué acción tomar según la opción seleccionada por el usuario. Dependiendo de la opción elegida, se llama a la función correspondiente para realizar la operación matemática o mostrar información "Acerca de".




 