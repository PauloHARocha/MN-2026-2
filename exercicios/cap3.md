# Lista de Exercícios: Capítulo 3

**Adaptada do livro _Cálculo Numérico: Aspectos Teóricos e Computacionais (2ª Edição) Márcia Ruggiero e Vera Lúcia da Rocha Lopes_**

**5.** Resolva o sistema linear a seguir utilizando o Método da Eliminação de Gauss:

$$
\begin{cases}
2x_1 + 2x_2 + x_3 + x_4 = 7\\
x_1 - x_2 + 2x_3 - x_4 = 1\\
3x_1 + 2x_2 - 3x_3 - 2x_4 = 4\\
4x_1 + 3x_2 + 2x_3 + x_4 = 12
\end{cases}
$$


**22.** Para cada sistema apresentado:

a) Verifique se o critério de Sassenfeld é satisfeito.

b) Caso seja possível, resolva o sistema utilizando Gauss-Seidel.

Primeiro sistema:

$$
A=
\begin{bmatrix}
10 & 1 & 1\\
1 & 10 & 1\\
1 & 1 & 10
\end{bmatrix},
\qquad
b=
\begin{bmatrix}
12\\12\\12
\end{bmatrix}
$$

Segundo sistema:

$$
A=
\begin{bmatrix}
4 & -1 & 0 & 0\\
-1 & 4 & -1 & 0\\
0 & -1 & 4 & -1\\
0 & 0 & -1 & 4
\end{bmatrix},
\qquad
b=
\begin{bmatrix}
1\\1\\1\\1
\end{bmatrix}
$$

**25.** Considere o sistema:

$$
\begin{cases}
2x_1 + 5x_2 = -3\\
3x_1 + x_2 = 2
\end{cases}
$$

a) Resolva o sistema utilizando os métodos de Gauss-Jacobi e Gauss-Seidel.

b) Repita os procedimentos após trocar a ordem das equações.

c) Compare os resultados e discuta o comportamento dos métodos.

**29.** Considere o sistema linear \(Ax=b\), cuja matriz de coeficientes é esparsa:

$$
A=
\begin{bmatrix}
1 & 1 & -1 & 2 & -1\\
2 & 0 & 0 & 0 & 0\\
0 & 2 & 0 & 0 & 0\\
4 & 0 & 0 & 16 & 0\\
0 & 0 & 4 & 0 & 0
\end{bmatrix},
\qquad
b=
\begin{bmatrix}
2\\2\\2\\20\\4
\end{bmatrix}
$$

a) Determine a solução examinando diretamente as equações do sistema.

b) Investigue como a reorganização das linhas pode facilitar a aplicação da Eliminação de Gauss. Apresente uma conclusão geral.

c) Aplique Gauss-Seidel e analise o comportamento do método.

d) Compare as características dos métodos diretos e iterativos quando aplicados a sistemas lineares esparsos.


# Lista de Exercícios: Sistemas Lineares

**Adaptada do _Caderno Didático de Métodos Numéricos em Python_ Tiago M. Buriol, Universidade Federal de Santa Maria (UFSM).**

**1.**

Use a eliminação de Gauss para resolver os seguintes sistemas lineares. Não reordene as equações. A solução exata para cada sistema é $(x_1,x_2,x_3)=(1,-1,3)$.

**(a)**

$$
\begin{cases}
4x_1-x_2+x_3=8\\
2x_1+5x_2+2x_3=3\\
x_1+2x_2+4x_3=11
\end{cases}
$$

**(b)**

$$
\begin{cases}
4x_1+x_2+2x_3=9\\
2x_1+4x_2-x_3=-5\\
x_1+x_2-3x_3=-9
\end{cases}
$$

**2.**

Resolva o seguinte sistema linear utilizando a eliminação de Gauss:

$$
\begin{cases}
x_1+x_2-x_3+x_4-x_5=2\\
2x_1+2x_2+x_3-x_4+x_5=4\\
3x_1+x_2-3x_3-2x_4+3x_5=8\\
4x_1+x_2-x_3+4x_4-5x_5=16\\
16x_1-x_2+x_3-x_4-x_5=32
\end{cases}
$$

**3.**

Determine a fatoração LU da matriz $A$ e resolva o sistema linear $Ax=b$, em que:

$$
A=
\begin{bmatrix}
1&1&0&3\\
2&1&-1&1\\
3&-1&-1&2\\
-1&2&3&-1
\end{bmatrix}
\qquad
b=
\begin{bmatrix}
4\\
1\\
-3\\
4
\end{bmatrix}
$$

**4.**

Use a fatoração do exercício anterior para resolver o sistema:

$$
\begin{cases}
x_1+x_2+3x_4=8\\
2x_1+x_2-x_3+x_4=7\\
3x_1-x_2-x_3+2x_4=14\\
-x_1+2x_2+3x_3-x_4=-7
\end{cases}
$$

**5.**

Usando algum método iterativo, determine uma solução aproximada para os sistemas dados, com aproximação inicial $x^{(0)}=(0,0,\ldots,0)^T$ e 10 iterações.

**(a)**

$$
\begin{bmatrix}
5&1&2&1&-1\\
0&6&1&1&-1\\
0&1&-3&2&1\\
3&0&2&7&0\\
1&1&0&0&8
\end{bmatrix}
\begin{bmatrix}
x_1\\x_2\\x_3\\x_4\\x_5
\end{bmatrix}
=
\begin{bmatrix}
1\\2\\0\\2\\1
\end{bmatrix}
$$

**(b)**

$$
\begin{cases}
4x_1+x_2+x_3+x_5=6\\
-x_1-3x_2+x_3+x_4=6\\
2x_1+x_2+5x_3-x_4-x_5=6\\
-x_1-x_2-x_3+4x_4=6\\
2x_2-x_3+x_4+4x_5=6
\end{cases}
$$

**(c)**

$$
\begin{cases}
4x_1-x_2=0\\
-x_1+4x_2-x_3=5\\
-x_2+4x_3=0\\
4x_4-x_5=6\\
-x_4+4x_5-x_6=-2\\
-x_5+4x_6=6
\end{cases}
$$

**6.**

Use a técnica iterativa de Gauss-Seidel para encontrar soluções aproximadas de:

$$
\begin{cases}
10x_1-x_2+2x_3=6\\
-x_1+11x_2-x_3+3x_4=25\\
2x_1-x_2+10x_3-x_4=-11\\
3x_2-x_3+8x_4=15
\end{cases}
$$

Começando com $x=(0,0,0,0)^T$ e iterando até que:

$$
\frac{\|x^{(k)}-x^{(k-1)}\|_\infty}
{\|x^{(k)}\|_\infty}<10^{-3}
$$