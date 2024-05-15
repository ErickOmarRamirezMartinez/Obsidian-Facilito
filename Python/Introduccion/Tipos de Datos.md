# Tipos de Datos
## **Números**:

- **Enteros (`int`)**: Son números sin parte decimal. Pueden ser positivos o negativos.
- **Números de punto flotante (`float`)**: Representan números reales y pueden contener una fracción decimal.
- **Números complejos (`complex`)**: Se utilizan para representar números complejos, y se escriben como `a + bj`, donde `a` y `b` son flotantes y `j` representa la raíz cuadrada de -1.

Ejemplos:
```Python
x = 123  # int
y = 3.14  # float
z = 2 + 3j  # complex

```

## **Secuencias**:

- **Listas (`list`)**: Colecciones ordenadas y mutables de elementos que pueden ser de diferentes tipos.
- **Tuplas (`tuple`)**: Colecciones ordenadas e inmutables de elementos. Funcionan de manera similar a las listas pero no pueden modificarse después de creadas.
- **Cadenas de texto (`str`)**: Secuencias inmutables de caracteres Unicode.

Ejemplos:
```Python
lista = [1, 2, 3]
tupla = (1, 2, 3)
texto = "Hola Mundo"
```

## **Mapeos**:

- **Diccionarios (`dict`)**: Colecciones no ordenadas de pares clave-valor. Las claves deben ser únicas y son inmutables.
Ejemplo:

```Python
diccionario = {"nombre": "Juan", "edad": 30}
```

## **Conjuntos**:

- **Conjuntos (`set`)**: Colecciones no ordenadas de elementos únicos y mutables.
- **Conjuntos Inmutables (`frozenset`)**: Similar a los conjuntos, pero no se pueden modificar después de su creación.

Ejemplo:
```Python
conjunto = {1, 2, 3}
conjunto_inmutable = frozenset([1, 2, 3])
```

## **Booleanos (`bool`)**:

- Representan verdadero o falso y son subclases de enteros (True es 1, False es 0).

Ejemplo:
```python
verdadero = True
falso = False
```

## **Nulo (`NoneType`)**:

- El tipo para el valor `None`, que se utiliza para representar la ausencia de valor.

Ejemplo:
```Python
sin_valor = None
```


## Codigo Facilito Tipo de Datos
```Python
# String

  

titulo_curso = "Curso Profesional"

nombre_completo = "Erick Omar"

  

print(nombre_completo + " " + titulo_curso)

  
  

mensaje = '''

    Estos es un mensaje

    con saltos de linea

    Codigo Facilito

'''

print(mensaje)

  
  

# Int

numero_uno = 10

print(numero_uno)

  

# Float

numero_dos = 3.14

print(numero_dos)

  

# Boolean

numero_tres = True

  

print(numero_tres)
```