# Estructura de archivos app / componente Vue

Normalmente:

- app.js
- index.html
- style.css

Utilizando VueFiles (Single File Component)

- componente.vue

# Partes del VueFile

- `<template>`
	- En esta parte se añade el código html, pudiendo incluso utilizarse preprocesadores

- `<script>` 
	- En esta parte se escribe el código js, pudiendo también utilizarse Ts

- `<style>`
	- Aquí escribiremos los estilos, pudiendo utilizar distintos lenguajes 

	
# Hello.vue

![bg h:240](./assets/vuefile.png)


# Pros & Cons del VueFile

Ventajas:

- Reutilización y portabilidad
	- La reutilización se simplifica, los componentes son más portables al vivir en un sólo archivo
- Bajo acoplamiento
	- El acoplamiento se reduce, al ser el mecanismo de importación más sencillo

Inconvenientes:

- Lines per file
	- Por la naturaleza del formato, el número de líneas por archivo puede llegar a crecer mucho
- Impacto en el desarrollo
	- Mucho scroll para saltar de zona
- Extrañeza
	- Este formato puede resultar difícil para desarrolladores que vengan de otros frameworks

# Extra: Diff con Styled Components

Referencia Styled components de React (Librería Emotion)

Con los styled components lo que hacemos es un "override" de los estilos de una tag html, para utilizarlo en nuestro componente

Con los vuefile lo que hacemos es encapsular en un sólo archivo toda la funcionalidad de una app o componente Vue, incluyendo sus estilos, siendo estos todo lo ricos que queramos.
