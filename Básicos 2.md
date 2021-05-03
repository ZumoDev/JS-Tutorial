# Tutorial para aprender JavaScript / Node.js (Parte 2)

## Inicio

### `if` Statements

¿Qué es un `if` statement?
- Los `if`s sirven para checar si una cosa es igual / no es igual / mayor / menor a otra y ejecutar una parte de código. Son los que más frecuentemente se usan.

¿Cómo se usa un `if` statement?
```js
if (valor1 === valor2) {codigo a usar}
```

Ejemplo de uso:
```js
var esFeo = false

if (esFeo === false) {
  console.log('No es feo!')
 }
 ```

**Decode:**

- Se declara una variable llamada `esFeo` con el valor `false` (falso).
- `if` checará si el valor de la variable `esFeo` es igual a `false`. Si es verdad, la consola escribirá 'No es feo!'.

---

### Otros tipos de `if`s

- `if`, el cláisco
- `else if`, para checar más valores si el valor anterior es `false`
- `else`, si ninguno de los valores es `true`

Ejemplos de uso:
```js
var esFeo = false

if (esFeo === false) {
  console.log('No es feo!')
 } else if (esFeo === true) {
   console.log('Es feo!')
} else {
  console.log('No se pudo saber si es feo o no :/')
}
```

**Decode:**
- Se declara la variable `esFeo` con el valor de `false`.
- Se revisa si `esFeo` es `false`. Si es verdad, se escribirá 'No es feo!', si es `true`, se escribirá 'Es feo!', 
- y si no es ninguno de esos dos, entonces se escribirá 'No se pudo saber si es feo o no :/'

**Para más dudas, mandame un mensaje por MD!**

### Checkers para `if`s

Ejemplos:
```js
if ('hola' === 'hola' && 1 === 1) {
  console.log('si')
}
```
> Esto checará si 'hola' es lo mismo que 'hola' y si 1 es lo mismo que 1.

```js
if ('hola' === 'hola' || 1 === 1) {
  console.log('si')
}
```
> Esto checará si 'hola' es lo mismo que 'hola' **O** si 1 es lo mismo que 1.

```js
if ('hola' !== 'hola') {
  console.log('no')
}
```
> Esto checará si 'hola' **no es lo mismo que** 'hola'.

**Para más dudas, mandame un mensaje por MD!**

---

### Más tipos de variables

Ejemplos
```js
let texto = 'hola'
const numero = 16
```

- `let` es una declaración de variable **local**, es decir, solo se puede usar en una parte de código.
Ejemplo

```js
function sumar() {
  let num1prompt = prompt('Número 1 a sumar ')
  let num2prompt = prompt('Número 2 a sumar ')
  
  console.log(num1prompt + num2prompt)
}
sumar()
```
> luego veremos eso de function jaja q presumido soy xdXDxd

- `const` es lo mismo a `var` pero es mas *elegante* xdxdxd
Ejemplo
```js
const uwu = 'hola'

if (uwu.includes(e)) {console.log('si')}
else {console.log('no')}
```

---

### MOMENTO PANAAAA WEEEE WOOOO WEEEEE WOOO OWEEEUEHWFIOUEWHUFWEIMFP

En esta parte pues, vas a aprender mas cosas de las que venian en el coso del utorial pasado jasdjasjdj xddxdxdxd

#### COMO:

- nada ajajajajjaj troleado

---

### Ejercicio

**Tendrás que:**
- Crear una variable llamada `numero` con el valor de `0` y otra variable llamada `numeroEnTexto` con el valor de `cero`
- Checar si: la variable `numero` es `0` **y** la variable `numeroEnTexto` es `cero`. Si es así, entonces tendrás que escribir en la consola un texto de que si es correcto
- y cambiar el valor de `numero` a `1` y `numeroEnTexto` a `uno`
- Si no, entonces tendrás que escribir un texto de que no es igual.

Ejemplo (no copies wn xd):
```js
const numero = 0
const numeroEnTexto = 'cero'

if (numero !== 1 && numeroEnTexto !== 1) {
  console.log('si')
} else {
  console.log('no')
}
```

arigato for ver este coso xdxdxd
