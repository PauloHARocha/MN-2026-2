# Lista de Exercícios: Capítulo 6

**Adaptada do livro _Cálculo Numérico: Aspectos Teóricos e Computacionais (2ª Edição)_, de Márcia Ruggiero e Vera Lúcia da Rocha Lopes.**

**1.**

Dado um conjunto de valores $(x_k, f(x_k))$, $k = 0, 1, 2, \ldots, m$, descreva situações em que você usaria um polinômio interpolador por esses pontos e situações em que você ajustaria uma curva a estes dados pelo método dos quadrados mínimos.

**2.**

Ajuste os dados abaixo pelo método dos quadrados mínimos utilizando:

a) Uma reta.

b) Uma parábola do tipo $ax^2 + bx + c$.

Trace as duas curvas no gráfico de dispersão dos dados. Como você compararia as duas curvas com relação aos dados?

| x | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|---|---|---|---|---|---|---|---|---|
| y | 0.5 | 0.6 | 0.9 | 0.8 | 1.2 | 1.5 | 1.7 | 2.0 |

**3.**

Dada a tabela abaixo, faça o gráfico de dispersão dos dados e ajuste uma curva da melhor maneira possível:

| x | 0.5 | 0.75 | 1 | 1.5 | 2.0 | 2.5 | 3.0 |
|---|---|---|---|---|---|---|---|
| y | -2.8 | -0.6 | 1 | 3.2 | 4.8 | 6.0 | 7.0 |

**4.**

A tabela abaixo mostra as alturas e pesos de uma amostra de nove homens entre as idades de 25 a 29 anos, extraída ao acaso entre funcionários de uma grande indústria:

| Altura (cm) | 183 | 173 | 168 | 188 | 158 | 163 | 193 | 163 | 178 |
|---|---|---|---|---|---|---|---|---|---|
| Peso (kg) | 79 | 69 | 70 | 81 | 61 | 63 | 79 | 71 | 73 |

a) Faça o diagrama de dispersão dos dados e observe que parece existir uma relação linear entre a altura e o peso.

b) Ajuste uma reta que descreva o comportamento do peso em função da altura, isto é, peso = f(altura).

c) Estime o peso de um funcionário com 175 cm de altura; e estime a altura de um funcionário com 80 kg.

d) Ajuste agora a reta que descreve o comportamento da altura em função do peso, isto é, altura = g(peso).

e) Resolva o item (c) com essa nova função e compare os resultados obtidos. Tente encontrar uma explicação.

f) Coloque num gráfico as equações (b) e (d) e compare-as.

**5.**

A tabela abaixo fornece o número de habitantes do Brasil (em milhões) desde 1872:

| Ano | 1872 | 1890 | 1900 | 1920 | 1940 | 1950 | 1960 | 1970 | 1980 | 1991 |
|---|---|---|---|---|---|---|---|---|---|---|
| Habitantes | 9.9 | 14.3 | 17.4 | 30.6 | 41.2 | 51.9 | 70.2 | 93.1 | 119.0 | 146.2 |

a) Obtenha uma estimativa para a população brasileira no ano 2000. Analise seu resultado.

b) Em que ano a população brasileira ultrapassou o índice de 100 milhões?


# Lista de Exercícios: Ajuste por Mínimos Quadrados

**Adaptada do _Caderno Didático de Métodos Numéricos em Python_ Tiago M. Buriol, Universidade Federal de Santa Maria (UFSM).**


**1.**

Em um experimento foram obtidos os seguintes dados:

| $x_i$ | 0 | 1 | 2 | 3 | 4 |
|---|---|---|---|---|---|
| $f(x_i)$ | 0,01 | 1,01 | 1,40 | 3,81 | 4,01 |

**(a)** Determine a reta que melhor se ajusta aos dados da tabela, usando o método dos mínimos quadrados.

**(b)** Calcule a soma do erro quadrático:

$$
\sum_{i=1}^{5}\left(f(x_i)-g(x_i)\right)^2
$$

**2.**

Encontre o polinômio

$$
p(x)=a_1+a_2x+a_3x^2
$$

que melhor se ajusta no sentido de mínimos quadrados aos pontos:

| $i$ | 1 | 2 | 3 | 4 |
|---|---|---|---|---|
| $x_i$ | -1,50 | -0,50 | 1,25 | 1,50 |
| $y_i$ | 1,15 | -0,37 | 0,17 | 0,94 |

**Resposta:** $a_1=-0,67112$, $a_2=-0,12123$, $a_3=0,73907$.

**3.**

Encontre a parábola

$$
y=ax^2+bx+c
$$

que melhor aproxima o seguinte conjunto de dados:

| $i$ | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| $x_i$ | 0,01 | 1,02 | 2,04 | 2,95 | 3,55 |
| $y_i$ | 1,99 | 4,55 | 7,20 | 9,51 | 10,82 |

**4.**

Após serem efetuadas medições num gerador de corrente contínua, foram obtidos os seguintes valores indicados por um voltímetro e um amperímetro:

| $I$ (A) | 1,58 | 1,75 | 2,10 | 2,20 | 2,50 |
|---|---|---|---|---|---|
| $V$ (V) | 210 | 155 | 170 | 120 | 85 |

Faça um gráfico dos dados.

a) Ajuste os dados por um polinômio de grau adequado.

b) Estime o valor a ser obtido no voltímetro quando o amperímetro estiver marcando 4,0 A.