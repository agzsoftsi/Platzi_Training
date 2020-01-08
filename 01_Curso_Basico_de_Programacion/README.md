# �Qu� es HTML/CSS/JS?

HTML, CSS y JavaScript son los tres lenguajes que est�n en el centro de crear aplicaciones web, en este curso vamos a ense�arte principalmente JavaScript.
 
## Vemos cada uno:
 
- HTML (lenguaje de marcas de hipertexto), es el lenguaje donde se define la informaci�n o el contenido del documento, el formato de los archivos es .html
- CSS (cascading style sheets), el lenguaje donde se especifica el dise�o del documento, maneja todo lo relacionado con la parte visual, el formato de los archivos es .css
- JavaScript, el lenguaje que hace que todo sea interactivo, es realmente el lenguaje de programaci�n que nos permite crear sitios web, el formato de los archivos es .js
- El que realmente interpreta estos lenguajes es el Navegador.
- TIP: Se puede escribir CSS y JavaScript dentro de HTML, los profesionales normalmente escriben esto por separado.
- JavaScript no es Java
- Java es un lenguaje para servidores, aplicaciones de escritorio y aplicaciones Android
- JavaScript es el lenguaje de la web, servidores, robots, etc.

## Primeros pasos en el navegador con alert

- Ya tienes un navegador y un editor de texto, eso es lo �nico que requieres.
- Ve a la consola, desde ah� puedes escribir JavaScript sin tener que crear un archivo.
- Primero mostremos un mensaje, escribe:

```
alert('Hola mam�, estoy programando');

```

- Lo que has hecho es ejecutar una funci�n, estas son colecciones de c�digo que hacen algo, en JS siempre que quieres ejecutar una debes escribir par�ntesis de apertura y de cierre, las comillas delimitan un texto (string) y punto y coma (;) se utiliza para terminar la instrucci�n.

- Tambi�n, podemos crear operaciones b�sicas,
 var x = 1;
 var y = 2;
 var z = x + y;

- Hemos declarado variables, las declaramos con la palabra reservada var, el nombre, operador de asignaci�n (=) y el valor que va a tener.
- Recuerda: Todo en programaci�n tiene que ver con seguir las reglas de un lenguaje y luego crear las instrucciones que quieres para lograr los objetivos que deseas.
- TIP: En consola puedes hacer m�s grande el tama�o de la letra con Ctrl y +

## HTML, CSS, JavaScript de verdad

- Los archivos HTML funciona con etiquetas, por ejemplo

Hola mam� **ya casi aprendo**

- Todos los contenidos en HTML deber�an estar dentro de una etiqueta, y todos los archivos HTML tienen esta estructura, c�mo

```
<title>T�tulo de la p�gina</title>
```

- Contenido de la p�gina
La etiqueta que te permite escribir CSS dentro de HTML es <style>, se coloca dentro de head. La etiqueta para escribir JS dentro de HTML es <script>, se coloca antes de terminar el body.

### Recuerda:
- Los nombres de las variables tienen algunas reglas, c�mo, no pueden tener espacio, debe empezar siempre con una letra, las min�sculas y las may�sculas importan.
- Identaci�n, tienes bloques de c�digo, estos deben ir un poco a la derecha.
- Los programadores pasan 80% de su tiempo leyendo c�digo y 20% escribiendo c�digo, por esto es importante seguir buenas pr�cticas. Es importante ver las extensiones de los archivos.

## Task 0 Peso en otro planeta : 

�Cu�nto pesas en la tierra?, calculemos tu peso en otro planeta
 
- Creemos nuestro primer algoritmo que nos permita saber nuestro peso en otro planeta, luego escribamos esto en c�digo usando JavaScript.
- Recuerda:
Los t�tulos se pueden agregar con la etiquetas h1,h2,h3,h4,h5,h6

gravedad tierra = 9,8 m/s2
gravedad marte = 3,7 m/s2
gravedad jupiter= 24,8 m/s2
peso = 77 kg
regla de tres:
marte = (peso*3,7)/9,8
- Escribimos de nuevo la estructura de html.
- Declaramos variables y ecuaciones para calcular el peso en otro planeta dentro de Script.
- Escribimos el resultado del calculo en el navegador, usando dosument.write.

## Obteniendo datos del usuario
�Qu� tal si obtenemos ahora datos del usuario?
 
### Recuerda:
- La consola nos sirve para saber el estado de las variables
- Cuando tienen un valor en comillas("") es un texto
- Puedes usar la funci�n prompt para recibir datos del usuario.
- Concatenar es unir cadenas de texto a variables
- Usando prompt, se obtienen los datos del usuario.
- revisando el estado de la variable introducida en prompt, usando consola, se puede ver su valor actual, pero queda entre comillas, lo que indica que es un texto.
- Con parseInt se obtiene una variable entera.
- Con parseFloat se obtiene una variable de punto flotante.
- Ya tenemos una calculadora para el eso en marte.

## Task 1 Flujo y condicionales

�Qu� tal si ahora podemos elegir el planeta?

Creemos primero un algoritmo para resolver nuestro problema, para esto debemos aprender a usar condicionales.

Para escribir una condicional usas la palabra reservada if, puedes escribir una como

```
if (planeta == 1)
{
	// C�digo si la condici�n se cumple
}
else
{
	// C�digo si la condici�n no se cumple
}

Si quisi�ramos tener tener varias condiciones podemos escribir nuevas condiciones con la palabra reservada else if

if (planeta == 1)
{
	// C�digo si la condici�n se cumple
}
else if (planeta == 2)
{
	// C�digo si la segunda condici�n se cumple
}
else
{
	// C�digo si las condiciones no se cumplen
}
```
### Recuerda:
- El nombre de los archivos deber�an seguir las mismas reglas que los nombres de variables
- El c�digo deber�a ser f�cil de leer

## El DOM: nuestro lugar de trabajo en la web

En programaci�n existen objetos, estos son como envolturas para c�digo, el navegador tiene algunos nativos c�mo:

- navigator: El objeto que contiene las funciones del navegador, tambi�n te permite acceder tambi�n al sistema operativo como el gps, guardar datos en el disco duro, etc.
- window: El objeto que maneja cada una de las pesta�as.
- document: El objeto que contiene todo lo que vemos dentro de nuestra p�gina
 
En aplicaciones web tenemos un concepto llamado DOM (Document Object Model) es la forma en que internamente el navegador organiza todo el HTML dentro de una estructura de �rbol

### El Modelo de Objetos del Documento (DOM)
- En programaci�n existen objetos, estos son como envolturas para c�digo, el navegador tiene algunos nativos c�mo:
- navigator: El objeto que contiene las funciones del navegador, tambi�n te permite acceder tambi�n al sistema operativo como el gps, guardar datos en el disco duro, etc.
- window: El objeto que maneja cada una de las pesta�as.
- document: El objeto que contiene todo lo que vemos dentro de nuestra p�gina
- En aplicaciones web tenemos un concepto llamado DOM (Document Object Model) es la forma en que internamente el navegador organiza todo el HTML dentro de una estructura de �rbol