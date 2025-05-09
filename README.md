# azure-ml-pipeline
Projeto de machine learning utilizando a plataforma do azure machine learning para prever vendas de sorvete em função do clima.

Durante o desenvolvimento do projeto, foi criada uma pipeline no Azure Machine Learning, que utilizou um cluster de computação (`cpu-cluster`) para rodar um modelo de regressão linear. `inputs/` contém um exemplo com dados de entrada para o modelo.


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

## Links dos Experimentos no Azure Machine Learning

- 🔗 [Pipeline de Regressão Linear no Azure ML](https://ml.azure.com/experiments/id/2507dc71-0cf3-4ac5-8be6-c6aa7e47f850/runs/f39686b9-f7b9-4e4e-820b-2fde9f063e74?wsid=/subscriptions/a958981a-0c43-4251-8922-fb830f08ae8e/resourcegroups/rg-dio-projeto/providers/Microsoft.MachineLearningServices/workspaces/workspace-dio&tid=51ebcf31-5839-412e-83bb-801a2ba78627#)
- 🤖 [Experimento de ML Automatizado](https://ml.azure.com/experiments/id/4a783ecf-27fa-4ad9-877d-26606a1da717/runs/quiet_lion_m86g4xbb12?wsid=/subscriptions/a958981a-0c43-4251-8922-fb830f08ae8e/resourcegroups/rg-dio-projeto/providers/Microsoft.MachineLearningServices/workspaces/workspace-dio&tid=51ebcf31-5839-412e-83bb-801a2ba78627)
> É necessário ter acesso ao workspace do Azure para visualizar os links acima.

