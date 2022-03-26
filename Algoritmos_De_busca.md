Algoritmos de busca

Quando “busca em largura” funcionária melhor que “busca em profundidade”

 Busca em largura (Breadth-first search) é um algoritmo onde funciona melhor quando o que estamos procurando está mais próximo ao começo. Pensando nisso, podemos falar que quanto mais fundo estiver o que estamos procurando, mais tempo de execução levará.

Primeiro caso de uso
Poderíamos utilizar busca em largura para mapear a menor trajetória para recolher os lixos de uma cidade.
Segundo caso de uso
Supondo que precisamos encontrar os primeiros nomes que comecem com a letra B na lista telefônica, nesse caso o algoritmo de busca em largura também seria eficiente pelos nossos estados finais estarem no próximo a raiz de nossa árvore.
Quando “busca em profundidade” funcionária melhor que “busca em largura”

Busca em profundidade (depth-first search) é um algoritmo interessante, o fato dele começar pelo fundo da árvore nos podem trazer boas expectativas quando o que estamos procurando está mais próximo ao fundo da árvore.
Primeiro caso de uso
Dado um problema em um banco de dados, onde tenhamos um formato de ID onde começa com uma letra e três números em sequência (EX: A123 até Z123) Estamos procurando as matrículas que começam com a letra Y, se o nosso banco de dados estiver em uma ordem alfabética, essas matrículas estariam no final, assim o algoritmo de busca em profundidade seria mais eficiente.
Segundo caso de uso
Nós somos um time de cientista de dados em uma empresa de rede social chamada PINU, a PINU contém uma ferramenta para o Microsoft Teams onde consegue monitorar o status de seus funcionários na empresa (Isso é uma prática bastante questionável da empresa PINU). Nessa ferramenta é listado os status na seguinte ordem: Ocupado, Disponível e Ausente. Com isso, a empresa perguntou para a equipe de cientistas de dados qual forma de busca seria mais eficiente para achar as pessoas ausentes, um dos cientistas respondeu: “Busca em profundidade, porque poderíamos já partir do fim dessa lista”.

Utilizando busca em largura e busca em profundidade em uma árvore
Considerando a árvore abaixo qual o caminho percorrido para se chegar ao nó 11 utilizando as buscas em largura e profundidade?
 
Utilizando busca em largura 

A forma seria: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 e 11.
Onde em uma figura seria:  
Utilizando busca em profundidade

A forma seria: 1, 8, 9, 4, 10 e 11
Onde em uma figura seria: 
 
 
