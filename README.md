# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Scarlet Angelina Ruelas Cardeña
## Actividad \#16 - Matrices doc
## Fecha: 11/Octubre/2025
## Descripción: En esta actividad se modificará el código utilizando formato Markdown de manera que al ejecutarlo se muestre los cambios del documento con los datos personales y de la materia a la vez que resolvemos los ejercicios.
# Determinantes de Matrices 2×2  
Este documento explica paso a paso cómo se calculan los determinantes de varias matrices 2×2.

La fórmula general para una matriz:

\[
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
\]

es:

\[
\text{det} = a \cdot d - b \cdot c
\]

---

##  Matriz A
\[
A =
\begin{pmatrix}
5 & 2 \\
3 & 1
\end{pmatrix}
\]

### Sustitución en la fórmula:
- \(a = 5\)
- \(b = 2\)
- \(c = 3\)
- \(d = 1\)

### Cálculo:
- \(a \cdot d = 5 \cdot 1 = 5\)
- \(b \cdot c = 2 \cdot 3 = 6\)

\[
\text{det}(A) = 5 - 6 = -1
\]

---

##  Matriz B
\[
B =
\begin{pmatrix}
-1 & 4 \\
2 & -8
\end{pmatrix}
\]

### Sustitución:
- \(a = -1\)
- \(b = 4\)
- \(c = 2\)
- \(d = -8\)

### Cálculo:
- \(a \cdot d = -1 \cdot -8 = 8\)
- \(b \cdot c = 4 \cdot 2 = 8\)

\[
\text{det}(B) = 8 - 8 = 0
\]

---

##  Matriz C
\[
C =
\begin{pmatrix}
6 & 9 \\
2 & 3
\end{pmatrix}
\]

### Sustitución:
- \(a = 6\)
- \(b = 9\)
- \(c = 2\)
- \(d = 3\)

### Cálculo:
- \(a \cdot d = 6 \cdot 3 = 18\)
- \(b \cdot c = 9 \cdot 2 = 18\)

\[
\text{det}(C) = 18 - 18 = 0
\]

---

##  Matriz D
\[
D =
\begin{pmatrix}
0 & 5 \\
-5 & 0
\end{pmatrix}
\]

### Sustitución:
- \(a = 0\)
- \(b = 5\)
- \(c = -5\)
- \(d = 0\)

### Cálculo:
- \(a \cdot d = 0 \cdot 0 = 0\)
- \(b \cdot c = 5 \cdot -5 = -25\)

\[
\text{det}(D) = 0 - (-25) = 25
\]

---

##  Conclusiones
- Si el determinante es **0**, la matriz **no es invertible** (matrices B y C).
- Si el determinante es diferente de 0, la matriz **sí es invertible** (matrices A y D).

---
