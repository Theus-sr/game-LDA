 Dungeon Algorithms

 Sobre o Projeto

Dungeon Algorithms é um jogo de exploração de masmorras desenvolvido com o objetivo de transformar algoritmos clássicos da Ciência da Computação em mecânicas de gameplay interativas.

O jogador controla um explorador que percorre salas e corredores gerados proceduralmente, coletando itens espalhados pelo mapa, como espadas, poções, diamantes e outros tesouros. Porém, o grande diferencial do jogo é que cada decisão importante é baseada em algoritmos amplamente estudados na computação.

Em vez de apenas aprender teoria, o jogador vivencia na prática como esses algoritmos funcionam e como podem ser utilizados para resolver problemas reais de otimização.



 Objetivo do Jogo

Explorar a masmorra da forma mais eficiente possível, coletando o maior número de itens enquanto utiliza algoritmos para planejar rotas, encontrar caminhos e organizar recursos.

Ao longo da partida, o jogador deve equilibrar exploração e estratégia para maximizar sua eficiência.



 Mecânicas Principais

 Coleta de Itens

Itens valiosos aparecem espalhados pelo mapa. Ao se aproximar deles, o jogador pode pressionar **E** para adicioná-los ao inventário.

Cada item possui um valor específico que será utilizado posteriormente para organização e análise.



 BFS (Breadth-First Search)

O algoritmo BFS é responsável pela navegação dentro da masmorra.

Quando o jogador seleciona um ponto do mapa, o BFS calcula automaticamente o menor caminho possível considerando paredes, obstáculos e corredores disponíveis.

O trajeto encontrado é exibido visualmente, permitindo que o jogador se desloque de forma eficiente.

Problema resolvido:

 Como chegar ao destino utilizando o menor número possível de movimentos?



 TSP (Travelling Salesman Problem)

O TSP auxilia no planejamento da coleta de itens.

Ao ativar essa funcionalidade, o jogo calcula a melhor ordem para visitar todos os itens disponíveis e retornar ao ponto inicial, minimizando a distância total percorrida.

O resultado é exibido por meio de uma rota numerada que guia o jogador pela masmorra.

Problema resolvido:

> Qual é a rota mais curta para coletar todos os itens e voltar ao início?



 HeapSort

Após coletar diversos itens, o inventário pode ficar desorganizado.

O algoritmo HeapSort permite ordenar automaticamente todos os itens do mais valioso para o menos valioso utilizando a estrutura de dados Heap.

A reorganização ocorre visualmente em tempo real, permitindo que o jogador acompanhe a execução do algoritmo.

Problema resolvido:*

> Como organizar rapidamente uma grande quantidade de itens por valor?



 Aplicação dos Algoritmos

| Algoritmo | Função no Jogo                              |
| --------- | ------------------------------------------- |
| BFS       | Encontrar o menor caminho entre dois pontos |
| TSP       | Calcular a rota ótima para coleta de itens  |
| HeapSort  | Ordenar o inventário por valor              |



 Diferencial do Projeto

Em muitos jogos, algoritmos trabalham nos bastidores sem que o jogador perceba. Em **Dungeon Algorithms**, os algoritmos são a própria jogabilidade.

Cada ação importante do jogador envolve conceitos clássicos da computação:

* Planejar rotas utilizando otimização.
* Encontrar caminhos mínimos em grafos.
* Organizar dados utilizando estruturas eficientes.

Dessa forma, o projeto une entretenimento e aprendizado, demonstrando aplicações práticas de algoritmos através de uma experiência interativa de exploração.


