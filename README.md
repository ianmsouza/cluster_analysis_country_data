# Projeto da disciplina de algoritmos de inteligência artificial para clusterização - 24E4_2

## Índice
- [Sobre](#sobre)
- [Pré-requisitos](#pré-requisitos)
- [Objetivo](#objetivo)

## Sobre
Aprendizagem não supervisionada em dados de países utilizando KMeans, KMedoid, HClust e DBScan.

## Pré-requisitos
Lista de pré-requisitos necessários para rodar o projeto:
- [Conda](https://www.anaconda.com/download)
- [Git](https://git-scm.com/downloads)
- [VsCode](https://code.visualstudio.com/download)
- Jupyter Notebook v7.0.8
- Python v3.12.4
- Anaconda v24.9.2 (Ambiente virtual chamado "infnet-24E4-2")

Para usar a biblioteca [scikit-learn-extra], precisa instalar a extenção 
- [Microsoft C++ Build Tools](https://visualstudio.microsoft.com/pt-br/visual-cpp-build-tools/)

## Objetivo
Este projeto tem como objetivo categorizar países com base em dados socioeconômicos e de saúde para identificar padrões de desenvolvimento. O trabalho é dividido em quatro partes principais:

1. **Infraestrutura:** Configuração de ambiente Python local em Jupyter Notebook com dependências específicas registradas em um arquivo requirements.txt, garantindo reprodutibilidade do código.
2. **Escolha de Base de Dados:** Seleção e análise exploratória de uma base de dados socioeconômicos e de saúde dos países, obtida do Kaggle, preparando-a para as tarefas de clusterização.
3. **Clusterização:** Agrupamento dos países usando métodos de K-Médias e Clusterização Hierárquica, com análise comparativa dos resultados.
4. **Escolha de Algoritmos:** Investigação dos métodos de clusterização K-Médias e DBScan, abordando suas características, convergência e sensibilidade a outliers.

Este trabalho visa aplicar técnicas de aprendizado não supervisionado para gerar insights sobre o desenvolvimento global e auxiliar em decisões estratégicas de alocação de recursos.
