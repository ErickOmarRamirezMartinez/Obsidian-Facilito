Los **arreglos** en JavaScript son estructuras de datos que permiten almacenar una colección de múltiples elementos bajo un solo nombre de variable. Estos elementos pueden ser de cualquier tipo, incluyendo números, cadenas, objetos, e incluso otros arreglos. Los arreglos son fundamentales en casi todos los programas de JavaScript debido a su versatilidad y la amplia gama de operaciones que se pueden realizar con ellos.

#### Creación de un Arreglo

Puedes crear un arreglo de varias maneras en JavaScript:

**Sintaxis Literal:**

```js
let frutas = ["manzana", "banana", "cereza"];
```

**Constructor de Arreglo:**

```js
let numeros = new Array(1, 2, 3, 4, 5);
```

#### Operaciones Básicas con Arreglos

Los arreglos en JavaScript ofrecen una variedad de métodos para realizar operaciones como añadir, eliminar y buscar elementos, así como otras transformaciones. Aquí algunos ejemplos comunes:

- **Añadir Elementos:**
    
    - `push()`: Añade uno o más elementos al final del arreglo.
    - `unshift()`: Añade uno o más elementos al inicio del arreglo.
    
    **Ejemplo:**

    ```js
let colores = ["rojo", "verde"]; colores.push("azul"); // ["rojo", "verde", "azul"] 
colores.unshift("amarillo"); // ["amarillo", "rojo", "verde", "azul"]``
```
    
- **Eliminar Elementos:**
    
    - `pop()`: Elimina el último elemento del arreglo y lo devuelve.
    - `shift()`: Elimina el primer elemento del arreglo y lo devuelve.
    
    **Ejemplo:**
    
	```js
let numeros = [1, 2, 3]; numeros.pop(); // [1, 2] numeros.shift(); // [2]``
	```
    
- **Buscar Elementos:**
    
    - `indexOf()`: Busca un elemento y devuelve su índice o -1 si no se encuentra.
    - `includes()`: Verifica si un arreglo contiene un elemento específico.
    
    **Ejemplo:**
    
    ```js
let animales = ["perro", "gato", "pez"]; console.log(animales.indexOf("gato")); // 1 console.log(animales.includes("pez")); // true
```

#### Usos Comunes de los Arreglos

1. **Almacenamiento de Datos:** Los arreglos son ideales para almacenar listas de datos, como listas de usuarios, productos en un carrito de compras, o datos para procesamiento.
2. **Manipulación de Datos:** Puedes usar arreglos para ordenar, filtrar y transformar datos de maneras complejas utilizando métodos como `sort()`, `filter()`, `map()` y `reduce()`.
3. **Control de Flujo:** Los arreglos se pueden usar para manejar múltiples tareas, ciclos o iteraciones, como en bucles `for` o `forEach()`.
4. **Implementación de Estructuras de Datos:** Los arreglos sirven como la base para estructuras de datos más complejas como pilas, colas, y matrices.

---

![[Pasted image 20240515210351.png]]
![[Pasted image 20240515210406.png]]
