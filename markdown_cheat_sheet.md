Esta es una referencia rápida y una muestra. Para obtener información más completa, consulta la [especificación original de John Gruber](https://daringfireball.net/projects/markdown/) 
y la página de [información sobre Markdown con estilo de GitHub](https://docs.github.com/en/get-started/writing-on-github).

También puedes explorar más [herramientas para Markdown](https://github.com/mundimark/awesome-markdown).

# Tabla de Contenidos

- [Encabezados](#encabezados)
- [Énfasis](#énfasis)
- [Listas](#listas)
- [Enlaces](#enlaces)
- [Imágenes](#imágenes)
- [Resaltado de Código y Sintaxis](#resaltado-de-código-y-sintaxis)
- [Notas al Pie](#notas-al-pie)
- [Tablas](#tablas)
- [Citas en Bloque](#citas-en-bloque)
- [Línea Horizontal](#línea-horizontal)
- [Salto de Línea](#salto-de-línea)
- [Videos de YouTube](#videos-de-youtube)

# Encabezados
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternativamente, para los encabezados H1 y H2, un estilo de subrayado:

Alt-H1
======

Alt-H2
------
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternativamente, para los encabezados H1 y H2, una clase de subrayado:

Alt-H1
======

Alt-H2
------

# Énfasis
```
Énfasis, también conocido como cursiva, con *asteriscos* o _guiones bajos_.

Énfasis fuerte, también conocido como negrita, con **asteriscos** o __guiones bajos__.

Énfasis combinado con **asteriscos y _guiones bajos_**.

El tachado usa dos tildes. ~~Tacha esto~~.

```

Cursiva, con *asteriscos* o _guiones bajos_.

Negrita, con **asteriscos** o __guiones bajos__.

Énfasis combinado con **asteriscos y _guiones bajos_**.

El tachado usa dos tildes. ~~Tacha esto~~.

# Listas
En este ejemplo, los espacios al inicio y al final se muestran con puntos: ⋅)
```
1. Primer elemento de lista ordenada
2. Otro elemento
⋅⋅* Sub-lista sin ordenar
1. Los números reales no importan, solo que sea un número
⋅⋅⋅1. Sub-lista ordenada
4. Y otro elemento
⋅⋅⋅Puedes tener párrafos con sangría adecuada dentro de los elementos de la lista. Observa la línea en blanco arriba y los espacios iniciales (al menos uno, pero usaremos tres aquí para alinear el Markdown sin procesar).

⋅⋅⋅Para tener un salto de línea sin un párrafo, necesitarás usar dos espacios al final.⋅⋅
⋅⋅⋅Nota que esta línea está separada, pero dentro del mismo párrafo.⋅⋅
⋅⋅⋅(Esto es contrario al comportamiento típico de GFM, donde los espacios finales no son necesarios).

* La lista sin ordenar puede usar asteriscos
- O guiones
+ O signos de más
```
1. Primer elemento de lista ordenada
2. Otro elemento
   
    * Sub-lista sin ordenar
    * Sub-lista sin ordenar2
1. Los números reales no importan, solo que sea un número
   
    1. Sub-lista ordenada
    2. Sub-lista ordenada2

3. Y otro elemento
  Puedes tener párrafos con sangría adecuada dentro de los elementos de la lista. Observa la línea en blanco arriba y los espacios iniciales (al menos uno, pero usaremos tres aquí para alinear el Markdown sin procesar).

   Para tener un salto de línea sin un párrafo, necesitarás usar dos espacios al final.⋅⋅
   Nota que esta línea está separada, pero dentro del mismo párrafo.⋅⋅
   (Esto es contrario al comportamiento típico de GFM, donde los espacios finales no son necesarios).

* La lista sin ordenar puede usar asteriscos
- O guiones
+ O signos de más

# Enlaces
```
[Soy un enlace en línea](https://www.google.com)

[Soy un enlace con título](https://www.google.com "Página principal de Google")

[Soy un enlace de referencia][Texto de referencia no sensible a mayúsculas o minúsculas]

[Soy una referencia relativa a un archivo del repositorio](libro_tyr.csv)

[Puedes usar números para las definiciones de enlaces de referencia][1]

O dejarlo en blanco y usar el [mismo texto del enlace].

Las URL y las URL entre paréntesis angulares se convierten automáticamente en enlaces.
http://www.example.com o <http://www.example.com> y a veces 
example.com (pero no en GitHub, por ejemplo).

Un poco de texto para mostrar que los enlaces de referencia pueden ir al final.

[texto de referencia no sensible a mayúsculas o minúsculas]: https://www.mozilla.org  
[1]: http://slashdot.org  
[mismo texto del enlace]: http://www.reddit.com
```
[Soy un enlace en línea](https://www.google.com)

[Soy un enlace con título](https://www.google.com "Página principal de Google")

[Soy un enlace de referencia][Texto de referencia no sensible a mayúsculas o minúsculas]

[Soy una referencia relativa a un archivo del repositorio](libro_tyr.csv)

[Puedes usar números para las definiciones de enlaces de referencia][1]

O dejarlo en blanco y usar el [mismo texto del enlace].

Las URL y las URL entre paréntesis angulares se convierten automáticamente en enlaces.
http://www.example.com o <http://www.example.com> y a veces 
example.com (pero no en GitHub, por ejemplo).

Un poco de texto para mostrar que los enlaces de referencia pueden ir al final.

[texto de referencia no sensible a mayúsculas o minúsculas]: https://www.mozilla.org  
[1]: http://slashdot.org  
[mismo texto del enlace]: http://www.reddit.com

# Imágenes
```
Aquí está nuestro logo (pasa el cursor para ver el texto del título):

Estilo en línea: 
![texto alternativo](https://github.com/AndreiGatoCB/repo_curso_git_github/blob/main/Logo.png "Logo Title Text 1")

Estilo de referencia: 
![texto alternativo][logo]

[logo]: https://github.com/AndreiGatoCB/repo_curso_git_github/blob/main/Logo_blanco.png "Logo Title Text 2"
```
Aquí está nuestro logo (pasa el cursor para ver el texto del título):

Estilo en línea: 
![texto alternativo](https://github.com/AndreiGatoCB/repo_curso_git_github/blob/main/Logo.png "Logo Title Text 1")

Estilo de referencia: 
![texto alternativo][logo]

Estilo de referencia: 
![texto alternativo][logo github]

[logo github]: https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png "logo de github"
[logo]: https://github.com/AndreiGatoCB/repo_curso_git_github/blob/main/Logo_blanco.png "Logo Title Text 2"

# Resaltado de Código y Sintaxis
```
El código en línea se escribe con `acentos graves alrededor`.
```
El código en línea se escribe con `acentos graves alrededor`.

Blocks of code are either fenced by lines with three back-ticks ` ``` `, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.

```
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
\```
 
```python
s = "Python syntax highlighting"
print s
\```
 
\```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
\```
```

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print(s)
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

# Notas al Pie
Las notas al pie no son parte de la especificación principal de Markdown, pero son compatibles con GFM.

```
Aquí hay una nota al pie simple[^1].

Una nota al pie también puede tener varias líneas[^2].  

También puedes usar palabras para ajustarte más a tu estilo de escritura[^note].

[^1]: Mi referencia.
[^2]: Cada nueva línea debe ir precedida de 2 espacios.  
  Esto permite tener una nota al pie con múltiples líneas.
[^note]:
    Las notas al pie nombradas seguirán renderizándose con números en lugar del texto, pero permiten una identificación y vinculación más fácil.
    Esta nota al pie también se ha hecho con una sintaxis diferente usando 4 espacios para las nuevas líneas.
```
Aquí hay una nota al pie simple[^1].

Una nota al pie también puede tener varias líneas[^2].  

También puedes usar palabras para ajustarte más a tu estilo de escritura[^note].

[^1]: Mi referencia.
[^2]: Cada nueva línea debe ir precedida de 2 espacios.  
  Esto permite tener una nota al pie con múltiples líneas.
[^note]:
    Las notas al pie nombradas seguirán renderizándose con números en lugar del texto, pero permiten una identificación y vinculación más fácil.
    Esta nota al pie también se ha hecho con una sintaxis diferente usando 4 espacios para las nuevas líneas.

# Tablas
Las tablas no son parte de la especificación básica de Markdown, pero son parte de GFM y Markdown Here las soporta. Son una forma fácil de agregar 
tablas a tu correo electrónico, una tarea que de otro modo requeriría copiar y pegar desde otra aplicación.
Los dos puntos se pueden usar para alinear columnas.
```
| Tablas      |	Son	              | Geniales |
|-------------|:---------------------:|:--------:|
|la col 3 e	  | alineada a la derecha | $1600    |
|la col 2 es  | centrada	           | $12      |
|las rayas de | cebra	son geniales  | $1       |
```

| Tablas      |	Son	                  | Geniales |
|-------------|:---------------------:|:--------:|
|la col 3 es	| alineada a la derecha	| $1600    |
|la col 2 es	| centrada	            | $12      |
|las rayas de | cebra	son geniales    | $1       |

Deben haber al menos 3 guiones separando cada celda del encabezado. Las tuberías exteriores (|) son opcionales, y no es necesario que la línea de 
Markdown en bruto se alinee de manera ordenada. También puedes usar Markdown en línea.
```
Markdown | Menos | Bonito
--- | --- | ---
*Todavía* |	`se renderiza` | **muy bien**
1 |	2 |	3
```
Markdown | Menos | Bonito
--- | --- | ---
*Todavía* |	`se renderiza` | **muy bien**
1 |	2 |	3

# Citas en Bloque
```
> Las citas en bloque son muy útiles en el correo electrónico para emular texto de respuesta.
> Esta línea es parte de la misma cita.

Ruptura de la cita.

> Esta es una línea muy larga que aún se citará correctamente cuando se ajuste. Oh, vamos a seguir escribiendo para asegurarnos de que sea lo suficientemente larga como para ajustarse para todos. Oh, puedes poner Markdown dentro de una cita en bloque.
```
> Las citas en bloque son muy útiles en el correo electrónico para emular texto de respuesta.
> Esta línea es parte de la misma cita.

Ruptura de la cita.

> Esta es una línea muy larga que aún se citará correctamente cuando se ajuste. Oh, vamos a seguir escribiendo para asegurarnos de que sea lo suficientemente larga como para ajustarse para todos. Oh, puedes poner Markdown dentro de una cita en bloque.

# Línea Horizontal
```
Tres o más...

---

Guiones

***

Asteriscos

___

Guiones bajos
```
Tres o más...

---

Guiones

***

Asteriscos

___

Guiones bajos

# Salto de Línea
Mi recomendación básica para aprender cómo funcionan los saltos de línea es experimentar y descubrir: 
presiona <Enter> una vez (es decir, inserta un salto de línea), luego presiona dos veces (es decir, inserta dos saltos de línea) y observa qué sucede. 
Pronto aprenderás a obtener lo que deseas. "Markdown Toggle" es tu amigo.

Aquí hay algunas cosas para probar:
```
Aquí hay una línea para que comencemos.

Esta línea está separada de la anterior por dos saltos de línea, por lo que será un párrafo separado.

Esta línea también es un párrafo separado, pero...
Esta línea solo está separada por un único salto de línea, así que es una línea separada en el mismo párrafo.
```
Aquí hay una línea para que comencemos.

Esta línea está separada de la anterior por dos saltos de línea, por lo que será un párrafo separado.

Esta línea también es un párrafo separado, pero 
Esta línea solo está separada por un único salto de línea, así que es una línea separada en el mismo párrafo.

# Colaboradores
@AndreiGatoCB
