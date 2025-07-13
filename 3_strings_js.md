
# 📚 Strings en JavaScript

## 🧠 ¿Qué es un string?
Un **string** es una cadena de texto, es decir, una secuencia de caracteres encerrados entre comillas.

```javascript
let saludo = "Hola mundo";
let nombre = 'Daniel';
let frase = `Hola, mi nombre es ${nombre}`; // Template string
```

Puedes usar **comillas dobles (" "), simples (' ')** o **template literals (` `)**.

---

## 🔧 Métodos comunes de los strings

### 1. `.length`
Devuelve la longitud (cantidad de caracteres) del string.
```javascript
let texto = "JavaScript";
console.log(texto.length); // 10
```

### 2. `.toUpperCase()` y `.toLowerCase()`
Convierte todo el texto a mayúsculas o minúsculas.
```javascript
let mensaje = "Hola";
console.log(mensaje.toUpperCase()); // "HOLA"
console.log(mensaje.toLowerCase()); // "hola"
```

### 3. `.includes()`
Verifica si una cadena contiene otra.
```javascript
let frase = "Bienvenido a la clase";
console.log(frase.includes("clase")); // true
```

### 4. `.indexOf()`
Devuelve el índice donde comienza una subcadena (o -1 si no está).
```javascript
let nombre = "Daniel";
console.log(nombre.indexOf("n")); // 2
```

### 5. `.slice()`
Extrae una parte del string.
```javascript
let palabra = "Programación";
console.log(palabra.slice(0, 5)); // "Progr"
```

### 6. `.replace()`
Reemplaza parte del texto por otro.
```javascript
let texto = "Hola mundo";
console.log(texto.replace("mundo", "Daniel")); // "Hola Daniel"
```

### 7. `.trim()`
Elimina los espacios al inicio y al final.
```javascript
let entrada = "   Hola   ";
console.log(entrada.trim()); // "Hola"
```

---

# 🧪 Ejercicios guiados

### 📝 Ejercicio 1: Saludo personalizado
**Instrucción:** Crea una variable `nombre` y usa un template string para decir: `"Hola, me llamo Daniel"`.

```javascript
let nombre = "Daniel";
let saludo = `Hola, me llamo ${nombre}`;
console.log(saludo);
```

---

### 📝 Ejercicio 2: Longitud de un mensaje
**Instrucción:** Crea una variable con un mensaje y muestra cuántos caracteres tiene.

```javascript
let mensaje = "Estoy aprendiendo JavaScript";
console.log(mensaje.length);
```

---

### 📝 Ejercicio 3: Todo en mayúsculas
**Instrucción:** Convierte a mayúsculas la frase `"aprendiendo con ejemplos"`.

```javascript
let frase = "aprendiendo con ejemplos";
console.log(frase.toUpperCase());
```

---

### 📝 Ejercicio 4: ¿Contiene una palabra?
**Instrucción:** Verifica si el texto `"Curso de JavaScript"` incluye la palabra `"Java"`.

```javascript
let curso = "Curso de JavaScript";
console.log(curso.includes("Java")); // true
```

---

### 📝 Ejercicio 5: Cortar parte del texto
**Instrucción:** Extrae la palabra `"Hola"` de `"Hola mundo cruel"`.

```javascript
let frase = "Hola mundo cruel";
console.log(frase.slice(0, 4)); // "Hola"
```

---

# 📌 Tarea para casa (con consignas)

### ✏️ Tarea 1:
Declara un string `"    Estoy feliz aprendiendo JS    "` y:
- Elimina los espacios con `.trim()`
- Convierte todo a mayúsculas

### ✏️ Tarea 2:
Crea una variable con tu nombre completo y usa `.replace()` para cambiar tu segundo nombre por una inicial.

### ✏️ Tarea 3:
Verifica si tu nombre contiene la letra `"a"` (mayúscula o minúscula, usando `.toLowerCase()`)

---

¿Listo para dominar los strings? 💪
