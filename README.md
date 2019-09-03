# Selection-Sort-e-Insertion-Sort

Insertion Sort 

 “Insertion sort é um algoritmo de ordenação simples que constrói um vetor (ou lista) final ordenando um item de cada vez. É menos eficiente em grandes listas que outros algoritmos como, por exemplo o quicksort, heapsort ou merge sort. Algumas vantagens são: implementação simples, é eficiente para pequenos conjuntos de dados, é mais eficiente na prática do que outros algoritmos como selection sort e bubble sort.”

Bom o método Insertion Sort tem um funcionamento bem simples de se entender. Ele consiste em percorrer o vetor da esquerda para a direita, pegando o valor que está passando, e testando com todos os valores que estão a sua esquerda se são maiores que ele. Assim sendo ele vai ordenando os valores do vetor da esquerda para a direita.

Como vemos no código acima a função insertion sort percorre o vetor da esquerda para a direita ordenando a posição que está passando no “for” em relação a todos os outros valores a sua esquerda. Ou seja se o valor da posição que está passando é menor que o valor da posição anterior ele faz a troca.
Vemos também que não é um método muito eficiente, pois ocorre um grande número de trocas, o que demoraria uma eternidade com uma quantidade maior de dados.

Selection Sort 

 “O selection sort (do inglês, ordenação por seleção) é um algoritmo de ordenação  baseado em se passar sempre o menor valor do vetor para a primeira posição (ou o maior dependendo da ordem requerida), depois o de segundo menor valor para a segunda posição, e assim é feito sucessivamente com os (n-1) elementos restantes, até os últimos dois elementos.”

Este método de ordenação de dados consiste em percorrer todo o vetor procurando qual é o menor valor, depois coloca o menor valor encontrado na posição que está passando e vai para a próxima posição, cada vez que ele percorre o vetor ele testa uma posição a menos, a qual ja está ordenada.
No código, a função principal cria o vetor, preenche ele aleatóriamente e mostra ele na tela, depois chama a função de ordenação, ela ordena os dados, e a função principal mostra eles ordenados na tela.
