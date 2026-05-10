**Trabalho- Equações Diferenciais Ordinárias**

**Membros: Gabriel Gonçalves Figueira, Guilherme Munhooz Verly e Paulo Emanuel De Araujo Pessanha** 

Consideramos o problema de estudar a variação da quantidade de núcleos radioativos de uma substância
que sofre decaimento e, ao mesmo tempo, possui uma produção contínua de novos núcleos em razão
de uma reação nuclear controlada. Este processo pode ser modelado por uma equação diferencial
do tipo:

$\frac{dN}{dt} = -λN  + P$

onde:

• N(t) é o número de núcleos radioativos no instante t (em átomos);

• λ é a constante de decaimento (em dia−1);

• P é a taxa de produção constante de novos núcleos (em átomos/dia).

Consideramos para o problema proposto os seguintes parâmetros:

N(0) = 1000 núcleos; λ = 2,7 dia−1; P = 20 núcleos/dia;

**Atividades Propostas**

1. Resolver a equação diferencial analiticamente, encontrando N(t).
 
2. Implementar, utilizando a linguagem de programação Python:
   
   (a) O método de Euler com passo h = 0,5, h = 0,1 e h = 0,05;

   (b) O método de Runge-Kutta de quarta ordem com passo h = 1,0, h = 0,5 e h = 0,1.

4. Considerar o intervalo de tempo 0 ≤ t ≤ 5 dia.

5. Plotar os gráficos das soluções numéricas obtidas por cada método e passo, juntamente com a
solução analítica no mesmo gráfico.

7. Calcular e apresentar o desvio relativo percentual entre as soluções numéricas e a analítica nos
instantes de tempo t = [0, 1, 2, 3, 4, 5] dias.

9. Comentar os resultados obtidos. Qual método apresentou melhor desempenho? Como o
tamanho do passo afetou a precisão das soluções? Qual é o efeito da produção contínua
sobre o comportamento do número de núcleos ao longo do tempo?
