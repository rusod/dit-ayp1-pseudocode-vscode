# Ayp1 # Pseudocode

Esta es una extensión para escribir seudcódigo como lo hacemos en la Facultad de Ingeniería - Universidad Nacional de la Patagonia.
Asignatura Alogorítmica y Programación 1

## Features

### Syntax Highlighting

The following items have syntax highlighting. Synonyms are separated by spaces.

#### Palabras claves reconocidas:
```
Si 
sino
Fin si
Fin mientras
Fin desde
Fin repetir
hasta
mientras
repetir
veces
desde
con paso
hasta
hacer
entonces
segun
Fin Funcion
Fin Procedimiento
Procedimiento
Funcion
Inicio
Fin
Variables
Var
constantes
Const
registro
arreglo
archivo
de
Algoritmo
tipos
```
#### Operadores lógicos:
```
y
o
no
en
				
```
#### Subalgoritmos:
```
funcion
procedimiento
```
#### Tipos simples:
``` 
entero
real
logico
cadena
caracter
```

#### Tipos estructorados:
```
arreglo
registro
archivo
```
#### Primiticas predefinidos:
```
mostrar
ingresar
div
mod
siguiente |sig
|anterior|ant
abs
redondear
trunc
rc
seno|coseno|tg
ln|exp
longitud|long
concatena
subcadena)
```
### Snippets
![Snippets](images/snippets.gif)

## Known Bugs

- do end autocloses in variables

## Release Notes

### 1.2.0

- Added template strings (e.g. `"Hi ${user.name}"`)

### 1.1.0

- Added structs
- Added `struct` and `structdo` snippets

### 1.0.3

- Fixed bug where do end would be autoclose in strings and comments

### 1.0.2

- Fixed bug which prevented comments in functions and procedures

### 1.0.1

- Minor changes to extension information

### 1.0.0

- Initial release with syntax highlighting and snippets for basic statements and definitions.


# Créditos

Basda en la extensión original

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/willumz.generic-pseudocode)](https://marketplace.visualstudio.com/items?itemName=willumz.generic-pseudocode)
<!-- [![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/willumz.generic-pseudocode)](https://marketplace.visualstudio.com/items?itemName=willumz.generic-pseudocode) -->

A simple extension for syntax highlighting of generic pseudocode.

Syntax highlighting exists for multiple variants of common pseudocode keywords, allowing you to use your own style and not confining you to a specific format.
