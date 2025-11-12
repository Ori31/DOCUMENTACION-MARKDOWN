# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Sergio Orion Huerta Martinez
## Actividad \#16 - Matrices doc

---
### Identificación de matrices

Matriz identidad, porque la diagonal está compuestos por solo unos y los elementos fuera de la diagonal son ceros.

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

MUESTRA

Calcula la suma de A y B

$$ A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
\end{pmatrix}
$$

---
# OTRO EJERCICIO
...

Ejercicios Resueltos

Ejercicio 1: Suma de Matrices

Matrices dadas:


A = [ 2   3 ]
    [-1   5 ]

B = [ 4  -2 ]
    [ 3   1 ]

Operación: A + B

Procedimiento:
Se suman los elementos correspondientes de cada matriz:

Primera fila: 2+4 = 6, 3+(-2) = 1

Segunda fila: -1+3 = 2, 5+1 = 6

Resultado:

A + B = [ 6   1 ]
        [ 2   6 ]

Ejercicio 2: Resta de Matrices 

Matrices dadas:

A = [ 7   2 ]
    [ 5   9 ]

B = [ 3   1 ]
    [ 2   4 ]

Operación: A - B

Procedimiento:
Se restan los elementos correspondientes de cada matriz:

Primera fila: 7-3 = 4, 2-1 = 1

Segunda fila: 5-2 = 3, 9-4 = 5

Resultado:
text

A - B = [ 4   1 ]
        [ 3   5 ]

Ejercicio 3: Multiplicación por Escalar

Matriz dada:

A = [ 2   4 ]
    [-1   5 ]

Escalar: k = 3

Operación: 3A

Procedimiento:
Cada elemento de la matriz se multiplica por el escalar 3:

Primera fila: 3×2 = 6, 3×4 = 12

Segunda fila: 3×(-1) = -3, 3×5 = 15

Resultado:

3A = [ 6   12 ]
     [-3   15 ]

Ejercicio 4: Operaciones con Matrices 2x2

Matrices dadas:

A = [ 2  -1 ]
    [ 3   4 ]

B = [ 5   2 ]
    [-1   3 ]

a) Suma A + B

Procedimiento:

[ 2+5   -1+2 ]   [ 7   1 ]
[ 3+(-1) 4+3 ] = [ 2   7 ]

Resultado:

A + B = [ 7   1 ]
        [ 2   7 ]

b) Calcula 2A - B

Procedimiento:

Primero calculamos 2A:

2A = [ 4   -2 ]
     [ 6    8 ]

Luego restamos B:

[ 4-5   -2-2 ]   [ -1   -4 ]
[ 6-(-1) 8-3 ] = [  7    5 ]

Resultado:

2A - B = [ -1   -4 ]
         [  7    5 ]

c) Multiplicación AB

Procedimiento:

[ (2×5)+(-1×(-1))   (2×2)+(-1×3) ]   [ 10+1   4-3 ]   [ 11   1 ]
[ (3×5)+(4×(-1))    (3×2)+(4×3)  ] = [ 15-4   6+12] = [ 11  18 ]

Resultado:

AB = [ 11   1 ]
     [ 11  18 ]

d) Multiplicación BA

Procedimiento:

[ (5×2)+(2×3)    (5×(-1))+(2×4) ]   [ 10+6   -5+8 ]   [ 16   3 ]
[ (-1×2)+(3×3)   (-1×(-1))+(3×4)] = [ -2+9    1+12] = [  7  13 ]

Resultado:

BA = [ 16   3 ]
     [  7  13 ]

e) Transpuesta de A

Procedimiento:
Intercambiamos filas por columnas:

Primera fila de A: [2, -1] → primera columna de Aᵀ: [2, -1]ᵀ

Segunda fila de A: [3, 4] → segunda columna de Aᵀ: [3, 4]ᵀ

Resultado:

Aᵀ = [ 2   3 ]
     [-1   4 ]

Ejercicio 5: Verificación de la Propiedad Asociativa 

Matrices dadas:

A = [ 2   0 ]
    [ 1   3 ]

B = [ 1   2 ]
    [ 3   4 ]

C = [ 1   1 ]
    [ 0   2 ]

Objetivo: Verificar que A(BC) = (AB)C
Procedimiento para A(BC):

Calculamos BC:

BC = [ (1×1)+(2×0)   (1×1)+(2×2) ]   [ 1   5 ]
      [ (3×1)+(4×0)   (3×1)+(4×2) ] = [ 3  11 ]

Calculamos A(BC):


A(BC) = [ (2×1)+(0×3)   (2×5)+(0×11) ]   [ 2  10 ]
         [ (1×1)+(3×3)   (1×5)+(3×11) ] = [ 10 38 ]

Procedimiento para (AB)C:

Calculamos AB:
    

AB = [ (2×1)+(0×3)   (2×2)+(0×4) ]   [ 2   4 ]
      [ (1×1)+(3×3)   (1×2)+(3×4) ] = [ 10 14 ]

Calculamos (AB)C:

(AB)C = [ (2×1)+(4×0)   (2×1)+(4×2) ]   [ 2  10 ]
         [ (10×1)+(14×0) (10×1)+(14×2)] = [ 10 38 ]

Resultado:

A(BC) = [ 2  10 ]   =   (AB)C
        [ 10 38 ]


Son iguales asi q se cumple la condicion



---







