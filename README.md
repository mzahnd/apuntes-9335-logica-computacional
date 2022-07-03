# Las Sagradas Escrituras de Lógica Computacional - 93.35

Apuntes de la materia Lógica Computacional (93.35) según se dictó durante
los años 2020, 2021 y el primer cuatrimestre del 2022 en el Instituto 
Tecnológico de Buenos Aires (ITBA).

## Instrucciones de compilación

El archivo principal del proyecto es `main.tex`, desde el cual se referencian
todos los demás.

### Linux
#### Terminal

Mediante
```
pdftex -file-line-error main.tex
``` 
Se obtiene un archivo `main.pdf` con el documento.

#### Vim
Si estás usando el plugin [VimTex](https://github.com/lervag/vimtex) basta con
abrir el archivo principal del proyecto y compilar el mismo. Se generará un
archivo `main.pdf` con el documento.

## Cómo colaborar

Tras clonar el repositorio y realizar las modificaciones que creas pertinentes,
asegurate de cumplir con lo siguiente antes de hacer un pull request:

- Las líneas deben ser de 79 caracteres o menos de largo (la excepción son 
URLs).
- Utilizá las cajas para teoremas, proposiciones, lemas, etc, que están 
definidas en [`main.tex`](main.tex) bajo el comentario 
`Teoremas, corolarios, lemas`.
- Utilizá los "Comandos propios" definidos en el archivo [`main.tex`](main.tex)
bajo un comentario con el mismo nombre.
- Si querés agregar notas al márgen, asegurate que, tras compilar el documento,
las mismas se vean por completo (LaTeX deja parte de ellas fuera de la página 
si son demasiado largas).

## Licencia

Todo el contenido de este repositorio fue creado por sus [AUTORES](AUTORES.md),
está basado en las clases teóricas de la materia dictadas por María Laura Noni 
y se encuentra bajo la licencia del MIT.

Ver el archivo [LICENSE.txt](LICENSE.txt) para mayor detalle.

