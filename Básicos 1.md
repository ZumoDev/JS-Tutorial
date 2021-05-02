# Tutorial para aprender JavaScript / Node.JS

## Introducción

### ¿Qué es JavaScript?
> supongo que ya lo sabes :v

--------------------------------------------

## Inicio

### Strings, Integrers y Booleans.

¿Qué es una String?
- Todo texto que este entre un " o ' se considera una string.

¿Qué es un integrer?
- Son números. Estos no llevan " o ', como en las strings.

¿Qué es un boolean?
- Son los que siempre serán "true" o "false". Estos tampoco llevan " o '.

--------------------------------------------

## Funciones

Estas son las funciones más básicas en JavaScript.

`console.log()`
- Esta función escribirá texto en la consola.

Ejemplo:

```js
console.log('Hola!')

```
> Esto lo que hará es escribir 'Hola!' en la consola.

`console.clear()`
- Esta función limpiará la consola de texto.

Ejemplo:
```js
console.log('Hola!')
console.clear()
console.log('La consola ha sido limpiada!')
```
> Esto lo que hará es escribir 'Hola!' en la consola, luego la limpiará y después escribirá 'La consola ha sido limpiada!'

--------------------------------------------

## Texto y números

Ahora que sabes como escribir texto en la consola a base de funciones, aprenderás a usar los números, como por ejemplo:
- Sumar
- Restar
- Multiplicar
- Dividir

>

### Sumar

Ejemplo:
```js
console.log(2 + 2)
```
> La consola escribirá el resultado de 2 + 2, que en este caso sería 4.

**Si se usa esta funcion entre " o ', no fucnionará!**

>

### Restar

Ejemplo:
```js
console.log(8 - 3)
```
> La consola escribirá el resultado de 8 - 3, que en este caso sería 5.

**Si se usa esta funcion entre " o ', no fucnionará!**

>

### Multiplicar

Ejemplo:
```js
console.log(3 * 5)
```
> La consola escribirá el resultado de 3 x 5, que en este caso sería 15.

**Si se usa esta funcion entre " o ', no fucnionará!**


### Dividir

Ejemplo:
```js
console.log(15 / 3)
```
> La consola escribirá el resultado de 15 entre 3, que en este caso sería 5.

**Si se usa esta funcion entre " o ', no fucnionará!**

---

## Variables

**¿Que es una variable?**
- Una variable es como una caja para guardar cosas. Las variables pueden guardar textos, números, etc.

### Como usar variables:

```js
var nombre = 'valor'
```

#### Decode:
- `var` es la declaración de la variable.
- `nombre` es el nombre de la variable.
- `valor` es el valor de la variable.

Ejemplos:
```js
var nombre = 'Pepito'
var edad = 16
var esFeo = false
```

---

### Usos de las variables

Una forma de usarlas es usando `console.log()`.

Ejemplo:
```js
var nombre = 'Pepito'
console.log(nombre)
```

**Decode:**
- `var` esta declarando que `nombre` es una variable y su valor es `Pepito`.
- `console.log(nombre)` escrbirá `Pepito` en la consola

Una forma de editar el valor de las variabes es este:
```js
var numero = 10
console.log(numero)
numero = numero + 1
console.log(numero)
```

**Decode:**
- Cuando `numero` sea declarado, se escribirá en la consola "10"
- Después, el valor de `numer` será "11", y se escribirá en la consola "11"

Para juntar strings y cantidades se puede hacer esto:
```js
var edad = 13
console.log('Pepito tiene ' + edad + 'años!')
```

**O**

```js
var edad = 13
console.log(`Pepito tiene ${edad} años!`)
```

### OJO
- **Al usar variables, no uses los " o '!**

---
## Ejercicio

1. Crea un código que:
- Cree una variable con el nombre de "cantidad" y que su valor sea "0".
- Haz que se escriba en la consola `"La cantidad es" + cantidad`
- Luego cambiar la edad al número que sea y que se escriba la nueva cantidad.
- Enviarme el código por MD

Ejemplo:
```js
var cantidad = 0
console.log(`La cantidad es ${cantidad}`)

cantidad = cantidad + 14
console.log('La nueva cantidad es ' + cantidad + ' !')
```

`Próximamente parte 2: Checar si un valor es verdadero o falso, y más tipos de variables!`
