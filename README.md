# exercicio_arvores_e_grafos
Exercício de Arvores e Grafos da Semana 02.

##Resultado obtido:
| Algoritmo     | Tamanho | Tempo (ms) | Comparacoes  | Movimentacoes  |
|---------------|---------|------------|--------------|----------------|
| Bubble Sort   | 100     | 0.000      | 4950         | 4950         |
|---------------|---------|------------|--------------|----------------|
| Selection Sort | 100     | 0.000      | 4950         | 50           |
|---------------|---------|------------|--------------|----------------|
| Bubble Sort   | 1000    | 4.000      | 499500       | 499500       |
|---------------|---------|------------|--------------|----------------|
| Selection Sort | 1000    | 2.000      | 499500       | 500          |
|---------------|---------|------------|--------------|----------------|
| Bubble Sort   | 10000   | 484.000    | 49995000     | 49995000     |
|---------------|---------|------------|--------------|----------------|
| Selection Sort | 10000   | 261.000    | 49995000     | 5000         |
|---------------|---------|------------|--------------|----------------|

## Análise e Conclusão
Com base nos testes realizados o algoritmo Selection Sort apresentou o melhor desempenho.

Por que aconteceu?
* Movimentações: A diferença foi gigante. No vetor de 10.000 itens, o Bubble Sort precisou fazer quase 50 milhões de trocas, enquanto o Selection Sort fez apenas 5.000 trocas.
* Tempo: O Selection Sort foi quase duas vezes mais rápido (261ms contra 484ms).

O Selection Sort é muito mais eficiente para vetores que estão totalmente desordenados (invertidos), pois ele economiza operações de escrita na memória.

Como rodar este projeto:
1. Baixe o arquivo `atividade_semana02.c`.
2. Compile em qualquer IDE de C/C++.
3. Execute para ver a tabela de performance.
