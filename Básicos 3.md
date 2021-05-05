# Tutorial para aprender JavaScript / Node.js (Parte 3)
hoal

### Lo que vas a ver en este tutorial:
- Loops (Repeticiones de código)
- Funciones personalizadas
- Prototypes (o asi les llamo yo xd)

---

## Loops (Repeticiones de código)

Cuando queremos repetir algo, siempre lo hacemos de la misma manera, y en JavaScript sería:
```js
console.log('hola')
console.log('hola')
console.log('hola')
console.log('hola')
console.log('hola')
console.log('hola')
console.log('hola')
console.log('hola')
```
**PERO**
- Para hacer esto en JavaScript, es una manera más simple:
```js
for (let i = 0;i <= 8;i++) {
  console.log('hola')
}
```
> Esto escribirá 8 veces 'hola' en la consola

**Decode:**
- Dentro de `for` estamos declarando una variable **local** (`let`) con el valor de `i` (que es el mas común).
- El `i <= 8` está checando que la variable `i` sea **igual o menor a** 8.
- el `i++` aumentará el valor de `i` una ves por cada ves que se repita.

**A estos loops se les llaman `for loops`!**

### Tambien podemos encontrar otro tipo de `for loops`:

```js
const uwu = 'hola' 

for (var e of uwu) {
  console.log('uwu')
}
```
> Esto escribirá uwu 4 veces, que es la lengitud de el valor de la variable `uwu` (que en este caso sería 'hola')

**Y**

```js
const uwu = 'hola'
for (var e of uwu) {
  console.log(e)
}
```
> Esto escribirá las letras de el valor de la variable 'hola', ya que estamos pidiendo a la función de `loop` que pege los elementos de la variable.

**Decode:**
- Dentro de `for` se declara una variable, donde se guarda los elementos de la variable después de `of` (que en este caso sería `uwu`)
- dentro de los {}, se escribe 'uwu' 4 veces / las letras de el valor de la variable.

Capturas de pantalla:
1er ejemplo: https://cdn.discordapp.com/attachments/786686918644465674/838897510978027520/Screen_Shot_2021-05-03_at_16.58.58.png
2do ejemplo: https://cdn.discordapp.com/attachments/786686918644465674/838897589943664640/Screen_Shot_2021-05-03_at_16.59.24.png

### Otro tipo de loop
#### Este tipo de loop, es un poco más simple que los ´for loops´

Ejemplo:
```js
let owo = 0

while (owo > 15) {
  console.log(owo)
  owo = owo + 1
}
```
> Esto escribirá en la consola el valor de `owo` cada que el loop se repita

---

## Funciones personalizadas

Las funciones personalizadas son útiles en cuando a disminuir el código usado.

- Ejemplo de función personalizada:
```js
function miFuncion() {
  console.log('Hola!')
}

miFuncion()
```
**Decode:**
- `function` declara una nueva función con el nombre de `miFuncion`.
- Dentro de los {}, se escribe lo que hará esta función personalizada.
- Después, `miFuncion()` ejecuta la función personalizada.

### Argumentos

**¿Que es un argumento?**
- Son llamadas extra a funciones. Por ejemplo, `console.log()`, que trae argumentos dentro de los (), que serían strings, integrers, booleans, variables, etc.

#### Nota:
- **Podemos usar argumentos dentro de funciones personalizadas, pero estas tendrán que ser rellenadas al momento de que esa función se use. Ejemplo:**

```js
function escribir(texto) {
  console.log(texto)
}

escribir('hola')
```
**Decode:**
- Se declara la función `escribir` con los argumentos `texto`.
- La función ejecutará el código `console.log()` cuando la función sea ejecutada.
- Se llama a la función en `escribir('hola')`

> `function () {}` es básicamente reemplazar código en una pequeña función.
> Pd: Tambíen puedes hacer funciones con más de 2 argumentos. Ejemplo: `function saludar(destinatario, saludo) {}`

---

## Prototypes / funciones de puntito xdxdxd

**¿Qué es un prototype?**
- Son las funciones que terminan en un **.**

Ejemplo:
```js
var texto = 'hola, soy pepito, al que le gusta el pepino :D kasdjasjd xd' 

if (texto.includes('hola')) {
  console.log('el texto si incluye la palabra "hola"!')
} else {
  console.log('el texto no incluye la palabra "hola"!')
}
```
**Decode:**
- Se declara la variable texto con el valor de bla bla bla me da flojera escribir xd.
- se usa un `if` para checar **si el texto incluye la palabra "hola"**.
- Lo que hará el `.includes()` es reemplasarse a si mismo por un boolean, checando si la variable `texto` incluye la palabra `hola`.
- Si es `true`, se pegará el texto `el texto si incluye la palabra "hola"!`. Si es `false`, se pegará el texto `el texto no incluye la palabra "hola"!`.

Esta explicación debería ser más que suficiente para usar el prototype más basico del planeta tierra.

---

## Ejercicio

Tendrás que:
- crear una variable con el valor de `0`.
- Crear una función personalizada, con los argumentos `num1, num2`.
- Esa función tendrá que sumar los 2 argumentos.
- Crea un `for loop` que se detenga después de 7 repeticiones.
- crea 2 variables locales: una con el valor de `5` y la otra con el valor de `10`.
- Usar las 2 nuevas variables como argumentos en tu función personalizada.
- sumar esas 2 variables por 1 cada repetición.

Ejemplo:
```js
const cantidad = 0

function sumar(num1, num2) {
  console.log(num1 + num2)
}

for (let i = 0; i <= 5;i++) {
  let num = 5
  let numero = 10
  sumar(numero, num)
  num++
  numero++
}
```

**Si tienes dudas, mandame un MD!**
