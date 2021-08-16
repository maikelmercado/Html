# markdown
# cabeceras h1
## cabeceras h2
### cabeceras h3
#### cabeceras h4
##### cabeceras h5
###### cabeceras h6

Underline 1 : sirve como titulo
------------
Underline 2
=============

### Emphasis
 - letra *italica* de la primera forma.
 - letra _italica_ de la segunda froma.
 - formato  **bold ostrong**
 - formato ~~tachado~~. formato normal
 - aqui podemos uisar *fromato italico* pero tambien bold

### listas
 1- listas ordenadas 
 2- listas ordenadas 
 3- listas ordenadas 


### Links

- <a href="http://google.com"> Este es un link HTMl </a>
- [este es un link de Markdown](http://www.google.com)
- [Esto es un link index](index.html)

### Imagenes
![Logo Github](https://cdn.worldvectorlogo.com/logos/github-icon.svg)

### Code Snippets
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

#### Codigo JavaScript
```JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
***
### Tablas
| Nombre | Apellido | Documento |
|------- | -------- | ----------|
 Nombre | Apellido | Documento |
  Nombre | Apellido | Documento |
   Nombre | Apellido | Documento |

***

### Citas
 Esto es un texto que hace referente a una cita:
 > Esto es una cita.
 ***

 ### Lineas Divisoras

 Este es un texto que se a divido
 
 ---

 ### Saltos de lineas

 Este es el primer parrafo.
 
 Este es el segundo parrrafo