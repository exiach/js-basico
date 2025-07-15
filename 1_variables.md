
# 🧠 Variables en JavaScript

## Ver videos: 
[lista de videos para una mejor comprension de Variables](https://www.youtube.com/watch?v=cf1UFRukxA8&list=PLGSnz-ERqn7jWF1kPjiCQUOakNx8WxIBR)


## ¿Qué es una variable?
Una **variable** es como una **caja con un nombre** que usamos para **guardar datos**. Podemos poner un valor dentro de ella (por ejemplo, un número, un texto o un valor lógico) y usar ese valor más adelante.

### 📦 En JavaScript, usamos `let`, `const` y `var` para declarar variables:
- `let`: Variable que **puede cambiar** su valor.
- `const`: Variable que **no puede cambiar** su valor (es constante).
- `var`: Se usaba antes de `let`, hoy casi no se recomienda (por temas de alcance).

## ✅ Ejemplo en JavaScript

```javascript
let nombre = "Daniel";
const edad = 30;

console.log("Hola, mi nombre es " + nombre + " y tengo " + edad + " años.");
```

### Explicación:
- `nombre` es una variable con el texto `"Daniel"`.
- `edad` es una constante con el número `30`.
- `console.log()` muestra el mensaje combinando texto y variables.

---

# 📚 Actividades y ejercicios prácticos

## 📝 Ejercicio 1: Declarar y mostrar
**Instrucción:** Declara una variable `ciudad` con el valor `"Cochabamba"` y muéstrala en consola.

```javascript
// Tu código aquí
```

**Solución esperada:**
```javascript
let ciudad = "Cochabamba";
console.log(ciudad);
```

---

## 📝 Ejercicio 2: Modificar una variable
**Instrucción:** Declara una variable `puntos` con valor `10`, luego súmale 5 y muestra el resultado.

```javascript
// Tu código aquí
```

**Solución esperada:**
```javascript
let puntos = 10;
puntos = puntos + 5;
console.log(puntos); // 15
```

---

## 📝 Ejercicio 3: Diferencia entre `let` y `const`
**Instrucción:** Declara una variable con `const` llamada `pais` con valor `"Bolivia"`, luego intenta cambiar su valor a `"Perú"`.

```javascript
// Tu código aquí
```

**Resultado esperado:**
```javascript
const pais = "Bolivia";
pais = "Perú"; // ❌ Error: Assignment to constant variable
```

---

## 📝 Ejercicio 4: Combinar variables en un mensaje
**Instrucción:** Declara una variable `nombre` y otra `edad`, y muestra este mensaje en consola:
> "Me llamo Juan y tengo 25 años."  
Pero usando las variables.

```javascript
// Tu código aquí
```

**Solución esperada:**
```javascript
let nombre = "Juan";
let edad = 25;

console.log("Me llamo " + nombre + " y tengo " + edad + " años.");
```

---

# 🧪 BONUS: Prueba rápida para saber si entendiste

**Preguntas:**
1. ¿Cuál es la diferencia entre `let` y `const`?
2. ¿Qué error aparece si intentas cambiar el valor de una variable declarada con `const`?
3. ¿Qué muestra este código?

```javascript
let x = 3;
x = x + 7;
console.log(x);
```
