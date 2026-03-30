# 📚 Miniguia de Estudos: Estrutura de Dados e Algoritmos com NotebookLM

Este repositório contém o resultado de um projeto de aprendizagem ativa desenvolvido para o desafio da **DIO**, utilizando o **NotebookLM** como ferramenta de curadoria e síntese de conhecimento sobre Estrutura de Dados e Algoritmos.

---

## 🎯 Contexto e Objetivos

O objetivo deste caderno temático é consolidar os fundamentos de **Estrutura de Dados e Algoritmos (DSA)**, focando em como organizar informações de forma eficiente e como processá-las utilizando lógica algorítmica. 

**Objetivos de estudo:**
* Compreender a diferença entre estruturas lineares (Arrays, Listas) e não-lineares (Árvores, Grafos).
* Dominar a análise de complexidade de tempo e espaço (Notação Big O).
* Criar um guia de consulta rápida para revisão técnica.

---

## 📑 Curadoria de Fontes

Para alimentar o NotebookLM, selecionei as seguintes fontes de alta qualidade (Open Source):

1.  **Introduction to Algorithms (MIT OpenCourseWare)** - Notas de aula sobre fundamentos de algoritmos.
2.  **Algorithm Design Canvas** - Documento PDF sobre estratégias de resolução de problemas.
3.  **Data Structures and Algorithms in Python (Summary)** - Resumo técnico focado em implementação.
4.  **Big O Cheat Sheet** - Guia visual sobre complexidade de algoritmos.

---

## 🧠 Engenharia de Prompts

Nesta etapa, documentei o processo de "conversa" com a IA para extrair o melhor conteúdo possível.

### Prompts Testados
| Ordem | Prompt Utilizado | Objetivo | Resultado/Feedback |
| :--- | :--- | :--- | :--- |
| 1 | "Resuma o que é Big O." | Visão Geral | Muito genérico. A IA não detalhou a diferença entre O(n) e O(log n). |
| 2 | "Com base nas fontes, crie uma tabela comparativa entre Array e Linked List focando em inserção e busca." | Comparação Técnica | **Excelente.** A IA utilizou os dados específicos dos PDFs para montar a tabela. |
| 3 | "Explique o algoritmo QuickSort para uma criança de 10 anos usando uma analogia com cartas." | Simplificação | Ajudou a fixar o conceito lógico antes de partir para o código. |

### 🛠 Troubleshooting (Desafios)
* **Dificuldade:** O NotebookLM inicialmente confundiu implementações de linguagens diferentes (Java vs Python).
* **Solução:** Ajustei o prompt especificando: *"Considere apenas a implementação em Python conforme o documento 3"*.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado: O Coração de DSA
As estruturas de dados são recipientes para armazenar dados, enquanto algoritmos são o passo a passo para manipular esses dados. 



* **Estruturas Lineares:** Arrays, Listas Ligadas, Pilhas (LIFO) e Filas (FIFO).
* **Estruturas Não-Lineares:** Árvores (Trees) e Grafos (Graphs), essenciais para representar hierarquias e redes sociais.

### 2. Glossário de Conceitos
* **Big O Notation:** Medida de quão rápido o tempo de execução cresce conforme o volume de dados aumenta.
* **Recursão:** Quando uma função chama a si mesma para resolver subproblemas menores.
* **Hash Table:** Estrutura que utiliza uma função hash para mapear chaves a valores, permitindo busca em tempo constante $O(1)$ no melhor caso.

### 3. Prompts Reutilizáveis para Revisão
* *"Atue como um entrevistador técnico e me faça 3 perguntas difíceis sobre Árvores Binárias baseadas nestes documentos."*
* *"Explique o pior cenário (Worst Case) para o algoritmo de busca binária."*
* *"Crie um roteiro de estudos de 5 dias para revisar Grafos e Algoritmo de Dijkstra."*

---

## 🛠️ Tecnologias Utilizadas
* [NotebookLM](https://notebooklm.google.com/)
* [GitHub](https://github.com/)
* IA Generativa para síntese de textos.

---
Feito por Luiz Eduardo no Desafio do bootcamp da CI&T - Do Prompt ao Agente da DIO.
