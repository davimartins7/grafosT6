# Trabalho Prático 6 - Resolução de Problemas com Grafos

## Isomorfismo em Árvores com Codificação Canônica

**Disciplina:** Resolução de Problemas com Grafos  
**Professor:** Ricardo Carubbi  

---

## Sobre o Projeto

Este projeto tem como objetivo verificar se **duas árvores não direcionadas são isomorfas**, ou seja, se possuem a mesma estrutura, mesmo que os vértices possuam rótulos diferentes.

A solução foi desenvolvida em **Python**, utilizando a estrutura principal de grafos no padrão **algs4**, conforme solicitado no enunciado da atividade.

O algoritmo implementado utiliza a técnica de **codificação canônica de árvores**, garantindo que a comparação seja feita de forma estrutural, correta e independente da ordem de leitura das arestas ou da numeração dos vértices.

---

## Conceitos Aplicados

- Grafos não direcionados
- Árvores
- Busca em largura (BFS)
- Validação de árvores
- Centro de árvores
- Enraizamento de árvores
- Recursividade
- Ordenação lexicográfica
- Codificação canônica
- Isomorfismo entre árvores

---

## Funcionamento do Programa

O programa executa as seguintes etapas:

1. Leitura de dois arquivos `.txt` no formato **algs4**
2. Construção dos grafos utilizando a classe `Graph`
3. Exibição da lista de adjacência de cada entrada
4. Validação se cada grafo representa uma árvore válida
5. Identificação do(s) centro(s) da árvore
6. Geração da codificação canônica
7. Comparação final entre as duas árvores
8. Exibição do resultado final:
   - Árvores Isomorfas
   - Árvores Não Isomorfas

---

## Técnica Utilizada

A técnica principal consiste em:

localizar o centro da árvore;
enraizar a árvore nesse centro;
codificar recursivamente cada subárvore;
ordenar lexicograficamente os códigos dos filhos;
gerar uma representação textual única da estrutura.

Se duas árvores produzirem a mesma codificação canônica, conclui-se que são isomorfas.

Vídeo Explicativo

Link do vídeo: https://youtu.be/-vmZax6riv8 

Autores:
Davi Martins
Isaac Coelho
Paulo Afonso
