# Proyecto: Precios de Spotify en el mundo

En este proyecto tendrás tu primer acercamiento a transformar data en información. El objetivo principal de este proyecto es aprender a diseñar y construir una interfaz web donde podamos visualizar y manipular data con funciones como array.map, array.filter, array.reduce y forEach.

Esperamos que puedan pensar en el usuario, entender cuál es la mejor manera de visualizar la data en la web según sus necesidades.

- Duración estimada: 1 a 2 días
- Equipos: 1 estudiante (individual).
- Tópicos:
  - Métodos de arreglos (forEach, map, filter, reduce)
  - Visualización de JSON en un navegador

## Índice
* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)
* [4. Consideraciones generales](#4-consideraciones-generales)
* [5. Criterios de aceptación mínimos del proyecto](#5-criterios-de-aceptación-mínimos-del-proyecto)
* [6. Hacker edition](#6-hacker-edition)
* [7. Consideraciones técnicas](#7-consideraciones-técnicas)
* [8. Pistas, tips y lecturas complementarias](#8-pistas-tips-y-lecturas-complementarias)
* [9. Checklist](#9-checklist)

***

## 1. Preámbulo

En estos días es normal que cada vez usemos servicios en internet para escuchar música, uno de los servicios favoritos de música que hay es Spotify, para poder tener una cuenta Premium uno tiene que hacer un pago mensual. El precio de este pago es diferente de acuerdo al país donde vives.

![music and moeney](https://media.giphy.com/media/JYFqacjzw57DW/giphy.gif)

 
## 2. Resumen del proyecto

Para este proyecto crearás un producto alrededor de los distintos precios que tienen las cuentas premium de Spotify alrededor del mundo.

Como entregable final tendrás una página web que permita visualizar data de los países, los precios de cuentas premium tanto en monedas locales como en dólares. 

Además se te pide que realices operaciones sobre estos datos como ordenarlos, filtrarlos, y hacer algún cálculo agregado. Con cálculo agregado nos referimos a distintos cálculos que puedes hacer con la data para mostrar información aún más relevante para los usuarios (promedio, el valor máximo o mínimo, etc).

Puede encontrar los datos aquí:

* [Precios de Spotify](https://github.com/matiassingers/spotify-pricing/blob/master/data/countries.json). Este set nos proporciona una lista de precios del plan premium de Spotify en todos los países del mundo.

## 3. Objetivos de aprendizaje

El objetivo principal de este proyecto es que aprendas a diseñar y construir una interfaz web donde se pueda visualizar y manipular data, entendiendo lo que el usuario necesita.

Dicho en palabras sencillas, aprenderás a:
* Aplicar y profundizar todo lo que aprendiste en el proyecto anterior.
* Definir qué data y de qué forma mostrarla en el producto, basándote en tu entendimiento del usuario.
* Manipular arreglos (arrays) y objetos (objects).
* Manipular el DOM (agregar elementos dinámicamente basados en la data).
* Manejar eventos del DOM para permitir interacción con el usuario (filtrado, ordenado, ...).

## 4. Consideraciones generales

* Este proyecto se debe resolver individualmente.
* Usa la data de aquí
* Tiempo para completar el reto: 1 a 2 días.
* El proyecto será entregado subiendo tu código a GitHub (commit/push) y la interfaz será desplegada usando GitHub Pages.

## 5. Criterios de aceptación mínimos del proyecto

* Todo el planeamiento del trabajo deberá ser documentado en un repositorio único por persona en el que se presente el planning, el research, los sketches y las inspiraciones utilizadas para definir el producto.
* Además, deberás detallar en el archivo readme.
* Mostrar la data en una interfaz: puede ser un card, una tabla, una lista, etc.
* Permitir al usuario filtrar y ordenar la data por precios
* Calcular el promedio del precio que cobra Spotify por cuentas premium por continente.
* Ser responsive, es decir, debe visualizarse sin problemas desde distintos tamaños de pantallas: móviles, tablets y desktops.
* El producto deberá presentarse publicado en github pages.
## 6. Hacker edition
Las secciones llamadas Hacker Edition son opcionales. Si terminaste con todo lo anterior y te queda tiempo, intenta completarlas. Así podrás profundizar y/o ejercitar más sobre los objetivos de aprendizaje del proyecto.

Features/características extra sugeridas:

* En lugar de consumir la data estática brindada en este repositorio, puedes consumir la data de forma dinámica, cargando un archivo JSON por medio de fetch. La carpeta src/data contiene una versión .js y una .json de de cada set datos.
* Agregar a tu interfaz de usuario implementada visualizaciones gráficas como ser un mapa del mundo que muestre los precios de Spotify por país, y coloree más oscuro o más claro si el precio es más alto o más bajo. Para ello te recomendamos explorar librerías de gráficas cómo D3.js, datamaps.js, y tinycolor.js
* También puedes añadir más datos sobre los países que muestras usando la librería restcountries.eu
## 7. Consideraciones técnicas
* El diseño visual de los componentes es de libre elección.
* Pueden usar algún framework de css si así lo deciden.
## 8. Pistas, tips y lecturas complementarias

#### Desarrollo Front-end
* [Array en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array)
* [Array.map en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/map)
* [Array.filter en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/filter)
* [Array.reduce en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/reduce)
* [Array.forEach en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Array/forEach)
* [Fetch API en MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
* [json.org](https://json.org/json-es.html)

#### Herramientas
* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)
* [GitHub Pages](https://pages.github.com/)
* [Node.js](https://nodejs.org/)
* [Jest](https://jestjs.io/)

#### Lecturas adicionales
* [JavaScript — Map vs. ForEach](https://codeburst.io/javascript-map-vs-foreach-f38111822c0f)
* [NodeSchool, functional JavaScript](https://github.com/timoxley/functional-javascript-workshop)
* [Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)
* [CodeWars, list of Katas: Kata](https://www.codewars.com/kata/search/my-languages?q=&tags=Arrays&beta=false&order_by=rank_id+asc)
* [.map() vs .forEach() - DEV Community 👩‍💻👨‍💻] (https://dev.to/torianne02/map-vs-foreach-pd4)

## 9. Checklist* [ ] Usa VanillaJS.
* [ ] Pasa linter (`npm run pretest`)
* [ ] Pasa tests (`npm test`)
* [ ] Pruebas unitarias cubren un mínimo del 70% de statements, functions y
  lines y branches.
* [ ] Incluye _Definición del producto_ clara e informativa en `README.md`.
* [ ] Incluye historias de usuario en `README.md`.
* [ ] Incluye _sketch_ de la solución (prototipo de baja fidelidad) en
  `README.md`.
* [ ] Incluye _Diseño de la Interfaz de Usuario_ (prototipo de alta fidelidad)
  en `README.md`.
* [ ] Incluye el listado de problemas que detectaste a través de tests de
  usabilidad en el `README.md`.
* [ ] UI: Muestra lista y/o tabla con datos y/o indicadores.
* [ ] UI: Permite ordenar data por uno o más campos (asc y desc).
* [ ] UI: Permite filtrar data en base a una condición.
* [ ] UI: Es _responsive_.

