Considere o problema de estudar a varia¸c˜ao da quantidade de n´ucleos radioativos de uma substˆancia
que sofre decaimento e, ao mesmo tempo, possui uma produ¸c˜ao cont´ınua de novos n´ucleos em raz˜ao
de uma rea¸c˜ao nuclear controlada. Este processo pode ser modelado por uma equação diferencial
do tipo:

dN
dt = −λN + P, (1)
onde:

• N(t) é o número de núcleos radioativos no instante t (em átomos);
• λ é a constante de decaimento (em dia−1);
• P ´e a taxa de produ¸c˜ao constante de novos núcleos (em átomos/dia).
Considere para o problema proposto os seguintes parâmetros:
N(0) = 1000 n´ucleos
λ = 2,7 dia−1
P = 20 n´ucleos/dia

Atividades Propostas
1. Resolver a equação diferencial analiticamente, encontrando N(t).
 
2. Implementar, utilizando a linguagem de programação Python:
   
(a) O método de Euler com passo h = 0,5, h = 0,1 e h = 0,05;

(b) O método de Runge-Kutta de quarta ordem com passo h = 1,0, h = 0,5 e h = 0,1.

4. Considere o intervalo de tempo 0 ≤ t ≤ 5 dia.

5. Plote os gr´aficos das soluções numéricas obtidas por cada método e passo, juntamente com a
solução analítica no mesmo gráfico.

7. Calcule e apresente o desvio relativo percentual entre as soluções numéricas e a analítica nos
instantes de tempo t = [0, 1, 2, 3, 4, 5] dias.

9. Comente os resultados obtidos. Qual método apresentou melhor desempenho? Como o
tamanho do passo afetou a precisão das soluções? Qual é o efeito da produção contínua
sobre o comportamento do n´umero de n´ucleos ao longo do tempo?
