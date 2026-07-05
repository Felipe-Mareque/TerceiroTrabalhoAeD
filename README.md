
# Trabalho – LeetCode 775: Global and Local Inversions

**Nome:** Felipe Reichow Mareque
**Turma:** M1

## Observação

**Não consegui terminar a atividade durante a aula.** Finalizei a implementação posteriormente para concluir o exercício e entender melhor a utilização de Árvores AVL.

## Descrição

Este trabalho consiste na resolução do problema **LeetCode 775 – Global and Local Inversions** utilizando uma **Árvore AVL**.

O problema fornece um vetor `nums`, que é uma permutação dos números de `0` até `n - 1`, e pede verificar se a quantidade de **inversões globais** é igual à quantidade de **inversões locais**.

* **Inversão global:** existe um par `(i, j)` com `i < j` e `nums[i] > nums[j]`.
* **Inversão local:** existe um índice `i` em que `nums[i] > nums[i + 1]`.

Se as duas quantidades forem iguais, a função retorna `true`; caso contrário, retorna `false`.

## Solução

Na solução foi utilizada uma Árvore AVL com o campo `tamanho` em cada nó para permitir contar, de forma eficiente, quantos elementos já inseridos são maiores que o elemento atual.

As inversões locais são contadas percorrendo o vetor apenas uma vez e comparando elementos vizinhos.

## Complexidade

* **Tempo:** **O(n log n)**.
* **Espaço:** **O(n)**.

Apesar de existir uma solução em **O(n)** para este problema, o objetivo desta atividade foi resolver o exercício utilizando Árvores AVL.


<img width="1349" height="571" alt="image" src="https://github.com/user-attachments/assets/6571741a-063c-4df2-bc72-08c0d79cbd78" />




<img width="1360" height="490" alt="image" src="https://github.com/user-attachments/assets/529ed062-03bc-4b88-9fc5-2dd466529916" />



