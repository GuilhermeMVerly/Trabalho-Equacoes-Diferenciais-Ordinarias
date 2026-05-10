Considere o problema de estudar a varia¸c˜ao da quantidade de n´ucleos radioativos de uma substˆancia
que sofre decaimento e, ao mesmo tempo, possui uma produ¸c˜ao cont´ınua de novos n´ucleos em raz˜ao
de uma rea¸c˜ao nuclear controlada. Este processo pode ser modelado por uma equa¸c˜ao diferencial
do tipo:
dN
dt = −λN + P, (1)
onde:
• N(t) ´e o n´umero de n´ucleos radioativos no instante t (em ´atomos);
• λ ´e a constante de decaimento (em dia−1
);
• P ´e a taxa de produ¸c˜ao constante de novos n´ucleos (em ´atomos/dia).
Considere para o problema proposto os seguintes parˆametros:



N(0) = 1000 n´ucleos
λ = 2,7 dia−1
P = 20 n´ucleos/dia
Atividades Propostas
1. Resolva a equa¸c˜ao diferencial analiticamente, encontrando N(t).
2. Implemente, utilizando uma linguagem de programa¸c˜ao de sua escolha:
(a) O m´etodo de Euler com passo h = 0,5, h = 0,1 e h = 0,05;
(b) O m´etodo de Runge-Kutta de quarta ordem com passo h = 1,0, h = 0,5 e h = 0,1.
3. Considere o intervalo de tempo 0 ≤ t ≤ 5 dia.
4. Plote os gr´aficos das solu¸c˜oes num´ericas obtidas por cada m´etodo e passo, juntamente com a
solu¸c˜ao anal´ıtica no mesmo gr´afico.
5. Calcule e apresente o desvio relativo percentual entre as solu¸c˜oes num´ericas e a anal´ıtica nos
instantes de tempo t = [0, 1, 2, 3, 4, 5] dias.
6. Comente os resultados obtidos. Qual m´etodo apresentou melhor desempenho? Como o
tamanho do passo afetou a precis˜ao das solu¸c˜oes? Qual ´e o efeito da produ¸c˜ao cont´ınua
sobre o comportamento do n´umero de n´ucleos ao longo do tempo?
