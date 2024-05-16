JavaScript ofrece dos características sintácticas poderosas y versátiles conocidas como **spread syntax** y **rest syntax**. Aunque utilizan la misma notación de tres puntos (`...`), sus propósitos y usos son bastante distintos.

#### Spread Syntax (Sintaxis de Expansión)

La **spread syntax** permite que un arreglo u objeto iterable (como un string o otro arreglo) sea expandido en lugares donde se esperan cero o más argumentos (en llamadas a funciones) o elementos (en arreglos).

##### Usos Comunes de Spread Syntax:

1. **Combinar Arreglos:**
    
    ```js
let frutas = ['manzana', 'banana']; let masFrutas = ['naranja', 'uva']; let todasLasFrutas = [...frutas, ...masFrutas]; console.log(todasLasFrutas); // ['manzana', 'banana', 'naranja', 'uva']
```
    
2. **Copiar Arreglos:**
    
    ```js
let copiaFrutas = [...frutas]; console.log(copiaFrutas); // ['manzana', 'banana']
```
    
3. **Expansión de Objetos:**
    
```js
let objeto = { nombre: 'Ana', edad: 20 }; let copiaObjeto = { ...objeto }; console.log(copiaObjeto); // { nombre: 'Ana', edad: 20 }
```
    
4. **Argumentos de Función:**
    
```js
function suma(x, y, z) {     return x + y + z; } let numeros = [1, 2, 3]; console.log(suma(...numeros)); // 6
```
    

#### Rest Syntax (Sintaxis de Resto)

La **rest syntax** se usa para representar un número indefinido de argumentos como un arreglo. Esto es útil en funciones cuando quieres aceptar múltiples argumentos sin especificar exactamente cuántos aceptarás.

##### Usos Comunes de Rest Syntax:

1. **Funciones con Número Indefinido de Argumentos:**
    
```js
function sumarTodos(...numeros) {     return numeros.reduce((acum, num) => acum + num, 0); } console.log(sumarTodos(1, 2, 3, 4)); // 10
```
    
2. **Desestructuración con Múltiples Elementos Restantes:**
    
    ```js
let [primera, ...resto] = [1, 2, 3, 4]; console.log(primera); // 1 console.log(resto); // [2, 3, 4]
```
    

### Diferencias Clave

- **Spread:** Descompone un arreglo o objeto en elementos individuales o propiedades.
- **Rest:** Combina múltiples elementos en un solo arreglo.
---

![[Pasted image 20240516004548.png]]
![[Pasted image 20240516004614.png]]

---
![[Pasted image 20240516005101.png]]
![[Pasted image 20240516005207.png]]


---
# Diferencia entre rest al argumento arguments
![[Pasted image 20240516005312.png]]
