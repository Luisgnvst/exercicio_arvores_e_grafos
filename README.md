# 🌳 Exercício — Árvores e Grafos (Semana 02)

Atividade prática da disciplina de Estrutura de Dados — UniEVANGÉLICA.
Implementação e comparação de algoritmos de ordenação em linguagem C.

## 📊 Resultado dos Testes

| Algoritmo      | Tamanho | Tempo (ms) | Comparações  | Movimentações |
|----------------|---------|------------|--------------|---------------|
| Bubble Sort    | 100     | 0.000      | 4950         | 4950          |
| Selection Sort | 100     | 0.000      | 4950         | 50            |
| Bubble Sort    | 1000    | 4.000      | 499500       | 499500        |
| Selection Sort | 1000    | 2.000      | 499500       | 500           |
| Bubble Sort    | 10000   | 484.000    | 49995000     | 49995000      |
| Selection Sort | 10000   | 261.000    | 49995000     | 5000          |

## 📝 Análise e Conclusão

O **Selection Sort** apresentou melhor desempenho para vetores invertidos:

- **Movimentações:** No vetor de 10.000 itens, Bubble Sort fez ~50 milhões de trocas, Selection Sort fez apenas 5.000.
- **Tempo:** Selection Sort foi quase 2x mais rápido (261ms vs 484ms).

## ▶️ Como rodar

1. Baixe o arquivo `atividade_semana02.c`
2. Compile: `gcc atividade_semana02.c -o resultado`
3. Execute: `./resultado`

## 🛠️ Tecnologia

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
