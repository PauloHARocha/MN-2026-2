# Lista de Exercícios: Capítulo 2

**Adaptada do livro _Cálculo Numérico: Aspectos Teóricos e Computacionais (2ª Edição) Márcia Ruggiero e Vera Lúcia da Rocha Lopes_**

**1.** Localize um intervalo $[a,b]$, com $b-a<1$, que contenha uma raiz de cada uma das equações a seguir.

a) $4\cos(x)-e^{2x}=0$

b) $\dfrac{x}{2}-\tan(x)=0$

c) $1-x\ln(x)=0$

d) $2^x-3x=0$

e) $x^3+x-1000=0$


**10.** Considere a função $f(x)=x^3-x-1$. Resolva-a pelo Método do Ponto Fixo com função de iteração $ \phi(x)=\frac{1}{x}+\frac{1}{x^2}$ e $x_0=1$. Justifique seus resultados.

**11.** Use o Método de Newton-Raphson para obter a menor raiz positiva das equações a seguir com precisão $\varepsilon=10^{-4}$.

a) $\dfrac{x}{2}-\tan(x)=0$

b) $2\cos(x)=e^{x/2}$

c) $x^5-6=0$

**12.** Aplique o Método de Newton-Raphson à equação $x^3-2x^2-3x+10=0$ com $x_0=1,9$. Justifique o que acontece.

**15.** Seja $f(x)=e^x-4x^2$ e $\xi$ sua raiz no intervalo $(0,1)$. Tomando $x_0=0,5$, encontre $\xi$ com precisão $\varepsilon=10^{-4}$ usando:

a) o Método do Ponto Fixo, com $\phi(x)=\frac{1}{2}e^{x/2}$

b) o Método de Newton-Raphson.

c) Compare a rapidez de convergência.

**16.** O valor de $\pi$ pode ser obtido através da resolução das seguintes equações:

a) $\sin(x)=0$

b) $\cos(x)+1=0$

Aplique o Método de Newton-Raphson com $x_0=3$ e precisão $10^{-7}$ em cada caso e compare os resultados. Justifique.

**19.** O polinômio $ p(x)=x^5-\frac{10}{9}x^3+\frac{5}{21}x$, tem seus cinco zeros reais, todos no intervalo $(-1,1)$.

a) Verifique que

$x_1\in(-1,-0,75)$

$x_2\in(-0,75,-0,25)$

$x_4\in(0,3,0,8)$

$x_5\in(0,8,1)$

b) Encontre, pelo respectivo método, usando $\varepsilon=10^{-5}$:

- $x_1$: Método de Newton-Raphson $(x_0=-0,8)$;
- $x_2$: Método da Bisseção $([a,b]=[-0,75;-0,25])$;
- $x_3$: Método da Posição Falsa $([a,b]=[-0,25;0,25])$;
- $x_4$: Método do Ponto Fixo $(I=[0,2;0,6],\ x_0=0,4)$;
- $x_5$: Método da Secante $(x_0=0,8,\ x_1=1)$.


# Lista de Exercícios: Métodos Numéricos Iterativos

**Adaptada do _Caderno Didático de Métodos Numéricos em Python_ Tiago M. Buriol, Universidade Federal de Santa Maria (UFSM).**

**1.** Determine um intervalo de tamanho **0,1** que contenha uma raiz de cada uma das seguintes equações.

a) $3x-e^x=0$

b) $\sin(x)+x^2+1=0$

c) $\sin(x)-x+2=0$

d) $2x-\tan(x)=0$

e) $3x-\cos(x)+1=0$

f) $\ln(x)-\sin(x)=0$


**2.** Localize graficamente um intervalo que contenha uma raiz e determine uma aproximação para a solução utilizando o Método da Bisseção com precisão $\varepsilon=10^{-3}$.

a) $x^2-2=0$

b) $3x-e^x=0$

c) $2x-\tan(x)=0$

d) $3x-\cos(x)+1=0$

e) $\ln(x)-\sin(x)=0$


**3.** A água está escoando em um canal trapezoidal com vazão $Q=20\ \text{m}^3/\text{s}$.

A profundidade crítica $y$ satisfaz a equação

$$
1-\frac{Q^2}{gA_c^3}B=0,
$$

em que $B=3+y$ e $A_c=3y+\frac{y^2}{2}$, sendo $g=9,81\ \text{m/s}^2$.

Determine a profundidade crítica $y$ utilizando o Método da Bisseção com precisão $\varepsilon=10^{-3}$.

**4.** Encontre uma aproximação inicial e utilize o Método do Ponto Fixo para as raízes das equações a seguir, se possível, com precisão de $\varepsilon=10^{-5}$.

a) $3x-e^x=0$

b) $2x-\tan(x)=0$

c) $e^x-3x^2=0$

d) $x^3+3x^2-1=0$

e) $x-0,8-0,2\sin(x)=0$

**5.** Utilize o Método de Newton-Raphson para encontrar soluções com precisão de $\varepsilon=10^{-5}$ para as equações a seguir.

a) $e^x+2^{-x}+2\cos(x)-6=0$

b) $(x-2)^2-\ln(x)=0$

c) $e^x-3x^2=0$

d) $\sin(x)-e^{-x}=0$

e) $x-0,8-0,2\sin(x)=0$


**6.** Use o Método de Newton-Raphson para determinar uma raiz real de $f(x)=-1+5,5x-4x^2+0,5x^3$ utilizando as aproximações iniciais:

a) $x_0=4,52$

b) $x_0=4,54$

Discuta e use métodos gráficos e analíticos para explicar quaisquer peculiaridades nos seus resultados.

**7.** Seja $f(x)=-x^3-\cos(x)$, com $x_0=-1$ e $x_1=0$, obtenha uma solução com precisão de 5 casas decimais utilizando o Método da Secante.

**8.** Obtenha uma solução para a equação $e^x+2^{-x}+2\cos(x)-6=0$ utilizando o Método da Secante com precisão $\varepsilon=10^{-5}$ e faça um gráfico do erro relativo em função do número de iterações.