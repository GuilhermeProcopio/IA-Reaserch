<h1>Problema de busca</h1>


<h2>Estado</h2>

<p>
 Podemos começar abordando o significado do estado direto do dicionário:
 “conjunto de qualidades ou características com que as coisas se apresentam; conjunto de condições em que se encontram em determinado momento.”,
 usando essa abordagem em problemas de busca, podemos introduzir o seguinte ambiente: um labirinto. Nesse cenário, devemos saber que um labirinto 
 deve haver pelo menos um caminho para levar até a saída e outros que não sucedem a isso, nesse problema, a nossa busca seria encontrar a saída do labirinto,
 um ser humano por tentativa e erro teria diversos estados; estado inicial: onde você começa no labirinto e estado final: nosso objetivo. Pensando nisso,
 teríamos situações em que tentaríamos decorar os caminhos possíveis até chegarmos ao fim do labirinto, podemos pensar nesse mapeamento como um conjunto de 
 ações ou conjunto de estados, onde poderíamos chamá-lo de estado intermediário; onde ocorre diversas ações para chegar no estado final. Com isso poderíamos 
 concluir que um estado é um momento na qual há enquanto tenhamos o objetivo de algo. Ou seja, ter um estado inicial e um estado final (Largada e chegada, na 
 corrida).
 </p>

<h2>Espaço de estados</h2>
 
 <p>
Voltando ao nosso exemplo do labirinto,
definimos o que seria um estado e quais são os estados possíveis enquanto problema de busca no nosso cenário.
Usaremos o mesmo cenário para introduzir sobre o espaço de estados. Se procurarmos no dicionário o significado de espaço encontraremos:
“extensão ideal, sem limites, que contém todas as extensões finitas e todos os corpos ou objetos existentes ou possíveis.”,
o mais interessante nessa definição é “extensão ideal”, podemos pensar nisso em a extensão ideal entre um espaço e outro (estado inicial e estado final),
dentre esse espaço temos nossos estados no labirinto, a forma que mapeamos ou decoramos o caminho para que possamos chegar ao fim dele, sendo isso; 
espaço de estados pode ser um estado intermediário onde ocorre um conjunto de ações para podermos alcançar nosso estado final.
 </p>


<h2>Árvore de busca</h2>
<p>
É uma árvore utilizada para distribuir as possibilidades de um espaço de estados e com isso traçar uma estratégia de busca para chegar ao seu objetivo. Mas falamos de uma forma bem direta e abstrata, como isso funciona realmente? Uma árvore de busca contém uma raiz (estado inicial) e com base em sua raiz, ao expandir suas possibilidades ela gera caminho da raiz através dos caminhos possíveis, utilizando uma estratégia de busca até chegar em nosso objetivo (estado final). 
Exemplo do labirinto:  
  <img href=https://user-images.githubusercontent.com/71650069/159827344-bb55e1b4-a587-4a14-844c-a695eab9572c.png>

Neste exemplo temos caminhos numerados para uma melhor compreensão. Vemos que nossa raiz é a entrada (número um) e nosso objetivo é a saída (número onze).  
Pronto, mapeamos nossa árvore de busca, agora podemos ter uma visualização da nossa árvore de busca do nosso labirinto.
<p>
<h2>Nó de busca<h2>
  
<p>
Nós de busca são uma parte do espaço de estado que pertence a árvore de busca e serve para distribuir as possibilidades.
  Podemos analisar isso pensando em uma trilha numa floresta, onde você começa pelo ponto de partida da trilha (estado inicial) e andando um pouco você
  se depara com mais dois caminhos possíveis, neles você precisa escolher um dos caminhos, nesse outro caminho há outras possibilidades e assim 
  suscetivelmente até encontrar o fim da trilha. Esses pontos onde deve-se tomar uma decisão, é considerado o nó, observe a figura a seguir:  
  Nesta figura, o nó é representado por essa forma oval, onde seria os caminhos que devessem ser seguidos até chegar ao fim da trilha.
  </p>
  <h2>Objetivo</h2>
  <p>
  Em um problema de busca, o nosso objetivo pode ser literalmente aquilo que estamos buscando. Seja um local em uma cidade,
  um nome em uma lista ou até mesmo a saída do labirinto.
  </p>
  Ação
<p>
  A ação podemos pensar no que seria possível fazer para encontrar os caminhos.
</p>
