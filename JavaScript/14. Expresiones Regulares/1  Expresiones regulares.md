Las expresiones regulares son una herramienta poderosa en JavaScript para la búsqueda y manipulación de cadenas. Permiten definir patrones de búsqueda complejos que facilitan la validación, extracción y transformación de texto de manera eficiente. En esta sección, exploraremos los conceptos básicos de las expresiones regulares y cómo pueden ser utilizadas en JavaScript.

#### ¿Qué son las Expresiones Regulares?

Una expresión regular es una secuencia de caracteres que forma un patrón de búsqueda. Se utiliza principalmente para la búsqueda de patrones de cadenas de texto. Una expresión regular puede ser tan simple como una palabra, o tan complicada como se necesite para cumplir con un patrón específico.

#### Sintaxis Básica

Las expresiones regulares en JavaScript se pueden definir de dos maneras:

1. **Literal de expresión regular:** Utilizando barras inclinadas para encerrar el patrón.
    
    javascript
    
    Copiar código
    
    `let regex = /abc/;`
    
2. **Constructor de la clase RegExp:** Útil cuando el patrón necesita ser dinámico.
    
    javascript
    
    Copiar código
    
    `let regex = new RegExp('abc');`
    

#### Métodos Comunes Usando Expresiones Regulares

- **`test()`**: Comprueba si una cadena cumple con el patrón definido por la expresión regular.
    
    javascript
    
    Copiar código
    
    `let pattern = /hello/; console.log(pattern.test("hello world")); // true`
    
- **`exec()`**: Busca una coincidencia en una cadena y devuelve un array con la información o `null` si no hay coincidencias.
    
    javascript
    
    Copiar código
    
    `let result = pattern.exec("hello world"); console.log(result[0]); // "hello" console.log(result.index); // 0`
    
- **`match()`**: Método de String que busca en la cadena las coincidencias con la expresión regular.
    
    javascript
    
    Copiar código
    
    `let matches = "hello world".match(/hello/); console.log(matches[0]); // "hello"`
    
- **`replace()`**: Método de String que realiza sustituciones basadas en una expresión regular.
    
    javascript
    
    Copiar código
    
    `let replacedText = "hello world".replace(/hello/, "goodbye"); console.log(replacedText); // "goodbye world"`
    
- **`search()`**: Método de String que devuelve el índice de la primera coincidencia de la expresión regular, o -1 si no se encuentra ninguna coincidencia.
    
    javascript
    
    Copiar código
    
    `let searchIndex = "hello world".search(/world/); console.log(searchIndex); // 6`
    

#### Flags de Expresiones Regulares

Las expresiones regulares pueden incluir "flags" que modifican su comportamiento:

- **`g`**: Global, no se detiene después de la primera coincidencia.
- **`i`**: Insensible a mayúsculas y minúsculas.
- **`m`**: Multilínea, permite que los caracteres de inicio y fin (`^` y `$`) operen en múltiples líneas.

javascript

Copiar código

`let regexGi = /hello/gi;`

#### Uso Práctico

Las expresiones regulares son útiles en muchas situaciones, como la validación de entradas de usuario (por ejemplo, verificar formatos de correo electrónico o números de teléfono), el análisis de texto y la transformación de datos.


[Regex101.com](https://regex101.com/)

---
![[Pasted image 20240516210945.png]]
![[Pasted image 20240516211006.png]]
![[Pasted image 20240516211102.png]]
![[Pasted image 20240516211136.png]]
![[Pasted image 20240516211146.png]]


