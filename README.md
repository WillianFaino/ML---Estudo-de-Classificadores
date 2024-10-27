# Classificação de Dados de Fígado

Este repositório contém um código Python que utiliza várias técnicas de classificação para analisar um conjunto de dados sobre fígado. O objetivo é prever a classe de um paciente com base em suas características médicas.

## Tecnologias Utilizadas

- **Python 3.x**
- **Pandas**: para manipulação e análise de dados.
- **Scikit-learn**: para implementação de algoritmos de aprendizado de máquina.
- **Matplotlib**: para visualização de dados.
- **SciPy**: para testes estatísticos.

## Conjunto de Dados

O conjunto de dados é carregado a partir de um arquivo CSV localizado em `H:\Downloads\Liver.csv`. Certifique-se de que o caminho esteja correto e que o arquivo esteja disponível.

## Funcionalidades

- Leitura e pré-processamento dos dados.
- Divisão dos dados em conjuntos de treinamento e teste.
- Implementação de diversos algoritmos de classificação, incluindo:
  - MLP Classifier (Rede Neural)
  - K-Nearest Neighbors (KNN)
  - Decision Tree Classifier (Árvore de Decisão)
  - Naive Bayes Classifier
  - Support Vector Machine (SVM)
- Avaliação do desempenho de cada modelo utilizando métricas como precisão, recall e f1-score.
- Realização de testes estatísticos para comparar o desempenho dos modelos.

## Como Executar

1. Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalar as dependências usando o seguinte comando:

   ```bash
   pip install pandas scikit-learn matplotlib scipy
   ```

2. Atualize o caminho para o arquivo CSV na linha:

  ```python
  dados = pd.read_csv('H:\Downloads\Liver.csv')
  ```

3. Execute o script python:
  ```bash
  python seu_script.py
  ```

## Resultados
O código imprime a precisão média de cada algoritmo após realizar várias execuções, além de relatórios de classificação e resultados de testes estatísticos (Kruskal e Mann-Whitney).

## Licença
Este projeto está sob a licença MIT.

