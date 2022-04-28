# Session 13 - 26.04.2022

# frontAgain

difficulty:
  - newbie
OAs:
  - strings
projects:
  - card-validation
  - cipher


[https://the-winter.github.io/codingjs/exercise.html?name=frontAgain&title=String-1](https://the-winter.github.io/codingjs/exercise.html?name=frontAgain&title=String-1)

Dada un string, devuelve true si los 2 primeros caracteres
también aparecen al final, como en el caso de "edited".

__Ejemplo__

```js
  frontAgain('edited') → true
  frontAgain('edit') → false
  frontAgain('ed') → true
```

# maxMod5


difficulty:
  - newbie
OAs:
  - conditionals
projects:
  - cipher
  - card validation


[https://the-winter.github.io/codingjs/exercise.html?name=maxMod5&title=Logic-1](https://the-winter.github.io/codingjs/exercise.html?name=maxMod5&title=Logic-1)

Dados dos valores int, devuelve el que sea mayor. Sin embargo,
si los dos valores tienen el mismo residuo cuando se dividen
por 5, entonces se devuelve el valor más pequeño. Sin embargo,
en todos los casos, si los dos valores son iguales, devuelve 0.
Nota: el operador % "mod" calcula el residuo, por ejemplo, 7 % 5 es 2.

__Ejemplo:__

```js
    maxMod5(2, 3) → 3
    maxMod5(6, 2) → 6
    maxMod5(3, 2) → 3
```
