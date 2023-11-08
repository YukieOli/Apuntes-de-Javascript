# Javascript básico 1

## Objetivos de la clase 🎯

Aprenderas los fundamentos básicos en Javascript, empezaremos por saber que son las variables, funciones, control de flujo,etc.

## Introduccón

**Javascript** se creo originalmente para serusado en el front-end de una página web.

Se trataba de dar dinamismo a las páginas que, en un principio, eran estáticas.

La introducción del motor V8 de google ha mejorado la velocidad y el funcionamiento de JS. 

En los ultimos años tomo una posición muy fuerte también del lado del servidor, a través de Node.js.
Esto hace que se pueda ahora programar tanto el front-end como el back-end solo con javascript.

#### Javascript no es igual a Java, son totalmente diferentes

---
# Variables

## ¿Qué es una variable?

Una variable es una forma de almacenar el valor de algo para usarlo más tarde.
Javascript tiene tipado **dinámico**, esto es que las variables se pueden configurar y reestablecer para cualquier tipo de dato.

Para crear una variable en javascript utiñizamos la palabra clave **var** seguida de un espacio y el nombre de la variable (con este identificador la podemos referir después)

Además de decñarar una variable, podemos asignarle un valor usando el signo **"="**

### Ejemplo:
``` javascript
var identificador = valor
var nombre = Luis
var edad = 32
var email = deidana.chan@gmail.com
```

#### Los identificadores pueden iniciar con una letra, un guión bajo o un signo de pesos ($), además de que puede contener también números.

#### JS también distingue entre mayúsculas y minúsculas para nombrar variables, así que Nombre y nombre serían dos nombres de variables DIFERENTES.

### Formas de declarar una variable
```Javascript
var nombre = 'juan'; // esta es la forma que más usaremos
let Apellido = 'Perez';
const comidafavorita = 'pizza';
```

### Se pueden crear variables con identificadores que contengan más de una palabra, usando dos diferentes formas, la *snake-case* y la *camel-case* por ejemplo:

```javascript
var nombre_de_la_mama;
var nombreDelPapa;
var NombreDelHermano; // Pascal-case no es muy usada en variables, es más para crear clases.
```
# Tipos de datos

Boolean
string
number
null
undefined

### booleano
Los booleanos tienes solo dos respuestas posibles "true" O "false"

### Strings
Cadena de texto, es toda respuesta formada por palabras y se crean con ("") o ('') 
ejemplo:
"felipe", "Andrés dijo: ' Hola a todos' "

### Number
Sin importar que un numero sea entero, flotante, decimal,negativo, etc, para javascript es un numero
5, 5,67, 3.1416, e, infinity,etc.

### undefined
(indefinido) si creamos variables sin valor asignado, el valor que toma por defecto es undefined
el **not defined** es un error de referencia, no es un tipo de dato, esto pasa cuando se quiera llamar una variable que no existe.

### null
(vacio) cuando declaramos una variable como null es por que no tiene ningun valor, hasta que se le asigna un valor especifico

### NaN
(not a number) cuando tratamos de hacer operaciones que no tienen sentido como un  5 + "hola", el 5 se transforma (castea) en string, pero solo funciona 
con sumas, cuando se trata de hacer una operación de resta entre datos distintos te marcará un **NaN**

//! Investigar el tema de la concatenación

Haciendo nuestro primer **Hola Mundo**
en javascript para imprimir por consola, usamos console.log() 
'''
console.log("hola mundo")
'''
en las extenciones de VSC buscamos "Code Runner" este permite compilar códigos de varios lenguajes de programación.

//Compilar significa que lo pone en marcha, lo ejecuta.

# Operadores aritmeticos


