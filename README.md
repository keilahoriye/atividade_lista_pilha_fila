# Atividade Lista, Pilha, Fila

## 1. Lista
Com um código pré-existente de uma lista ligada dinâmica, o objetivo desse exercício é transformá-la em duplamente ligada (no qual cada elemento aponta para seu anterior e para seu sucessor). Algumas considerações da atividade são:
- Se o elemento a ser inserido for o primeiro da lista, o campo ant dele deverá ser NULL.
- O elemento seguinte ao novo deverá ter seu campo ant atualizado para apontar para o novo elemento.
- Esta será uma inserção sem repetição.
- A estrutura não será circular e não terá nó-cabeça.

## 2. Pilha Estática
A atividade pede para que seja implementada uma função para exibir a pilha de forma invertida, que mostra as chaves dos elementos da pilha partindo da base até o topo.

## 3. Fila com nó-cabeça
Considerando a implementação dinâmica em fila, o intuito da atividade é acrescentar um nó-cabeça, para garantir que todos os elementos válidos sempre tenham um anterior e a estrutura nunca fique vazia. A estrutura não será circular nem duplamente ligada. Apenas será adicionado um nó-cabeça (durante a inicialização), e as funções de inserção e exclusão deverão considerar a existência desse elemento, que nunca deverá ser excluído.
