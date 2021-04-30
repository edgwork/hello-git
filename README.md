# Encabezados
# Encabezado H1
## Encabezado H2
### Encabezado H3
#### Encabezado H4
##### Encabezado H5
###### Encabezado H6

#
# Underlines
Underline 1
-----------
Underline 2
===========

# Formatos de Énfasis
- formato ~~tachado~~ única forma
- formato *italica* de la primera forma
- formato _italica_ de la segunda forma
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma
- Se puede usar formato *italico*, **bold** y ~~tachado~~ en el mismo parrafo

# Listas
1. Lista ordenada
2. Lista ordenada
3. Lista ordenada

- Lista desordenada
- Lista desordenada
- Lista desordenada

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imágenes
![Logo Hithub](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code Snippets
Código en JSON:
```JSON
{
    "titles": "apples",
    "count": [12000, 20000],
    "description": { "text": "...", "sensitive": false }
},
{
    "titles": "oranges",
    "count": [17500, null],
    "description": { "text": "...", "sensitive": false }
}
```
Código Java
```Java
/**
 * @author John Smith <john.smith@example.com>
*/
package l2f.gameserver.model;

public abstract strictfp class L2Char extends L2Object {
  public static final Short ERROR = 0x0001;

  public void moveTo(int x, int y, int z) {
    _ai = null;
    log("Should not be called");
    if (1 > 5) { // wtf!?
      return;
    }
  }
}
```
Código Javascript
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
Código Go
```Go
package main

import "fmt"

func main() {
    ch := make(chan float64)
    ch <- 1.0e10    // magic number
    x, ok := <- ch
    defer fmt.Println(`exitting now\`)
    go println(len("hello world!"))
    return
}
```
Yaml
```YAML
# comment
string_1: "Bar"
string_2: 'bar'
string_3: bar
inline_keys_ignored: sompath/name/file.jpg
keywords_in_yaml:
  - true
  - false
  - TRUE
  - FALSE
  - 21
  - 21.0
  - !!str 123
"quoted_key": &foobar
  bar: foo
  foo:
  "foo": bar

reference: *foobar

multiline_1: |
  Multiline
  String
multiline_2: >
  Multiline
  String
multiline_3: "
  Multiline string
  "

ansible_variables: "foo {{variable}}"

array_nested:
  - a
  - b: 1
    c: 2
  - b
  - comment
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Edgar Javier | Rivera | 123578 |
| Marijose     | Rivera | 951234 |
| Maricela     | Vera   | 753951 |
| Edgar José   | Rivera | 852741 |

# Citas
Esto es un texto refrente a una cita que pondremos debajo:
> Esto es una cita

Esto es otro texto que no se relaciona con la cita anterior
> Esto es otra cita

# Líneas Divisoras
Esto es un texto que será dividido por guiones medios

---
Esto es otro texto dividido por asteriscos

***
Esto es otro texto dividido por guiones bajos

___

# Saltos de Línea

