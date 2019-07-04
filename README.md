# Programacion-Basica
----
## Tutorial de Python.

### Anaconda (distribución de Python).

#### ¿Qué es Anaconda?

Anaconda es un distribución libre y abierta de los lenguajes Python, utilizada en ciencia de datos, y aprendizaje automático. Esto incluye procesamiento de grandes volúmenes de información, análisis predictivo y cómputos científicos. Está orientado a simplificar el despliegue y administración de los paquetes de software.

Las diferentes versiones de los paquetes se administran mediante el sistema de gestión de paquetes conda, el cual lo hace bastante sencillo de instalar, correr, y actualizar software de ciencia de datos y aprendizaje automático como ser Scikit-team, TensorFlow y SciPy.

La distribución Anaconda es utilizada por 6 millones de usuarios e incluye más de 250 paquetes de ciencia de datos válidos para Windows, Linux y MacOS.

#### Instalación de Anaconda.

Aunque instalar Python en una computadora es bastante sencillo, vamos a usar una distribución de Python gratuita llamada Anaconda. Aunque está disponible sólo en inglés, esta distribución incluye multitud de utilidades que nos facilitarán el trabajo y es ideal para empezar. Para instalarla, sólo tienes que descargar la versión de Anaconda para tu sistema operativo desde su página web.

Una vez instalado, sigue los siguientas pasos:

    1. Abrir el buscador de Windows.
    2. Abrir la carpeta "Anaconda(64-bits)".
    3. Hacer click en "Anaconda Prompt" o "Spider".

### Operadores

Tipo de datos básicos.

En python los tipos de datos básicos se dividen en, números, como pueden ser 3 (entero ó integer) 1.75, (punto flotante ó float) 7+5j (complejos ó complex).

Para poder conocer el tipo de dato de una variable susaremos la instrucción "type()".

Otro tipo de dato basico en PYTHON son las cadenas de texto, por ejemplo, "Hola Mundo" (cadena de texto o string ó 'Hola Mundo' ó "Jenny's dog").

Como se puede notar a diferencia de muchos otros lenguajes en PYTHON no se declara el tipo de variable al crearla.

Para resumir en PYTHON se puede reprecentar números enteros, reales, y complejos. Los números enteros son aquellos números positívos o negatívos que no tienen desimales. En la mayor parte de las maquinas las variables enteras ("int") pueden almacrnar números de -2^31 a 2^31. En plataformas de 64 bites el rango es de -2^63 a 2^63.

Los números flotantes son los que tienen decimales. En PYTHON se expresan mediante el tipo "float" se puede representar números de -2^64 a 2^64.

Los números complejos son aquellos que tienen una parte imaginaria. Para definir una variable compleja se utiliza en termino "complex".

Operadores:

		suma                    r=3+2
		resta	                r=4-7
            (guión) negación        r=-7
		multiplicación		r=2*6
		exponente		r=2**6
		división		r=3.5/2
		división entera		r=3.5//2
		modulo (residuo)	r=7%2

Un ejemplo de esto puede ser el siguiente:

    a=int(input('Incerta un numero '))   
    b=int(input('Incerta otro numero '))

    s=a+b   
    print('La suma es ' ,s)    
    r=b-a   
    print('La resta es ' ,r)    
    m=a*b   
    print('El producto es ' ,m)   
    d=a/b   
    print('El residuo es ' ,d)   
    dd=b/a
    print('El resultado es ' ,dd)    
    p=a**b   
    print('El resultado de "a" a la "b" es ' ,p)   
    import math    
    print('El logaritmo es ' ,math.log10(a))

### Sentencias condicionales.

Si un programa no fuera más que una lista de ordenes a ejecutar de forma secuencial, una por una, no tendria mucha utilidad. Las condicionales nos permiten comparar condicionales y hacer que nuestp programa se comparte de una forma u otra, que ejecute un fragmento de código u otro, dependiendo de esas condiciones.

#### Condicional if.

La dorma más simple de una sentencia condicionales el "if" (del ingles "si") seguida de la condición a evaluar,(:) y en la siguiente linea in dentado, el codigo a ejutar en caso de que se cumpla sicha condición, como se muestra en el siguiente código, que muestra el color de la casilla de un tablero de ajedres.

    casilla=str(input('escoje una casilla? :'))
    if casilla == ('a1'):
          print('casilla negra')
    elif casilla == ('a3'):
          print('casilla negra')
    elif casilla == ('a5'):
          print('casilla negra')
    elif casilla == ('a7'):
          print('casilla negra')
    elif casilla == ('b2'):
          print('casilla negra')
    elif casilla == ('b4'):
          print('casilla negra')
    elif casilla == ('b6'):
          print('casilla negra')
    elif casilla == ('b8'):
          print('casilla negra')
    elif casilla == ('c1'):
          print('casilla negra')
    elif casilla == ('c3'):
          print('casilla negra')
    elif casilla == ('c5'):
          print('casilla negra')
    elif casilla == ('c7'):
          print('casilla negra')
    elif casilla == ('d2'):
          print('casilla negra')
    elif casilla == ('d4'):
          print('casilla negra')
    elif casilla == ('d6'):
          print('casilla negra')
    elif casilla == ('d8'):
          print('casilla negra')
    elif casilla == ('e1'):
          print('casilla negra')
    elif casilla == ('e3'):
          print('casilla negra')
    elif casilla == ('e5'):
          print('casilla negra')
    elif casilla == ('e7'):
          print('casilla negra')
    elif casilla == ('f2'):
          print('casilla negra')
    elif casilla == ('f4'):
          print('casilla negra')
    elif casilla == ('f6'):
          print('casilla negra')
    elif casilla == ('f8'):
          print('casilla negra')
    elif casilla == ('g1'):
          print('casilla negra')
    elif casilla == ('g3'):
          print('casilla negra')
    elif casilla == ('g5'):
          print('casilla negra')
    elif casilla == ('g7'):
          print('casilla negra')
    elif casilla == ('h2'):
         print('casilla negra')
    elif casilla == ('h4'):
          print('casilla negra')
    elif casilla == ('h6'):
          print('casilla negra')
    elif casilla == ('h8'):
          print('casilla negra')
    else:
          print('casilla blanca')

O transformar algo tan común, como la tu edad, a años perros.

    humanos=float(input('Indique su edad humanos :'))
    perros1=((humanos-2)*(4))+21
    perros2=humanos*10.5
    if humanos > 2:
        print('la conversion de edad humanos a perros es de ',perros1)
    elif humanos < 0:
        print('favor de ingresar los datos de forma correcta')
    else: 
        print('la conversion de edad humanos a perros es de ',perros2)

### Bucle While.

Mientras que las condicionales permiten ejecutar distintos fragmentos de código dependiendo de ciertas condiciones, los bucles permiten ejecutar un mismo fragmento de código un cierto número de veces, mientras se cumpla una determinada acción condición.

El bucle while(en español "mientras") ejecuta un fradmento de código, mientras se cumpla la condición, tiene la siguiente estructura:

    llave='0123'
    pasword=''
    while True :
        pasword=input('inserte su pasword:')
        if pasword== llave:
            print('felicidades, entraste al sistema')
            break
        else:
            print('pasword incorrecto')
            print('intente de nuevo')    
    print('fin de programa')

### Ciclo For.

En pyhton "for" se utiliza como una forma genérica de interés sobre una secuencia, es decir, recorrer una secuencia.

    variable = secuencia  
    secuencia = ["uno", "dos", "tres"]  //estos son elementos
    for elemento in secuencia:
        print(elemento)                //4 esopacios 

Y los resultados serán:

    uno
    dos
    tres
    
El siclo "for" debe marcarse con un rango como se muestra de la siguiente manera:

    for temperatura in range(0,100,10):    //range es el rango y va el inicio, hasta
                                             donde quiero llegar y en este caso va de 10
    print(temperatura,'gC')                  en 10.

Un ejemplo del ciclo "for" puede ser el siguiente:

    for celcius in range(0,101,10):
        farenheit = (1.8*celcius)+32
        print(celcius,'gC','|',farenheit,'gF')

También se puede hacer una lista de descuentos, como se muestra en el siguiente caso:

    for precio in range(4,201,5):
        precio=(precio+0.95)
        descuento = (precio*0.60)
        preciof=(precio-descuento)
        print(precio,'$','|',"{:.2f}".format(descuento),'|',"{:.2f}".format(preciof,'$'))

O incluso puedes hacer una tabla de multiplicar.

    print(' ',1,2,3,4,5,6,7,8,9,10)
    for a in range(1,11,1):
        x=a*1
        b=a*2
        c=a*3
        d=a*4
        e=a*5
        f=a*6
        g=a*7
        h=a*8
        i=a*9
        j=a*10
        print(x,a,b,c,d,e,f,g,h,i,j)

### Modulo Turlte 
Hay muchos módulos en python que proveen características poderosas que podemos usar en nuestros propios programas. Algunos de estos pueden enviar correos electrónicos y algunos de estos pueden extraer información de paginas de Internet. Para el manejo de gráficos usaremos un modulo que permite crear figuras y patrones. El modulo que se usara permiten desarrollar nuestro pensamiento computacional.

      
    import turtle
    ventana=turtle.Screen()	//Crea una ventana en blanco			
    alex=turtle.Turtle()	//Crear un objeto de la clase turtle lo puedo llamar como yo quiera se llama "alex" y puede tener atributos
    alex.forward(50)	        //Avanza 50 unidades
    alex.left(90)		//gira a la izquierda 90°
    alex.forward(30)	        //Avanza 30 unidades
    ventana.mainloop()	//Hasta que el usuario cierra la ventana el programa termina

Un ejemplo del modulo Turtle puede ser:

     import turtle
     ventana=turtle.Screen()
     alex=turtle.Turtle()
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     ventana.mainloop()


Te aparecera una flecha, y no como tal una tortuga, pero si la quisieras ponlo de la siguiente manera:

    import turtle
    ventana=turtle.Screen()
    ventana.bgcolor('red')
    ventana.title("Hola")

    alex=turtle.Turtle()
    alex.shape("turtle")
    alex.color("blue")
    alex.pensize(10)
    alex.forward(100)
    alex.left(120)
    alex.forward(100)
    ventana.mainloop() 

Aparte de poder figuras con el mismo codigo, y escojer el color de fondo o el color de la,  las tortugas:

    a=input('Escoje un color de los siguientes para la ventana: brown chocolate coral red pink purple blue green yellow black :  ')
    b=input('Escoje un color de los siguientes para la tortuga 1: brown chocolate coral red pink purple blue green yellow black :  ')
    c=input('Escoje un color de los siguientes para la tortuga 2: brown chocolate coral red pink purple blue green yellow black :  ')
    import turtle
    ventana=turtle.Screen()
    ventana.bgcolor(a)
    ventana.title("Hola, Kary bebe")
    kary=turtle.Turtle()
    kary.shape("turtle")
    kary.color(b)
    kary.pensize(5)
    kary.forward(100)
    kary.left(120)
    kary.forward(100)
    kary.left(120)
    kary.forward(100)
    kary.left(120)
    kary.forward(100)
    kar=turtle.Turtle()
    kar.shape("turtle")
    kar.color(c)
    kar.pensize(5)
    kar.forward(100)
    kar.left(-120)
    kar.forward(100)
    kar.left(-120)
    kar.forward(100)
    kar.left(-120)
    kar.forward(100)
    ventana.mainloop() 
 
Puedes hacer también puedes hacer círculos con el Modulo Turtle, como este: 

    import turtle
    ventana=turtle.Screen()
    ventana.bgcolor("black")
    ventana.title("Hola")
    leo=turtle.Turtle()
    mike=turtle.Turtle()
    leo.shape("turtle")
    leo.color("green")
    leo.pensize(2)
    mike.shape("turtle")
    mike.color("red")
    mike.pensize(2)
    leo.speed(9)
    mike.speed(10)
    leo.penup()
    mike.penup()
    leo.setpos(0,-50)
    leo.pendown()
    leo.circle(50)
    mike.setpos(0,-100)
    mike.pendown()
    mike.circle(100)
    ventana.mainloop()

Incluso, con el Modulo Turtle, puedes poner imagenes. Pero solo imagenes que tengan extención ".gif", como se muestra en el siguiente caso:
(Nota: Tienes que guardar la imagen en la misna carpeta, donde estas guardando el programa)

    import turtle
    ventana=turtle.Screen()
    ventana.setup(1000, 500)
    ventana.tracer(0)
    ventana.addshape("mario.gif")
    mario=turtle.Turtle()
    mario.speed(0)
    mario.shape("mario.gif")
    mario.penup()
    mario.goto(-500, 0)
    while True:
        ventana.update()
        mario.forward(.5)

Y si quieres, incluso puedes hacer que la imagien rebote en el orde de la ventana.

    import turtle
    window= turtle.Screen()
    window.addshape("mario.gif")
    border= turtle.Turtle()
    border.speed(0)
    border.up()
    border.hideturtle()
    border.pensize(0)
    border.color('white')
    border.goto(500,500)
    border.down()
    border.goto(500,-500)
    border.goto(-500,-500)
    border.goto(-500,500)
    border.goto(500,500)
    camino=turtle.Turtle()
    camino.speed(0)
    camino.shape("mario.gif")
    camino.up()
    dx=1
    while True:
        x,y= camino.position()
        if x+dx>=500 or x+dx<=-500:
            dx=-dx
        camino.goto(x+dx,y)
    window.mainloop()

### Funciónes 

Una función es un fragmento de código con un nombre asociado que realiza una serie de tareas y devuelve un valor. A demás de ayudarnos a programar y depurar dividiendo el programa en partes, las funciones también permiten reutilizar código.
     
	##definicion de una funcion
	def ladra():
	    print('guau, guau')
	##cuerpo principal del programa
	ladra()
Las Funciones ayudan al programador a dividir un problema en pequeñas piezas que pueden ser re usadas. También ayudan al programador a concentrarse en una pequeña parte del programa a la vez. Como resultado el escribir funciones es una parte importante del desarrollo del sofware. 

En nuestro caso debemos aprender a:

	1. Definir una función para usarla después.
	2. Pasar uno o más valores a una función.
	3. Desarrollar un cálculo complejo en una función.
	4. Regresar uno o más resultados a una función.
	5. Llamar a una función que previamente hayamos definido.

Puede también colocarce el Modulo Turtle con algunos de los ciclos, como se muestra este, con Ciclo For:

    import turtle
    def dibujar_cuadro(tur, d):
        for i in range(4):
            tur.forward(d)
            tur.left(90)
    ventana=turtle.Screen()
    ventana.bgcolor('green')
    ventana.title('Funciones')
    rafa = turtle.Turtle()
    dona = turtle.Turtle()
    dibujar_cuadro(rafa, 50)
    dibujar_cuadro(dona, 200)
    ventana.mainloop()

O también se pueden cambiar el color de las lineas.

    import turtle
    def dibujar_cuadro(tur, d):
        for i in ['red','purple','blue','yellow']:
            tur.color(i)
            tur.forward(d)
            tur.left(90)
    ventana=turtle.Screen()
    ventana.bgcolor('green')
    ventana.title('Funciones')
    rafa = turtle.Turtle()
    dona = turtle.Turtle()
    dibujar_cuadro(rafa, 50)
    dibujar_cuadro(dona, 200)
    ventana.mainloop()

Incluso, con el mismo ciclo, puedes cambiar el angulo y el tamaño de las figuras.

    import turtle
    def dibujar_multiples_cuadro(tur, d):
        for i in ['red','purple','blue','yellow']:
            tur.color(i)
            tur.forward(d)
            tur.left(90)
    ventana=turtle.Screen()
    ventana.bgcolor('black')
    ventana.title('Funciones')
    alex = turtle.Turtle()
    alex.pensize(3)
    d=20
    for i in range(50):
        dibujar_multiples_cuadro(alex, d)
        d = d+10
        alex.forward(10)
        alex.right(18)
    ventana.mainloop()

O no solo que vallan creciendo, sino, que se queden en un mismo tamaño.

    import turtle

    def dibujar_cuadro_caracol(tur, d):
        for i in  ['red','blue','green','yellow']:
            tur.color(i)
            tur.forward(d)
            tur.left(90)

    ventana=turtle.Screen()
    ventana.bgcolor('black')
    ventana.title('funciones')

    alex=turtle.Turtle()
    alex.pensize(2)
    alex.speed(100)

    d=100

    for i in range(20):
        dibujar_cuadro_caracol(alex, d)
    
        alex.forward(10)
        alex.right(18)
        alex.setpos(0, 0)




    ventana.mainloop()

O hacer suceciones de un cuadrado, como se muestra en el siguiente programa:

    import turtle


    def dibujar_cuadro_seguir(tur, p):
        for i in range(4):
            tur.forward(20)
            tur.left(90)
    

    ventana=turtle.Screen()
    ventana.bgcolor('blue')
    ventana.title('funciones')

    omar=turtle.Turtle()
    omar.pensize(5)
    omar.speed(2)

    p=30

    for i in range(5):
        dibujar_cuadro_seguir(omar, 5)

        omar.penup()
        omar.setpos(p,0)
        omar.pendown()
        p=p+30

Y no solo que vallan hacia un lado, sino que, también pueden hacerce cuadrados más grandes.

    import turtle

    def dibujar (tur,d):
        for i in range(4):
            tur.color('blue')
            tur.forward(d)
            tur.left(90)
     
     
    ventana=turtle.Screen()
    ventana.bgcolor('black')
    ventana.title('funciones')

    alex=turtle.Turtle()
    alex.pensize(3)
    alex.speed(20)

    m=-10

    for i in range(20,1591,20):
        dibujar(alex,i)
        alex.penup()
        alex.goto(m,m)
        alex.pendown()
        m=m-10

    ventana.mainloop()

O hacer incluso algo más extenzo y con un poco más de estética:
 
    import turtle

    def cuadrado(tur, d):
        f=90
        for i in  range(500):
            tur.color('blue') 
            tur.forward(d)
            tur.left(f)
            d=d+5
            f=f+0.02
        
    ventana=turtle.Screen()
    ventana.bgcolor('black')
    ventana.title('funciones')

    d=15
    alex=turtle.Turtle()
    alex.speed(25)

    cuadrado(alex, d)

    ventana.mainloop()

### Programación Ambientada a Objetos.

Al principio del curso comentavamos que Python es un lenguaje multiparadigma en el que se podía trabajar con programación estructurada, como veniamos haciendo ahora o con programación orientada a objetos el cual es un paradigma de programación en el que los conceptos del mundo real relevantes para nuestro problema se modelan a travéz de clases y objetos, y en el que nuestro programa consiste en una serie de interacciones entre objetos.

> OBJETOS:

> Un objetos es una entidad que agrupa un estado y una funcionalidad relacionada. El estado del objeto se define a través de variables llamadas atributos, mientras que la funcionalidad de modela a través de funciones a las que se les conoce con el nombre de MÉTODOS DEL OBJETOS.

> **Diagrama UML sirve para definir un objeto y culales son su métodos y sus atributos**

> Un ejemplo de objeto podría ser un coche en el que tendriamos Atributos como: la marca, el numero de puertas, o el color.

> Y Métodos como: arrancar, parar.

> O bien cualquier otra combinación de Atributos y Métodos según lo que fuera relevante para nuestro programa.

> CLASES:

> Una clase no es más que una plantilla genérica de la cual insancia los objetos; es la plantilla que define que Atributos y Métodos tendrán los objetos de esa clase.

En PYTHON las clases de definen Mediante la palabra clave "CLASS" seguido del nombre de la clase, seguido por dos puntos, y a continicación, inentado el cuerpo de la clase.

Por ejemplo:

    class Coche(object):
        def __init__(self,gasolina):
            self.gasolina = gasolina
        def arrancar(self):
            if self.gasolina > 0:
                print('Arranca')
            else:
                print('No Arranca')
        def conducir(self):
            if self.gasolina > 0:
                self.gasolina = self.gasolina - 1
                print('Quedan ', self.gasolina,' litros')
            else:
                print('No se mueve')
    vocho = Coche(5)
    tsuru = Coche(3)

    vocho.arrancar()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir() 

Pero no solo puedes poner algo en común, como un carro, si no también puedes hacer que el programa detecte si es o no, una figura, como por ejemplo un triangulo.

    class Triangulo(object):
        def __init__(self,angulo1,angulo2,angulo3):
            self.angulo1 = angulo1
            self.angulo2 = angulo2
            self.angulo3 = angulo3
        def ChecarAngulo(self):
            if self.angulo1+self.angulo2+self.angulo3 == 180:
                print('Es un triangulo')
            else:
                print('No es un triangulo')
    miTriangulo=Triangulo(90,30,60)
    miTriangulo.ChecarAngulo()

O incluso, puedes hacer que un programa continue una canción en texto.

    class Cancion(object):
        def __init__(self,letra):
            self.letra = letra
        def cantame(self):
            print(self.letra)
    micumpleanos=Cancion(["...que cantaba el rey David," " hoy por ser dia de tu santo," " te las cantamos a ti."])
    micumpleanos.cantame()
    
### Ejercicios hechos en clase.
 
#### Ejercicio 1
	nombre='Marco Antonio Becerra Ortega'
	calle='Carrera Naucalpan Toluca #794'
	colonia='San Rafael Chamapa'
	municipio='Naucalpan'
	estado='Estado de Mexico'
	cp=53670
	print( nombre,'\n',calle,'\n', colonia,'\n', municipio,'\n', estado,'\n', cp)
![ejercicio1](https://user-images.githubusercontent.com/52546998/60686928-1908a200-9e71-11e9-85ed-befccb71e491.PNG)

#### Ejercicio 2
	print('ingresa tu nombre')
	nombre=input()
	print('hola ' + nombre + ' :3')
![ejercicio2](https://user-images.githubusercontent.com/52546998/60686945-2c1b7200-9e71-11e9-8ebd-3323001d1d08.PNG)

#### Ejercicio 3
	print('Programa para calcular area')
	Largo=float(input('Ingresa el largo de la habitacion '))
	Ancho=float(input('Ingrese el ancho de la habitacion '))
	print('El Largo de tu habitacion es:', Largo, 'metros','\n', 'El ancho de tu habitacion es:' ,Ancho,'metros','\n', 'El area de tu habitacion es:',Largo*Ancho,'metros cuadrados')  
![ejercicio3](https://user-images.githubusercontent.com/52546998/60687220-d9db5080-9e72-11e9-9ec8-ee9c0fad8c72.PNG)

#### Ejercicio 4
	l=float(input('indica el largo de una cancha de futbol en metros: '))
	a=float(input('indica el ancho de una cancha de futbol en metros: '))
	areax=l*a
	area=float(areax*0.000247105)
	print('El area de una cancha de futbol es de ', area, 'acres')
![ejercicio4](https://user-images.githubusercontent.com/52546998/60688205-5b35e180-9e79-11e9-8529-256282d1cace.PNG)

#### Ejercicio 5
	print('Recicle Botellas')
	un_litro=int(input('Cuantas botellas vas a poner '))
	mas_litro=int(input('Cuantas botellas vas a poner de mas litros '))
	pago=(un_litro*mas_litro)
	pagom=(un_litro*1)
	pagon=float=(mas_litro*2.50)
	pagot=(pagom+pagon)
	print('se te va a dar $',pagot,'pesos')
![ejercicio5](https://user-images.githubusercontent.com/52546998/60688263-ba93f180-9e79-11e9-9f7d-563dfffc80a1.PNG)
 
#### Ejercicio 6
	print('Bienvenido al restaurante Juanito')
	print('Carretera Naucalpan Toluca #794 Col. San Rafael Chamapa  CP. 53660')
	print('Tu orden fue de: ')
	comida=input()
	costo=50
	print('Tu ','comida', 'vale $' ,costo)
	iva=0.16
	con_iva=float(costo*iva)
	print('Con IVA es $ ',con_iva)
	prop=0.10
	con_prop=float(costo*prop)
	print('Con propina son $' ,con_prop)
	total=con_iva+con_prop
	tot=costo+total
	print('Tu total es de $' ,tot)
![ejercicio6](https://user-images.githubusercontent.com/52546998/60688268-c384c300-9e79-11e9-960d-b4cd2f6fef7d.PNG)


#### Ejercicio 7
	n=int(input('Indique un numero :'))
	s=int((n*(n+1))/2)
	print('El resultado es ', s)
![ejercicio7](https://user-images.githubusercontent.com/52546998/60688274-cda6c180-9e79-11e9-85b3-a6b8ab4d1446.PNG)

#### Ejercicio 8
	w=int(input('Indique el numero de widget  :'))
	g=int(input('Indique el numero de gizmos  :'))
	p1=w*75
	p2=g*112
	pt=int(p1+p2)
	print('El peso total de los productos adquiridos es de ', pt , 'gramos')
![ejercicio8](https://user-images.githubusercontent.com/52546998/60688276-d26b7580-9e79-11e9-94a1-d082fd5493e8.PNG)

#### Ejercicio 9
	s=float(input('Indique la cantidad de saldo que tiene la cuenta :'))
	s1=float(s*0.4)+s
	s2=float((s1*0.4)*2)+s
	s3=float((s2*0.4)*3)+s
	print(' El saldo que se tendra en la primer aunalidad es de ', s1 , 'pesos','\n',
	'El saldo que se tendra en la segunda aunalidad es de ', s2, 'pesos','\n',
	'El saldo que se tendra en la tercera aunalidad es de ', s3, 'pesos')
![ejercicio9](https://user-images.githubusercontent.com/52546998/60688279-d6979300-9e79-11e9-8a64-effb35794203.PNG)

#### Ejercicio 10
	import math
	a=int(input('indique la variable a :'))
	b=int(input('indique la variable b :'))
	r1=a+b
	r2=b-a
	r3=a*b
	r4=a//b
	r5=a%b
	r6=a**b
	print(' la suma de a+b es ', r1, '\n',
	'La resta de b-a es ', r2, '\n' ,
	'El producto de a y b es ', r3, '\n',
	'El cociente cuando a es dividido por b es  ', r4, '\n',
	'El residuo cuando a es dividido por b es  ', r5, '\n',
	'El resultado de a a la b  ', r6, '\n',
	'El resultado de log10 a es ', math.log(a), '\n')
![ejercicio10](https://user-images.githubusercontent.com/52546998/60688282-db5c4700-9e79-11e9-8478-1390f8057c67.PNG)
 
#### Ejercicio 11
	g=float(input('Indique el MPG :'))
	l=float(235.21/g)
	print('La convercion de MPG a litros/100km es' , l)
![ejercicio11](https://user-images.githubusercontent.com/52546998/60688283-e020fb00-9e79-11e9-814f-5e17dde7473d.PNG)

#### Ejercicio 12
	import math
	t1=int(input('Indique la latitud del primer punto de la tierra en grados :'))
	g1=int(input('Indique la longitud del primer punto de la tierra en grados :'))
	t2=int(input('Indique la latitud del segundo punto de la tierra en grados :'))
	g2=int(input('Indique la longitud del segundo punto de la tierra en grados :'))
	st1=(math.sin(t1))
	st2=(math.sin(t2))
	ct1=(math.cos(t1))
	ct2=(math.cos(t2))
	cg12=(math.cos(g1-g2))
	ac=(math.acos(st1*st2+ct1*ct2*cg12))
	d=float(6371.01*ac)
	print('La distancia entre los puntos que siguen la superficie de la tierra es ',"{:.2f}".format(d) , 'Km')
![ejercicio12](https://user-images.githubusercontent.com/52546998/60688286-e44d1880-9e79-11e9-9410-0eb5bd3086cc.PNG)

#### Ejercicio 13
	import math
	r=float(input('Indique el radio de un circulo :'))
	p=math.pi
	a=p*(r**2)
	v=((4/3)*p*(r**3))
	print('El area de un circulo es ',"{:.2f}".format(a),'\n', 'El volumen de una esfera es ',"{:.2f}".format(v))
![ejercicio13](https://user-images.githubusercontent.com/52546998/60688288-e7e09f80-9e79-11e9-893d-683d022c4c8e.PNG)

#### Ejercicio 14
	d=int(input('indique los dias :'))
	h=int(input('indique las horas :'))
	m=int(input('indique los minutos :'))
	s=int(input('indique los segundos :'))
	t=s+(m*60)+(h*3600)+(d*86400)
	print('El tiempo trascurrido es  ', t ,'segundos')
![ejercicio14](https://user-images.githubusercontent.com/52546998/60688291-eb742680-9e79-11e9-88c3-c5d735ac1a34.PNG)

#### Ejercicio 15
	from time import asctime
	print(asctime())
![ejercicio15](https://user-images.githubusercontent.com/52546998/60688297-f16a0780-9e79-11e9-85f2-7d6e9970125e.PNG)

#### Ejercicio 16
	import turtle
	import time
	from math import sin, pi
	from random import random
	def circle_dance(population=11, resolution=480, loops=1, flip=0, lines=0):
	    population = int(population)
	    resolution = int(resolution)
	    radius = 250
	    screen = turtle.Screen()
	    screen.tracer(0)
	    if lines:
	        arrange_lines(population, radius)
	    turtles = [turtle.Turtle() for i in range(population)]
	    for i in range(population):
	        dancer = turtles[i]
	        make_dancer(dancer, i, population)
	    animate(turtles, resolution, screen, loops, flip, radius)
	def arrange_lines(population, radius):
	    artist = turtle.Turtle()
	    for n in range(population):
	        artist.penup()
	        artist.setposition(0, 0)
	        artist.setheading(n / population * 180)
	        artist.forward(-radius)
	        artist.pendown()
	        artist.forward(radius * 2)
	    artist.hideturtle()
	def make_dancer(dancer, i, population):
	    dancer.setheading(i / population * 180)
	    dancer.color(random_turtle_colour())
	    dancer.penup()
	    dancer.shape('turtle')
	    dancer.turtlesize(2)
	def random_turtle_colour():
	    return random() * 0.9, 0.5 + random() * 0.5, random() * 0.7
	def animate(turtles, resolution, screen, loops, flip, radius):
	    delay = 4 / resolution      # 4 seconds per repetition
	    while True:
	        for step in range(resolution):
        	    timer = time.perf_counter()
	            phase = step / resolution * 2 * pi
	            draw_dancers(turtles, phase, screen, loops, flip, radius)
	            elapsed = time.perf_counter() - timer
	            adjusted_delay = max(0, delay - elapsed)
	            time.sleep(adjusted_delay)
	def draw_dancers(turtles, phase, screen, loops, flip, radius):
	    population = len(turtles)
	    for i in range(population):
	        individual_phase = (phase + i / population * loops * pi) % (2*pi)
	        dancer = turtles[i]
	        if flip:
	            if pi / 2 < individual_phase <= 3 * pi / 2:
	                dancer.settiltangle(180)
	            else:
	                dancer.settiltangle(0)
	        distance = radius * sin(individual_phase)
	        dancer.setposition(0, 0)
	        dancer.forward(distance)
	    screen.update()
	if __name__ == '__main__':
	    import sys
	    circle_dance(*(float(n) for n in sys.argv[1:]))
![ejercicio16](https://user-images.githubusercontent.com/52546998/60688299-f5962500-9e79-11e9-9b43-76236af26171.PNG)
	   
#### Ejercicio 17 
	entero=int(input('Introdusca un numero entero :'))
	par=entero%2
	if par == 0:
	    print('El numero es par')
	else:
	    print('El numero no es par')
![ejercicio17](https://user-images.githubusercontent.com/52546998/60688303-fa5ad900-9e79-11e9-994d-5f427fbfbcb8.PNG)
    
#### Ejercicio 18
	humanos=float(input('Indique la edad humana :'))
	perros1=((humanos-2)*(4))+21
	perros2=humanos*10.5
	if humanos > 2:
	    print('la conversion de anos humanos a perros es de ',perros1)
	elif humanos < 0:
	    print('favor de ingresar los datos de forma correcta')
	else: 
	    print('la conversion de edad humana a perros es de ',perros2)
![ejercicio18](https://user-images.githubusercontent.com/52546998/60688310-047cd780-9e7a-11e9-9e60-ba11ccb8fde8.PNG)
	    
#### Ejercicio 19
	import numpy as np
	import matplotlib.pyplot as plt
	
	#creando un vector nuerico
	y=int(input('que quieres graficar:\n 1 seno\n 2 coseno\n 3 tangente\n'))
	
	x=np.arange(100)
	y1=np.sin(x)
	y2=np.cos(x)
	y3=np.tan(x)
	
	if y == 1:
	    plt.plot(x,y1)
	elif y == 2:
	    plt.plot(x,y2)
	elif y == 3:
	    plt.plot(x,y3)
	else:
	    print('Ingrese la opcion adecuada')
	
	#graficar
	plt.show()
![ejercicio19](https://user-images.githubusercontent.com/52546998/60688311-0b0b4f00-9e7a-11e9-8f9c-1fc792e7476e.PNG)
	
#### Ejercicio 20
	c=str(input('Indique la letra del tabero'))
	f=int(input('Indique el numero del tabero'))
	x=('c'*f)
	x=(len(x))
	print(x)
![ejercicio20](https://user-images.githubusercontent.com/52546998/60688315-11013000-9e7a-11e9-8141-ef06e7e984b2.PNG)

#### Ejercicio 21
	for celcius in range(0,101,10):
	    farenheit = (1.8*celcius)+32
	    print(celcius, 'gC','|', farenheit, 'gF')
![ejercicio21](https://user-images.githubusercontent.com/52546998/60688320-16f71100-9e7a-11e9-897d-d9a6fc8b7cfb.PNG)
    
#### Ejercicio 22
	for precio in range(4,200,5):
	    precio=(precio+0.95)
	    descuento=(precio*0.60)
	    precio1=precio-descuento
	    print(precio,"|","{:.2f}".format(descuento),"|","{:.2f}".format(precio1))
![ejercicio22](https://user-images.githubusercontent.com/52546998/60688323-1b232e80-9e7a-11e9-9842-07ec07cefebc.PNG)

#### Ejercicio 23
	print(' ',1,2,3,4,5,6,7,8,9,10)
	for a in range(1,11,1):
	    x=a*1
	    b=a*2
	    c=a*3
	    d=a*4
	    e=a*5
	    f=a*6
	    g=a*7
	    h=a*8
	    i=a*9
	    j=a*10
	    print(x,a ,b ,c ,d ,e ,f ,g ,h ,i ,j)
![ejercicio23](https://user-images.githubusercontent.com/52546998/60688329-1f4f4c00-9e7a-11e9-8171-1dc4ae65ac06.PNG)
    
#### Ejercicio 24
	def tarifa(kilometros):
	    precio=7.25+(7*kilometros)
	    if precio < 40:
	        precio=40
	    return precio
	kilometros=float(input('Indique los kilometros :'))
	n=tarifa(kilometros)
	print(n)
![ejercicio24](https://user-images.githubusercontent.com/52546998/60688337-26765a00-9e7a-11e9-8c76-5fe030db2e56.PNG)

#### Ejercicio 25
	def tarifa(producto):
	  
	    tarifa=150+45*(producto-1)
	    
	    if producto == 1:
	        tarifa=150
	    elif producto == 0:
	        tarifa=0
	        
	    return tarifa
	producto=float(input('Ingresa el numero1 de productos :'))
	total=tarifa(producto)
	
	print(total)
![ejercicio25](https://user-images.githubusercontent.com/52546998/60688340-2c6c3b00-9e7a-11e9-88fb-2d8c65b600ee.PNG)

#### Ejercicio 26
	def producto(envio):
	    producto = 150+45*(envio-1)
	    if envio==1:
	        return 150
	    elif envio==0:
	        return 0
	    return producto
	
	envio=float(input('Cuantos articulos vas a pedir? '))
	b=producto(envio)
	print (b)
![ejercicio26](https://user-images.githubusercontent.com/52546998/60688345-30985880-9e7a-11e9-8f8d-e9225a603431.PNG)

#### Ejercicio 27
	import turtle
	ventana=turtle.Screen()
	alex=turtle.Turtle()
	alex.forward(100)
	alex.left(90)
	alex.forward(100)
	alex.left(90)
	alex.forward(100)
	alex.left(90)
	alex.forward(100)
	alex.left(90)
	alex.forward(100)
	ventana.mainloop()
![ejercicio27](https://user-images.githubusercontent.com/52546998/60688349-342bdf80-9e7a-11e9-8797-00622daecb3f.PNG)

#### Ejercicio 28
	import turtle
	ventana=turtle.Screen()
	ventana.bgcolor("yellow")
	ventana.title("Hola, Kary bebe")
	kary=turtle.Turtle()
	kary.color("blue")
	kary.pensize(5)
	kary.forward(100)
	kary.left(120)
	kary.forward(100)
	ventana.mainloop() 
![ejercicio28](https://user-images.githubusercontent.com/52546998/60688351-3857fd00-9e7a-11e9-8f9c-142cb8cebc16.PNG)

#### Ejercicio 29
	#Modificar el programa anterior para que antes de crear la ventana se le pregunte al usuario que color de fondo desea. Debe de guardar la respuesta del usuario en una variable y modificar el color de fondo de la ventana de acuerdo a los deceos del usuario.

	a=input('Escoje un color de los siguientes para la ventana: brown chocolate coral red pink purple blue green yellow black :  ')
	
	import turtle
	ventana=turtle.Screen()
	ventana.bgcolor(a)
	ventana.title("Hola amor")
	
	kary=turtle.Turtle()
	kary.shape("turtle")
	kary.color("blue")
	kary.pensize(10)
	kary.forward(100)
	kary.left(120)
	kary.forward(100)
	ventana.mainloop() 
![ejercicio29](https://user-images.githubusercontent.com/52546998/60688355-3c841a80-9e7a-11e9-93ca-8c7032abacf1.PNG)

#### Ejercicio 30
	a=input('Escoje un color de los siguientes para la ventana: brown chocolate coral red pink purple blue green yellow black :  ')

	b=input('Escoje un color de los siguientes para la tortuga 1: brown chocolate coral red pink purple blue green yellow black :  ')

	c=input('Escoje un color de los siguientes para la tortuga 2: brown chocolate coral red pink purple blue green yellow black :  ')

	import turtle
	ventana=turtle.Screen()
	ventana.bgcolor(a)
	ventana.title("Hola, Kary bebe")

	kary=turtle.Turtle()
	kary.shape("turtle")
	kary.color(b)
	kary.pensize(5)

	kary.forward(100)
	kary.left(120)
	kary.forward(100)
	kary.left(120)
	kary.forward(100)
	kary.left(120)
	kary.forward(100)

	kar=turtle.Turtle()
	kar.shape("turtle")
	kar.color(c)
	kar.pensize(5)

	kar.forward(100)
	kar.left(-120)
	kar.forward(100)
	kar.left(-120)
	kar.forward(100)
	kar.left(-120)
	kar.forward(100)

	ventana.mainloop() 
![ejercicio30](https://user-images.githubusercontent.com/52546998/60688364-40b03800-9e7a-11e9-885d-4e98ae673a25.PNG)

#### Ejercicio 31
	import turtle
	ventana=turtle.Screen()
	ventana.bgcolor("black")
	ventana.title("Hola, Kary bebe")

	omar=turtle.Turtle()
	kary=turtle.Turtle()

	omar.shape("turtle")
	omar.color("green")
	omar.pensize(2)

	kary.shape("turtle")
	kary.color("red")
	kary.pensize(2)

	omar.speed(9)
	kary.speed(10)

	omar.penup()
	kary.penup()
	omar.setpos(0,-50)
	omar.pendown()
	omar.circle(50)
	kary.setpos(0,-100)
	kary.pendown()
	kary.circle(100)

	ventana.mainloop()
![ejercicio31](https://user-images.githubusercontent.com/52546998/60688371-44dc5580-9e7a-11e9-8036-38be18baca8b.PNG)

#### Ejercicio 32
	import turtle
	a=int(input('Introdizca el numero de circulos que desea:'))

	ventana = turtle.Screen ()
	ventana.bgcolor("lightgreen")
	ventana.title("Hola")

	rafael = turtle.Turtle()
	rafael.shape("turtle")
	rafael.color ("blue")
	rafael.pensize (2)

	rafael.speed(1)

	for i in range(a):
  
	  rafael.penup()
	  rafael.setpos(0,-(i*10))
	  rafael.pendown()
	  rafael.circle(i*10)
  
	ventana.mainloop()
![ejercicio32](https://user-images.githubusercontent.com/52546998/60688372-486fdc80-9e7a-11e9-9ae7-b0c7c5211a4b.PNG)

#### Ejercicio 33
	import turtle

	ventana= turtle.Screen()
	ventana.setup(500,500)
	ventana.tracer(0)
	ventana.addshape("mario2.gif")

	mario = turtle.Turtle()
	mario.speed(0)
	mario.shape("mario2.gif")

	mario.penup()
	mario.goto(-350,0)

	while True:
	    ventana.update()
	    mario.forward(0.10)
![ejercicio33](https://user-images.githubusercontent.com/52546998/60688375-4c9bfa00-9e7a-11e9-8a3d-bf830c3930dd.PNG)
    
#### Ejercicio 34
	import turtle

	window= turtle.Screen()
	window.addshape("mario2.gif")
	border= turtle.Turtle()
	border.speed(0)
	border.up()
	border.hideturtle()
	border.pensize(0)
	border.color('white')
	border.goto(300,300)
	border.down()
	border.goto(300,-300)
	border.goto(-300,-300)
	border.goto(-300,300)
	border.goto(300,300)


	camino=turtle.Turtle()
	camino.speed(20)
	camino.shape("mario2.gif")
	
	camino.up()
	dx=1
	
	while True:
	    x,y= camino.position()
	    if x+dx>=300 or x+dx<=-300:
	        dx=-dx
   
	    camino.goto(x+dx,y)

	window.mainloop()
![ejercicio34](https://user-images.githubusercontent.com/52546998/60688377-5160ae00-9e7a-11e9-9712-156d98edbe4a.PNG)

#### Ejercicio 35
	class Coche(object):
	    def __init__(self,gasolina):
	        self.gasolina = gasolina
	   
	    def arrancar(self):
	        if self.gasolina > 0:
	            print("Arranca")
	        else:
	            print("No arranca")
    
	    def conducir(self):
	        if self.gasolina > 0:
	            self.gasolina = self.gasolina - 1
	            print("Quedan", self.gasolina, "litros")
	        else:
	            print("No se mueve")
    
	vocho = Coche(5)
	tsuru = Coche(3)

	vocho.arrancar()
	vocho.conducir()
	vocho.conducir()
	vocho.conducir()
	vocho.conducir()
	vocho.conducir()
	vocho.conducir()
	tsuru.arrancar()
	tsuru.conducir() 
![ejercicio35](https://user-images.githubusercontent.com/52546998/60688378-558ccb80-9e7a-11e9-9e6c-570559703122.PNG)

#### Ejercicio 36
	class Triangulo(object):
	    def __init__(self,angulo1,angulo2,angulo3):
	        self.angulo1 = angulo1
	        self.angulo2 = angulo2
	        self.angulo3 = angulo3
        
	    def checarangulo(self):
	        if (self.angulo1+self.angulo2+self.angulo3) == 180:
	            print("Es un triangulo")
	        else:
	            print("No es un trianfulo")
            
	Mitriangulo=Triangulo(90,30,60)
	
	Mitriangulo.checarangulo()
![ejercicio36](https://user-images.githubusercontent.com/52546998/60688380-59205280-9e7a-11e9-8673-fa52244fc579.PNG)

#### Ejercicio 38
	class Cancion(object):
	    def __init__(self,letra):
	        self.letra = letra
	    
	    def cantame(self):
	        print(self.letra)

	micumpleanos=Cancion(["...que cantaba el rey David," " hoy por ser dia de tu santo," " te las cantamos a ti."])

	micumpleanos.cantame()
![ejercicio38](https://user-images.githubusercontent.com/52546998/60688385-5de50680-9e7a-11e9-95d2-fe3449f81edc.PNG)

#### Ejercicio 39
	import turtle

	ventana = turtle.Screen()
	ventana.bgcolor('blue')
	ventana.title('ventana')

	a = turtle.Turtle()
	d=50
	a.forward(d)
	a.left(90)
	a.forward(d)
	a.left(90)
	a.forward(d)
	a.left(90)
	a.forward(d)
	a.left(90)

	ventana.mainloop()
![ejercicio39](https://user-images.githubusercontent.com/52546998/60688390-62112400-9e7a-11e9-92cc-942668a5d4dc.PNG)

#### Ejercicio 40
	import turtle

	ventana=turtle.Screen()
	ventana.bgcolor('green')
	ventana.title('Funciones')

	omar = turtle.Turtle()
	d = 50

	for i in range(4):
	    omar.forward(d)
	    omar.left(90)

	ventana.mainloop()
![ejercicio40](https://user-images.githubusercontent.com/52546998/60688392-65a4ab00-9e7a-11e9-9fcf-1a25559dc8dc.PNG)

#### Ejercicio 41
	import turtle

	def dibujar_cuadro(tur, d):
	    
	    for i in range(4):
	        tur.forward(d)
	        tur.left(90)
        
	ventana=turtle.Screen()
	ventana.bgcolor('blue')
	ventana.title('funciones')

	a=turtle.Turtle()
	b=turtle.Turtle()
	dibujar_cuadro(a, 50)
	dibujar_cuadro(b, 200)

	ventana.mainloop()
![ejercicio41](https://user-images.githubusercontent.com/52546998/60688394-69d0c880-9e7a-11e9-8db8-f01b4faa98e9.PNG)

#### Ejercicio 42
	import turtle
	def dibujar_cuadro(tur,d):
	    for i in ['red','purple','hotpink','blue']:
	        tur.color(i)
	        tur.forward(d)
	        tur.left(90)

	ventana = turtle.Screen()
	ventana.bgcolor('lightgreen')
	ventana.title('funciones')

	alex= turtle.Turtle()
	jessie=turtle.Turtle()

	dibujar_cuadro(alex,50)
	dibujar_cuadro(jessie,200)
	ventana.mainloop()
![ejercicio42](https://user-images.githubusercontent.com/52546998/60688396-6d644f80-9e7a-11e9-8648-7a91579d519e.PNG)

#### Ejercicio 43

	import turtle
	
	def dibujar_multiples_cuadros(tur,d):
	    for i in ['red','purple','hotpink','blue']:
	        tur.color(i)
	        tur.forward(d)
	        tur.left(90)

	ventana = turtle.Screen()
	ventana.bgcolor('lightgreen')
	ventana.title('funciones')

	a= turtle.Turtle()
	a.pensize(3)

	d= 20
	for i in range(15):
	    dibujar_multiples_cuadros(a, d)
	    d= d + 10
	    a.forward(10)
	    a.right(18)


	ventana.mainloop()
![ejercicio43](https://user-images.githubusercontent.com/52546998/60688398-70f7d680-9e7a-11e9-86c3-1c5ff333a53e.PNG)

#### Ejercicio 44
	import turtle


	def dibujar_cuadro_seguir(tur, p):
	    for i in range(4):
	        tur.forward(20)
	        tur.left(90)
    

	ventana=turtle.Screen()
	ventana.bgcolor('red')
	ventana.title('funciones')

	alex=turtle.Turtle()
	alex.pensize(5)
	alex.speed(2)

	p=30

	for i in range(5):
	    dibujar_cuadro_seguir(alex, 5)

	    alex.penup()
	    alex.setpos(p,0)
	    alex.pendown()
	    p=p+30
    
	ventana.mainloop()
![ejercicio44](https://user-images.githubusercontent.com/52546998/60688400-7523f400-9e7a-11e9-9f9e-ce795bfc0693.PNG)

#### Ejercicio 45
	import turtle
	def dibujar (tur,d):
	    for i in range(4):
	        tur.forward(d)
	        tur.left(90)     
	ventana=turtle.Screen()
	ventana.bgcolor('blue')
	ventana.title('funciones')
	alex=turtle.Turtle()
	alex.pensize(3)
	m=-10
	for i in range(20,101,20):
	    dibujar(alex,i)
	    alex.penup()
	    alex.goto(m,m)
	    alex.pendown()
	    m=m-10 
	ventana.mainloop()
![ejercicio45](https://user-images.githubusercontent.com/52546998/60688403-78b77b00-9e7a-11e9-90f9-d0a6b8667af9.PNG)

#### Ejercicio 46
	import turtle
	def dibujar(tur, d):
    	    for i in range(8):
	        tur.forward(d)
	        tur.left(45)        
	ventana=turtle.Screen()
	ventana.bgcolor('blue')
	ventana.title('funciones')
	a=turtle.Turtle()
	dibujar(a, 50)
	ventana.mainloop()
![ejercicio46](https://user-images.githubusercontent.com/52546998/60688407-7c4b0200-9e7a-11e9-8147-0fa551670e9f.PNG)

#### Ejercicio 47
	import turtle
	def dibujar_cuadro_caracol(tur, d):
	    for i in  ['red','blue','yellow','red']:
	        tur.color(i)
	        tur.forward(d)
	        tur.left(90)
    	ventana=turtle.Screen()
	ventana.bgcolor('black')
	ventana.title('funciones')
	alex=turtle.Turtle()
	alex.pensize(2)
	alex.speed(100)
	d=100
	for i in range(20):
	    dibujar_cuadro_caracol(alex, d)    
	    alex.forward(10)
	    alex.right(18)
	    alex.setpos(0, 0)
	ventana.mainloop()
![ejercicio47](https://user-images.githubusercontent.com/52546998/60688411-80771f80-9e7a-11e9-90a2-4164b2133deb.PNG)

#### Ejercicio 48
	import turtle
	def cuadrado(tur, d):
	    for i in  range(80):   
	        tur.forward(d)
	        tur.left(90)
	        d=d+5        
	ventana=turtle.Screen()
	ventana.bgcolor('yellow')
	ventana.title('funciones')
	d=15
	alex=turtle.Turtle()
	alex.speed(10)
	cuadrado(alex, d)
	ventana.mainloop()
![ejercicio48](https://user-images.githubusercontent.com/52546998/60688413-84a33d00-9e7a-11e9-92d0-7cb63d8b3bf8.PNG)

#### Ejercicio 49
	import turtle
	def cuadrado(tur, d):
	    f=90
	    for i in  range(80): 
	        tur.forward(d)
	        tur.left(f)
	        d=d+5
	        f=f+0.02
	ventana=turtle.Screen()
	ventana.bgcolor('blue')
	ventana.title('funciones')	
	d=15
	alex=turtle.Turtle()
	alex.speed(10)	
	cuadrado(alex, d)
	ventana.mainloop()
![ejercicio49](https://user-images.githubusercontent.com/52546998/60688415-88cf5a80-9e7a-11e9-9d0c-b02a444b343f.PNG)












