
# 📚 Tipos de Datos en JavaScript

En JavaScript, los datos se agrupan en **tipos primitivos** y **tipos de objeto**.

---

## ✅ Tipos de datos primitivos

1. **String** – Cadenas de texto
```javascript
let nombre = "Daniel";
```

2. **Number** – Números (enteros o decimales)
```javascript
let edad = 25;
let precio = 19.99;
```

3. **Boolean** – Verdadero o falso
```javascript
let esMayor = true;
```

4. **Undefined** – Variable declarada pero sin valor
```javascript
let ciudad;
```

5. **Null** – Intencionalmente sin valor
```javascript
let valor = null;
```

6. **Symbol** – Valor único e inmutable (más avanzado)
```javascript
let id = Symbol("id");
```

7. **BigInt** – Números grandes (mayores que 2^53 - 1)
```javascript
let numeroGrande = 1234567890123456789012345678901234567890n;
```

---

## 🧱 Tipos de datos de objeto

1. **Object** – Estructura que agrupa pares clave-valor
```javascript
let persona = {
  nombre: "Ana",
  edad: 30
};
```

2. **Array** – Lista ordenada de elementos
```javascript
let frutas = ["manzana", "banana", "pera"];
```

3. **Function** – Bloque de código reutilizable
```javascript
function saludar() {
  console.log("Hola!");
}
```

---

# 🧪 Ejercicios prácticos

### 📝 Ejercicio 1:
Declara una variable tipo string llamada `pais` y asígnale el valor `"Bolivia"`.

### 📝 Ejercicio 2:
Declara una variable llamada `altura` y asígnale un número decimal.

### 📝 Ejercicio 3:
Declara una variable llamada `tienePermiso` y asígnale un valor booleano.

### 📝 Ejercicio 4:
Declara una variable `usuario` sin asignarle valor (undefined).

### 📝 Ejercicio 5:
Crea una variable `respuesta` con valor `null`.

### 📝 Ejercicio 6:
Declara un objeto llamado `auto` con propiedades `marca` y `modelo`.

### 📝 Ejercicio 7:
Crea un array llamado `colores` con al menos 3 elementos.

### 📝 Ejercicio 8:
Escribe una función `multiplicar` que reciba dos números y retorne su producto.

### 📝 Ejercicio 9:
Declara una variable `id` con un valor tipo `Symbol`.

### 📝 Ejercicio 10:
Declara un número muy grande usando `BigInt`.

---

# 🧠 Preguntas rápidas

1. ¿Qué diferencia hay entre `undefined` y `null`?
2. ¿Cómo se representa un valor booleano en JavaScript?
3. ¿Qué tipo de dato es un array?
4. ¿Qué tipo de dato es el resultado de `typeof null`?
5. ¿Qué método usarías para revisar si una variable es un array?

---

¿Listo para seguir practicando? 🚀
