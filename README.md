# Motor-de-Intelig-ncia-de-Varejo

## Objetivo

Desenvolver uma Prova de Conceito (PoC) para o backend analítico de um grande e-commerce utilizando Programação Orientada a Objetos, Big Data, Machine Learning, NLP e Sistemas de Recomendação.

## Tecnologias Utilizadas

* Python
* PySpark
* Pandas
* Scikit-Learn
* NetworkX
* WordCloud
* Matplotlib

## Estrutura do Projeto

* data_manager.py: ingestão e gerenciamento dos dados
* models.py: classe abstrata ModeloAnalitico
* churn_model.py: previsão de abandono de carrinho
* nlp_analyzer.py: processamento de linguagem natural
* recommender.py: motor de recomendação baseado em grafos

## Execução

```bash
pip install -r requirements.txt

python main.py
```

## Funcionalidades

### Etapa 1 - Big Data

Carga e processamento de 1 milhão de registros utilizando PySpark.

### Etapa 2 - Machine Learning

Treinamento de uma Árvore de Decisão para prever abandono de carrinho.

Variáveis utilizadas:

* idade
* tempo_navegacao
* valor_carrinho
* quantidade_visitas

### Etapa 3 - NLP

Extração de palavras relevantes dos comentários dos clientes e geração de Word Cloud.

### Etapa 4 - Sistema de Recomendação

Construção de um grafo de produtos comprados em conjunto utilizando NetworkX.

## Resultados

O sistema gera automaticamente:

* Matriz de Confusão
* Word Cloud
* Grafo de Recomendações
