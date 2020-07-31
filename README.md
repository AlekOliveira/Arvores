# Árvores
![img](https://github.com/AlekOliveira/Arvores/blob/master/exemploAvre.png)

### O que são e quais suas funções?

Árvore, no contexto da programação, engenharia de software e ciência da computação, é uma das mais importantes estruturas de dados não lineares. Herda as características das topologia em árvore. Conceitualmente diferente das listas, em que os dados se encontram numa sequência, nas árvores os dados estão dispostos de forma hierárquica, seus elementos se encontram "acima" ou "abaixo" de outros elementos da árvore.

São estruturas eficientes e simples em relação ao tratamento computacional, diferentemente dos grafos. Há inúmeros problemas no mundo real que podem ser modelados e resolvidos através das árvores. Estruturas de pastas de um sistema operacional, interfaces gráficas, bancos de dados, auto-complete de textos e sites da internet são exemplos de aplicações de árvores.

Uma árvore é formada por um conjunto de elementos que armazenam informações chamados nodos (ou nós). Toda a árvore possui o elemento chamado raiz, que possui ligações para outros elementos denominados ramos ou filhos. Estes ramos podem estar ligados a outros elementos que também podem possuir outros ramos. O elemento que não possui ramos é conhecido como nó folha, nó terminal ou nó externo.

Uma terminologia muito utilizada nas estruturas de árvores tem origem das árvores genealógicas. O relacionamento entre nodos é descrito com os termos "pai" (ou "mãe") para os antecessores diretos de um nodo, "filhos" (ou "filhas") para os descendentes diretos e "irmãos" (ou "irmãs") para todos os nodos com mesmo pai.

# Árvores implementadas neste projeto

## Btree
- 

## Btree+
- 

## N-area
- Uma árvore N-ária (também conhecida como k-ária ou k-way) é uma árvore enraizada na qual cada nó não tem mais que **N** filhos. Uma árvore binária é o caso especial em que **N = 2**, e uma árvore ternária é outro caso com **N = 3** que limita seus filhos a três.

![img](https://github.com/AlekOliveira/Arvores/blob/master/exemploNarea.png)

Exemplo de uma N-area com **N = 5**



## Patricia
- A árvore PATRICIA é uma representação compacta de uma Trie onde os nós que teriam apenas um filho são agrupados nos seus antecessores. É comum que as árvores Trie possuam um grupo disperso de chaves, desse modo, muitos nós possuem apenas um descendente. Isto faz com que as Trie tenham um custo grande de espaço. Você pode saber mais sobre Árvores Trie clicando aqui.

Concebido por Donald Morrison, PATRICIA é um algoritmo para realização de buscas em árvores com as chaves dos nós representadas em binário, sem armazenar as chaves nos nós. O nome é um acrônimo de “Practical Algorithm To Retrieve Information Coded In Alphanumeric”, e o método é particularmente útil para tratamento de chaves de tamanho variável extremamente longas, tais como títulos e frases. No caso de pesquisas analíticas, os dados podem tirar proveito deste método desde que as informações sejam armazenadas como cadeias de texto.

![img](https://github.com/AlekOliveira/Arvores/blob/master/exemploPatricia.png)

