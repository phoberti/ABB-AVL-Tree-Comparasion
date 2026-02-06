# Comparação entre Árvore Binária de Busca (ABB) e Árvore AVL

Este repositório é um **fork** do projeto original disponível em:
[https://github.com/EduardoGarzon/ABB-AVL-Tree-Comparasion](https://github.com/EduardoGarzon/ABB-AVL-Tree-Comparasion)

O objetivo deste fork é registrar minha participação no desenvolvimento do projeto, bem como manter uma versão vinculada ao meu perfil para fins acadêmicos e profissionais.

---

## Sobre o Projeto

O projeto realiza uma **comparação prática entre duas estruturas de dados**:

* Árvore Binária de Busca (ABB)
* Árvore AVL (árvore binária de busca balanceada)

A proposta é analisar e comparar o desempenho das duas estruturas em operações como:

* Inserção de elementos
* Busca de elementos
* Número de comparações realizadas
* Tempo de execução

O foco principal é evidenciar as diferenças de desempenho entre uma árvore não balanceada (ABB) e uma árvore auto-balanceada (AVL).

---

## Conceitos Envolvidos

### Árvore Binária de Busca (ABB)

Estrutura de dados em que:

* Cada nó possui no máximo dois filhos
* Os valores menores ficam à esquerda
* Os valores maiores ficam à direita

No pior caso, pode se degenerar em uma lista encadeada, resultando em complexidade O(n).

---

### Árvore AVL

Uma árvore AVL é uma ABB que mantém balanceamento automático após inserções e remoções.

A diferença de altura entre subárvores esquerda e direita é no máximo 1, garantindo complexidade O(log n) no pior caso para inserção e busca.

---

## Objetivo da Comparação

O projeto permite observar na prática:

* Como a ordem de inserção influencia a ABB
* Como o balanceamento mantém o desempenho da AVL
* A diferença real de custo computacional entre as duas estruturas

