# azure-ml-pipeline
Projeto de machine learning utilizando a plataforma do azure machine learning para prever vendas de sorvete em função do clima.

Durante o desenvolvimento do projeto, foi criada uma pipeline no Azure Machine Learning, que utilizou um cluster de computação (`cpu-cluster`) para rodar um modelo de regressão linear.

O processo incluiu:

- Criação do ambiente Conda e instalação dos pacotes necessários (`mlflow`, `azureml-mlflow`);
- Criação e configuração do cluster de cálculo;
- Desenvolvimento e execução do pipeline;
- Análise de sentenças com IA;
- Registro do modelo e avaliação dos resultados.

## Insights obtidos

- Entendi como funciona o fluxo de trabalho completo no Azure ML Studio, desde a criação do workspace até a execução de pipelines.
- Aprendi a lidar com erros comuns relacionados a clusters e permissões.
- Vi na prática como estruturar um pipeline reutilizável com componentes modulares.

## Possibilidades percebidas

- É possível automatizar todo o ciclo de vida de um projeto de Machine Learning com Azure ML.
- A modularização via Designer facilita muito a reutilização e a escalabilidade de soluções.
- Com o registro de modelos e rastreamento de experimentos (MLflow), fica mais simples acompanhar versões e métricas de desempenho.
