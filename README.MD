# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de énfasis
- formato *itálica* de la primera forma.
- formato _itálica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aquí podemos usar *formato itálico*, pero también **bold** y ~~tachado~~.

# Listas
1. Esto es un ítem de lista ordenada.
2. Esto es un ítem de lista ordenada.
3. Esto es un ítem de lista ordenada.
- Esto es un ítem de lista desordenada.
- Esto es un ítem de lista desordenada.
- Esto es un ítem de lista desordenada.

# Links
- <a href="https://www.google.es">Esto es un link HTML</a>
- [Esto es un link en Markdown](https://www.google.es)
- [Esto es un link al index](index.html)

# Imágenes
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets
Código en JSON:
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
Código en Javascript:
```Javascript
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

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | Burgos | 123456 |
| Tomas | Thompson | 0909090 |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Líneas divisorias
Esto es un texto que será dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividio por guiones bajos.

___
