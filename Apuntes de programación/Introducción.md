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
var nombre_de_la_mama
var nombreDelPapa
```
