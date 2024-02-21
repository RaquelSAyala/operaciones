# Librería operaciones de vectores y matrices complejas.
## Autora: Raqul Iveth Selma Ayala

Librería desarrollada con la intento de llevar a cabo cálculos matemáticos que involucran vectores 
y matrices de naturaleza compleja. En este conjunto de herramientas, se incluyen las próximas funciones:

1. Adición de vectores complejos.
2. Inverso (aditivo) de un vector complejos.
3. Multiplicación de un escalar por un vector complejo.
4. Adición de matrices complejas.
5. Inversa (aditiva) de una matriz compleja.
6. Multiplicación de un escalar por una matriz compleja.
7. Transpuesta de una matriz/vector
8.  Conjugada de una matriz/vector
9.  Adjunta (daga) de una matriz/vector
10. Producto de dos matrices (de tamaños compatibles)
11. Función para calcular la "acción" de una matriz sobre un vector.
12. Producto interno de dos vectores
13. Norma de un vector
14. Distancia entre dos vectores
15. Valores  y vectores propios de una matriz
16. Revisar si una matriz es unitaria
17. Revisar si una matriz es Hermitiana
18. Producto tensor de dos matrices/vectores

## ¿Cómo se usa?
Es esencial tener conocimiento de los números complejos que se pretenden manipular, 
y luego seleccionar de manera adecuada las funciones prediseñadas y simplificadas para su aplicación.


## Notación

(Parte real, Parte Compleja)

# Casos de prueba para las funciones de operaciones con números complejos

# Vectores complejos
vec1 = [1+2j, 3-1j]
vec2 = [2-1j, 4+3j]

# Matrices complejas
mat1 = [[1+2j, 3-1j],
       [0+1j, -2-3j]]
mat2 = [[2-1j, 4+3j],
        [1-2j, 5+4j]]
mat3 = [[1+2j, 3-1j], 
       [0+1j, -2-3j]]

# Pruebas para las funciones de operaciones con números complejos
print("Suma de vectores complejos:", sumar_vectores_complejos(vec1, vec2))
print("Inverso de vector complejo:", inverso_vector_complejo(vec1))
print("Multiplicación escalar de vector complejo:", multiplicar_escalar_vector_complejo(2+3j, vec1))

print("Suma de matrices complejas:\n", sumar_matrices_complejas(mat1, mat2))
print("Inversa de matriz compleja:\n", inversa_matriz_compleja(mat1))
print("Multiplicación escalar de matriz compleja:\n", multiplicar_escalar_matriz_compleja(2-1j, mat2))

print("Matriz transpuesta:\n", matriz_transpuesta(mat3))
print("Matriz conjugada:\n", matriz_conjugada(mat3))




