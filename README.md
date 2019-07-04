# Programacion-Basica-
# UNIDAD 1 INTRODUCCIÓN A PROGRAMACIÓN.

Los ejercicios están diseñados para desarrollar en el alumno la oportunidad de practicar problemas pequeños en pasos, secuenciales adicionalmente se volverá familia las sintaxis de &quot;Python&quot;, desarrollando los siguientes temas. Generar una salida con la sentencia PRINT Leer la entrada de usuario con el teclado usando RAW\_INPUT Realizar los cálculos sencillos con suma(+),resta(-), multiplicacion(),division(/ ó %), modulo

Para poder entrar a la terminal, escribes el comando Python. Para salir de Python utilizas Exit.

• EJEMPLO: print(&#39;Hola mundo&#39;)

Cadena de texto: letras,caracteres para escribir.

\* PROGRAMA 1 EJEMPLO.

Nombre = &#39;Omar Rodrigo Guipio Romero&#39;

 Direccion = &#39;Flor de coral #97, Magdalena Chichicaspa&#39;

Codigo = &#39;52773&#39;

Print = (&#39;Nombre, Direccion, Codigo&#39;)

## VARIABLE FLOTANTE

Esta variable nos ayuda para guardar numeros con punto decimal. para forzar a una variable que sea flotante usaremos (float).

\* OPERADORES

OPERACIÓN DESCRIPCION EJEMPLO

• + SUMA r= 3+2

• - RESTA r=4-7

• - NEGACION r=-7

• x MULTIPLICACION r=2\*6

• xx EXPONENTE r=2 6

• / DIVISION r=3.5/2

• // DIVISION ENTERA r=3.5//2

• % MODULO r=7%2

# UNIDAD 2 CONTROL DE FLUJO

## SENTENCIAS CONDICIONALES

Si una lista no fuera mas que una lista de ordenes a ejecutar en forma de secuencia, una por una, no tendría utilidad, las condiciones nos permiten comprobar condiciones y hacer que nuestro programa se comporte de una manera u otra. -Condición: &#39;if&#39; la forma condicional es &#39;if&#39; seguido de dos puntos (&#39;:&#39;)

• EJEMPLO: &#39;if&#39; (condición o indicación):

 else: identación(cuatro espacios) #codigosa ejecutar en caso de que la indentación sea falsa.





### BUCLES

El bucle while (mientras) ejecuta un fragmento de código mientras se culpa una condición.

• estructura del bucle: while condición:

                  (4 espacios): fragmento del código que se repite

#### CILCO FOR...IN

En Python for se utiliza como una forma genérica de iterar sobre una secuencia es decir recorre una secuencia.

• Secuencia [&#39;uno&#39;, &#39;dos&#39;, &#39;tres&#39;]

• Ejemplo: for (elemento) in (secuencia):

# UNIDAD 3 FUNCIONES.

Las funciones ayudan al programador a dividir problemas en pequeñas piezas que pueden ser reusadas. De igual manera ayuda al programador a escribir funciones ya que es una parte importante del desarrollo del software. En nuestro caso debemos aprender a:

1.- Definir una función para usarla después.

2.- Pasar uno o más valores a una función.

3.- Desarrollar un cálculo completo en una función.

4.- Regresar uno o más resultados a una función.

5.-Llama a una función que previamente hayas definido.

# EJMPLOS:

### 1

nombre=&#39;Omar Rodrigo Guipio Romero &#39;

calle=&#39;Flor de Coral #97&#39;

colonia=&#39;Magdalena Chichicaspa&#39;

municipio=&#39;Huixquilucan&#39;

estado=&#39;Estado de Mexico&#39;

cp=53660

print(nombre +&#39;\n&#39;+ calle +&#39;\n&#39;+ colonia +&#39;\n&#39;+ municipio +&#39;\n&#39;+ estado +&#39;\n&#39; cp)

### 2

print(&#39;Programa para calcular area&#39;)

Largo=float(input(&#39;Ingresa el largo de la habitacion &#39;))

Ancho=float(input(&#39;Ingrese el ancho de la habitacion &#39;))



print(&#39;El Largo de tu habitacion es:&#39;, Largo, &#39;metros&#39;,&#39;\n&#39;, &#39;El ancho de tu habitacion es:&#39; ,Ancho,&#39;metros&#39;,&#39;\n&#39;, &#39;El area de tu habitacion es:&#39;,Largo\*Ancho,&#39;metros cuadrados&#39;)

### 3

restaurante = &quot;La noche&quot;

direccion = &#39;Paraje la canoa S/N &#39;

comida = float(input(&#39;Total de la comida: &#39;))

impuesto = comida/100\*16

propina = comida/100\*10

r = comida + impuesto + propina

print(restaurante)

print(direccion)

print(comida)

print(impuesto)

print(propina)

print( &#39;$&#39; , r , &#39;MNX&#39; )



### 4

widgate1=int(input(&#39;cuantos widgates llevas: &#39;))

gizmo1=float(input(&#39;cuantos gizmos llevas: &#39;))

total=widgate1 + gizmo1

print(&#39;llevas un total de&#39; ,total, &#39;productos en tu pedido&#39;)

peso1=widgate1 \* 75

print(&#39;el peso de tus widgates es de &#39;,peso1,&#39;gramos&#39;)

peso2=gizmo1 \* 112

print(&#39;el peso de tus gizmos es de &#39; ,peso2,&#39;gramos&#39;)

peso= peso1 + peso2

print(&#39;el peso total de tu pedido es&#39; ,peso,&#39;gramos&#39;)

### 5

numero1 = float(input(&#39;insertar nuemero entero: &#39;))

a = numero1

numero2 = float(input(&#39;insertar nuemero entero: &#39;))

b = numero2

suma = a + b

resta = a - b

producto = a \* b

cociente = a / b

reciduo = a % b

resultado = a \*\* b

import math

print(&#39;la suma es&#39; , suma, )

print(&#39;la resta es&#39; , resta, )

print(&#39;el dpricto es&#39; , producto, )

print(&#39;el cociente es&#39; , cociente, )

print(&#39;el reciduo es&#39; , reciduo, )

print(&#39;el resultado es&#39; , resultado, )

print(&#39;el logaritmo de 10 de a es:&#39; ,math.log(a))

### 6

from time import asctime

print(asctime())

### 7

MPG = float(input(&#39;ingresa la cantidad de eficiencia de gasolina en MPG: &#39;))

e = 235.215 / MPG

print(&#39; la eficiencia de la gasolina es: &#39; , e, &#39;en l/100Km&#39; )

### 8

####ESCRIBA UN PREOGRAMA QUE LE DIGA AL USUARIO EL NUMERO DE DIAS, HORAS, MINUTOS Y SEGUNDOS, EL PREOGRAMA DEBE CALCULAR Y DESPLEGAR EL NUMERO DE SEGINDOS TOTALES

print(&#39;Llene los siguientes datos.&#39;)

d=float(input(&#39;Cuantos dias &#39;))

h=float(input(&#39;Cuantas horas &#39;))

m=float(input(&#39;Cuantos minutos &#39;))

s=float(input(&#39;Cuantos segundos &#39;))

t=s+(m\*60)+(h\*3600)+(d\*86400)

print(&#39;El tiempo en segundos es&#39;,t)

###  9

humanos=float(input(&#39;Indique su edad humanos :&#39;))

perros1=((humanos-2)\*(4))+21

perros2=humanos\*10.5

if humanos \&gt; 2:

    print(&#39;la conversion de edad humanos a perros es de &#39;,perros1)

elif humanos \&lt; 0:

    print(&#39;favor de ingresar los datos de forma correcta&#39;)

else:

    print(&#39;la conversion de edad humanos a perros es de &#39;,perros2)

### 10

casilla=str(input(&#39;escoje una casilla? :&#39;))

if casilla == (&#39;a1&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;a3&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;a5&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;a7&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;b2&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;b4&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;b6&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;b8&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;c1&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;c3&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;c5&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;c7&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;d2&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;d4&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;d6&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;d8&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;e1&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;e3&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;e5&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;e7&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;f2&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;f4&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;f6&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;f8&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;g1&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;g3&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;g5&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;g7&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;h2&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;h4&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;h6&#39;):

      print(&#39;casilla negra&#39;)

elif casilla == (&#39;h8&#39;):

      print(&#39;casilla negra&#39;)



else:

            print(&#39;casilla blanca&#39;)
