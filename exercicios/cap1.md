# Lista de Exercícios: Capítulo 1

**Adaptada do livro _Cálculo Numérico: Aspectos Teóricos e Computacionais (2ª Edição) Márcia Ruggiero e Vera Lúcia da Rocha Lopes_**

**1.** Converta os seguintes números decimais para sua forma binária:

- x = 37
- y = 2345
- z = 0,1217

**2.** Converta os seguintes números binários para sua forma decimal:

- x = $(101101)_2$
- y = $(110101011)_2$
- z = $(0,1101)_2$
- w = $(0,111111101)_2$

**3.** Seja um sistema de aritmética de ponto flutuante de quatro dígitos, base decimal e com acumulador de precisão dupla. Dados os números

- x = 0,7237 × 10<sup>4</sup>
- y = 0,2145 × 10<sup>−3</sup>
- z = 0,2585 × 10<sup>1</sup>

Efetue as seguintes operações e obtenha o erro relativo no resultado, supondo que x, y e z estão exatamente representados:

a) x + y + z

b) x − y − z

c) x / y

d) (xy) / z

e) x(y / z)

**9.** Considere uma máquina cujo sistema de representação de números é definido por:

$\beta$ = 10, t = 4, $e_1$ = −5 e $e_2$ = 5.

a) Qual o menor e o maior número em módulo representados nesta máquina?

b) Como será representado o número 73,758 nesta máquina, utilizando:
- arredondamento;
- truncamento.

c) Se a = 42450 e b = 3, qual o resultado de a + b?

d) Qual o resultado da soma

$$
S = 42450 + \sum_{k=1}^{10} 3
$$

nesta máquina?

e) Idem para a soma

$$
S = \sum_{k=1}^{10} 3 + 42450
$$

**10.** Escreva um programa em Python para obter o resultado da seguinte operação:

$$
S = 10000 - \sum_{k=1}^{n} x
$$

para:

a) n = 100000 e x = 0,1;

b) n = 80000 e x = 0,125.

Compare os resultados obtidos e explique.