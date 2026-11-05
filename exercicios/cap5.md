# Lista de Exercícios: Capítulo 5

**Adaptada do livro _Cálculo Numérico: Aspectos Teóricos e Computacionais (2ª Edição)_, de Márcia Ruggiero e Vera Lúcia da Rocha Lopes.**

**1.**

Dada a tabela abaixo:

| x | 2.4 | 2.6 | 2.8 | 3.0 | 3.2 | 3.4 | 3.6 | 3.8 |
|---|---|---|---|---|---|---|---|---|
| $e^x$ | 11.02 | 13.46 | 16.44 | 20.08 | 24.53 | 29.96 | 36.59 | 44.70 |

Calcule $e^{3.1}$ usando um polinômio de interpolação sobre três pontos.


**10.**

Seja a tabela:

| x | 0.15 | 0.20 | 0.25 | 0.30 | 0.35 | 0.40 |
|---|---|---|---|---|---|---|
| f(x) | 0.12 | 0.16 | 0.19 | 0.22 | 0.25 | 0.27 |

Usando um polinômio interpolador de grau 2, trabalhe de dois modos diferentes para obter o valor estimado de $x$ para o qual $f(x)=0.23$.

**14.**

Dada a tabela:

| x | 0 | 0.2618 | 0.5234 | 0.7854 | 1.0472 | 1.309 |
|---|---|---|---|---|---|---|
| f(x) | 0 | 1.0353 | 2 | 2.8284 | 3.4641 | 3.8637 |

Obtenha uma aproximação para $f(0.6)$ usando um polinômio interpolador de grau 4 na forma de Newton.


# Lista de Exercícios: Interpolação Polinomial

**Adaptada do _Caderno Didático de Métodos Numéricos em Python_ Tiago M. Buriol, Universidade Federal de Santa Maria (UFSM).**

**1.**

Encontre polinômios interpoladores para as funções abaixo no intervalo de $x_0=1$ até $x_n=3$, com 3, 4 e 5 pontos escolhidos arbitrariamente no intervalo.

a) $f(x)=\ln(x+1)$

b) $f(x)=\sqrt{1+x}$

c) $f(x)=e^{2x}\cos(3x)$

**2.**

Dada a tabela a seguir de valores de uma função $f$:

| x | 0,15 | 0,17 | 0,19 | 0,21 |
|---|---|---|---|---|
| f(x) | 0,176 | 0,234 | 0,278 | 0,322 |

a) Obtenha uma estimativa para $f(0,20)$ utilizando interpolação polinomial.

b) Obtenha a expressão analítica do polinômio interpolador.

c) Estime $f(0,20)$ e $f(0,22)$ utilizando um polinômio de segundo grau. Compare os resultados com os obtidos anteriormente.

**3.**

O concreto novo ganha resistência com o passar dos dias, atingindo 99% de sua resistência máxima aos 28 dias.

A tabela abaixo mostra os resultados de um ensaio de resistência à compressão simples (em MPa), obtidos em laboratório especializado, de três diferentes traços de concreto:

1. Dosagem padrão, sem a adição de agregado miúdo reciclado.
2. Substituindo 20% de agregado miúdo natural por agregado miúdo reciclado.
3. Substituindo 40% de agregado miúdo natural por agregado miúdo reciclado.

| Dias | Traço 1 | Traço 2 | Traço 3 |
|---|---|---|---|
| 3 | 14,4025 | 21,8450 | 19,0045 |
| 7 | 27,4350 | 31,2800 | 26,7450 |
| 14 | 34,4900 | 35,1600 | 31,3000 |
| 21 | 34,3750 | 38,1000 | 34,1800 |
| 28 | 36,1650 | 39,9800 | 35,6550 |

a) Encontre o polinômio que interpola os dados de cada um dos ensaios.

b) Estime quantos dias são necessários para que cada um dos concretos alcance 32 MPa.

c) Encontre a resistência de cada concreto após 16 dias.

**4.**

Utilize polinômios interpoladores de Lagrange de grau três para aproximar cada um dos seguintes valores:

a) $f(8,4)$, sabendo que:

| x | 8,1 | 8,3 | 8,6 | 8,7 |
|---|---|---|---|---|
| f(x) | 16,94410 | 17,56492 | 18,50515 | 18,82091 |

b) $f(-1/3)$, sabendo que:

| x | -0,75 | -0,5 | -0,25 | 0 |
|---|---|---|---|---|
| f(x) | -0,07181250 | -0,02475000 | 0,33493750 | 1,10100000 |

c) $f(0,25)$, sabendo que:

| x | 0,1 | 0,2 | 0,3 | 0,4 |
|---|---|---|---|---|
| f(x) | 0,62049958 | -0,28398668 | 0,00660095 | 0,24842440 |

d) $f(0,9)$, sabendo que:

| x | 0,6 | 0,7 | 0,8 | 1,0 |
|---|---|---|---|---|
| f(x) | -0,17694460 | 0,01375227 | 0,22363362 | 0,65809197 |


**5.**

Use interpolação de Newton para construir polinômios interpoladores de grau três para os pontos espaçados de forma desigual fornecidos na tabela a seguir:

| x | -0,1 | 0,0 | 0,2 | 0,3 |
|---|---|---|---|---|
| f(x) | 5,30 | 2,00 | 3,19 | 1,00 |

Acrescente $f(0,35)=0,97260$ à tabela e construa o polinômio interpolador de grau quatro.