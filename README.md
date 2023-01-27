# Curso_Basico_de_Javascript

**Curso Básico de Javascript**

<h2>Content List</h2>

- [¿Por qué Javascript?](#¿por-qué-javascript)
- [¿Qué es Javascript y Para qué Sirve?](#¿qué-es-javascript-y-para-qué-sirve)


## ¿Por qué Javascript?

Antes del 2019, para construir una página web eran necesarias tres tecnologías. El lenguaje que crea la estructura (HTML), otro que añade estilos (CSS) y un lenguaje de programación, este era JavaScript.

Por este motivo, JavaScript era la única tecnología que se utilizaba para dotar de interactividad a la página. Después del 2019, la W3C (World Wide Web Consortium) genera WebAssembly. Este es un lenguaje de programación nuevo que te permite desarrollar aplicaciones web con otros lenguajes de programación, como C++ o Python.

Sin embargo, JavaScript aún tiene una comunidad enorme de desarrolladores que fortalecen el dominio de este lenguaje. A continuación nos enfocaremos en las áreas que puedes aplicar para aprenderlo.

<h3>Desarrollo Web</h3>

Para construir aplicaciones web, existen librerías o frameworks robustos basados en JavaScript. Algunos de estos son: Angular, React o Vue.

<h3>Desarrollo de aplicaciones</h3>

Si el desarrollo web no es lo tuyo, también puedes utilizar JavaScript para construir aplicaciones nativas. React Native es un framework que te permite construir aplicaciones nativas en Android o iOS.

**Electron** es un framework que te permite construir aplicaciones de escritorio en Mac o Windows.

<h3>Backend o Internet of Things (IOT)</h3>

Node.js es un entorno de ejecución de JavaScript del lado del servidor. Este te permite manejar las solicitudes y respuestas que el navegador recibe por medio del usuario, este componente se lo conoce como Backend, mientras que todas las interacciones con el usuario se denomina Frontend.

Igualmente, puedes construir aplicaciones dedicadas al IOT (Internet of Things), que te permite **relacionar objetos cotidianos con el internet.**

## ¿Qué es Javascript y Para qué Sirve?

**JavaScript** es un lenguaje de programación dinámico que tiene la capacidad de ser utilizado en muchos dispositivos diferentes. Puede usarse en ordenadores personales, servidores web y teléfonos inteligentes. Es un lenguaje interpretado, orientado a objetos, débilmente tipado y dinámico.

Esta aplicación se emplea comúnmente para el desarrollo web front-end y más recientemente para algunos desarrollos back-end a través de frameworks como Node.Js. o Next.Js. Tiene características como la programación orientada a objetos, funciones y herencia basada en prototipos.

<h3>¿Cómo nace Javascript?</h3>

Nace con la necesidad de generar dinamismo en las páginas web y que a su vez los usuarios y las empresas pudieran interactuar unos con otros. Fue creado por Brendan Eich en 1995 y se convirtió en un estándar oficial del World Wide Web Consortium (W3C) en 1997.

<h3>¿Por qué decimos que Javascript es un lenguaje dinámico?</h3>

Corre directamente en la etapa de Runtime, sin una etapa de compilación previa. Esto permite probar nuestro código inmediatamente; pero también es lo que hace que los errores no se muestren sino hasta que se ejecuta el programa. Lo que se ve a primera vista, cuando se analiza el código, es muy probable que no sea lo que se va a obtener cuando el programa se ejecute.

JavaScript permite declarar (por ejemplo) variables cuyo valor (y tipo) solo se conocerá al momento de su ejecución en función de las condiciones dadas al momento de correrlo en un entorno real. En cambio, los lenguajes estáticos no compilarán en código ejecutable a menos que todos los valores (o tipos de valores) se conozcan por adelantado.

<h3>¿Por qué es débilmente tipado?</h3>

Porque los tipos de datos no están bien definidos en el lenguaje y permite, por ejemplo, operaciones entre numerosos y letras. Esto sucede porque el lenguaje asume tipos de datos que no necesariamente fueron los que se querían representar. Se pueden hacer operaciones entre tipos distintos de datos (enteros con strings, booleanos con enteros, etc.). Ejemplo:

```javascript
4 + "7"; // 47
4 * "7"; // 28
2 + true; // 3
false - 3; // -3
```

<h3>¿Realmente es Javascript un lenguaje interpretado?</h3>

Sí, y la razón es que el navegador lee línea por línea nuestro código, el cual le indica lo que tiene que ir haciendo, sin la necesidad de compilar. Todo esto es controlado por el motor de Javascript V8 del navegador

<h3>Qué significa que Javascript es Backwards Compatible</h3>

Todas las funciones nuevas que salen para Javascript no dañarán el trabajo ya hecho previamente, pero no se podrá utilizar en nuestro entorno de trabajo inmediatamente. Para solucionar esto está Babel, que permite usar las nuevas características del lenguaje, pero lo transforma a una versión que el navegador pueda entender.