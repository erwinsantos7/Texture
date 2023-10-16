---
layout: post
title:  "Post"
description: Mi primer post
date:   2019-05-23 21:03:36 +0530
categories: Javascript NodeJS
---
Codigo de hola mundo hecho en JavaSript

```javascript
const express = require('express')
const app = express()
 
app.get('/', function (req, res) {
  res.send('Hello World')
})
 
app.listen(3000)
```
 Este código CSS establece el estilo de la página web, definiendo cómo se verá el contenido dentro del elemento body, incluyendo la fuente, la altura de línea y la eliminación de márgenes, y mejora la suavidad de las fuentes en navegadores particulares.

```scss
body {
	font-family: 'Nunito Sans', sans-serif;
	line-height: 1.5em;
	margin: 0;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}
```
Eso es todo por hoy nos vemos luego
