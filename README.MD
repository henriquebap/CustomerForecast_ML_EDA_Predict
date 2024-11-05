# Projeto de Previsão de Comportamento do Cliente

## Visão Geral

Este projeto visa desenvolver um sistema robusto para prever o comportamento do cliente, como padrões de compra e tendências de vendas futuras, utilizando técnicas de aprendizado de máquina. As insights geradas por este modelo podem ser utilizadas para aprimorar decisões de negócios, otimizar estratégias de marketing e melhorar a satisfação geral do cliente.

## Objetivos

- Construir um modelo preditivo para prever comportamentos do cliente como frequência de compra, valor do pedido e produtos preferidos.
- Utilizar técnicas avançadas de aprendizado de máquina para analisar dados do cliente.
- Implantar o modelo mais preciso para facilitar previsões em tempo real.

## Fluxo do Processo

1. **Coleta e Exploração de Dados**: Utilizamos diversos conjuntos de dados contendo informações cruciais sobre clientes, pedidos, pagamentos, avaliações, produtos, vendedores e dados de geolocalização.
2. **Pré-processamento de Dados**: Implementamos etapas de pré-processamento para garantir dados limpos e utilizáveis, incluindo tratamento de valores ausentes, normalização e codificação de características categóricas.
3. **Engenharia de Características**: Criamos novas características baseadas na lógica de negócios para enriquecer o conjunto de dados e melhorar a precisão do modelo.
4. **Seleção e Treinamento do Modelo**: Aplicamos múltiplos algoritmos de aprendizado de máquina e deep learning para treinar modelos preditivos. Os modelos foram avaliados com base em métricas de desempenho para identificar a melhor abordagem.
5. **Avaliação do Modelo**: Após o treinamento, cada modelo foi avaliado usando várias métricas de avaliação, como acurácia, precisão, recall e F1-score.

## Conjuntos de Dados

O projeto utiliza os seguintes conjuntos de dados:

1. Conjunto de Dados de Clientes
2. Conjunto de Dados de Geolocalização
3. Conjunto de Dados de Itens de Pedidos
4. Conjunto de Dados de Pagamentos de Pedidos
5. Conjunto de Dados de Avaliações de Pedidos
6. Conjunto de Dados de Pedidos
7. Conjunto de Dados de Produtos
8. Conjunto de Dados de Vendedores
9. Conjunto de Dados de Tradução de Nomes de Categorias de Produtos

## Modelos Implementados

- Regressão Logística
- Random Forest
- XGBoost

## Resultados

Os modelos de ensemble (Random Forest e XGBoost) demonstraram desempenho superior em comparação com a Regressão Logística na tarefa de classificação de vendas acima ou abaixo da mediana.

### Gráfico de Desempenho dos Modelo

![RandomForestROC](https://github.com/henriquebap/CustomerForecast_ML_EDA_Predict/blob/main/images/RandomForestROC.png)

### Melhor Modelo e Avaliação

O modelo Random Forest foi selecionado como o melhor modelo para este projeto. Aqui estão suas métricas de avaliação:

- F1-Score: 1.0
- Área sob a curva ROC: 1.0
- Matriz de Confusão: (array([[3, 0],
  [0, 2]]),

## Próximos Passos

- Implantar o modelo na nuvem (por exemplo, Azure ML) para uso em produção.
- Desenvolver uma interface de usuário para facilitar o uso do modelo por não-técnicos.
- Continuar refinando o modelo com dados atualizados e feedback dos usuários.

## Instalação e Execução

### Pré-requisitos

Certifique-se de ter as seguintes dependências instaladas:

- Python 3.7 ou superior
- Jupyter Notebook
- Git (opcional para clonar o repositório)
- Bibliotecas Python listadas no arquivo `requirements.txt`

### Passos de Instalação

1. Clone este repositório (ou faça o download diretamente):

```bash
git clone https://github.com/henriquebap/CustomerForecast_ML_EDA_Predict.git
cd CustomerForecast_ML_EDA_Predict
```

2. Instale as bibliotecas necessárias:

```
pip install -r requirements.txt
```

### Executando o Projeto

1. Inicie o Jupyter Notebook:

```
jupyter notebook
```

2. Abra o arquivo `.ipynb` do notebook principal na interface do Jupyter.
3. Siga as instruções dentro do notebook para carregar o dataset, realizar a análise exploratória e executar o modelo de previsão de clientes.

## Como Usar

1. Clone este repositório
2. Instale as dependências listadas em `requirements.txt`
3. Execute o notebook Jupyter para treinar e avaliar os modelos
4. Use o modelo salvo (`model_rf_class.pkl`) para fazer previsões em novos dados

## Requisitos

Os requisitos do projeto estão listados no arquivo `requirements.txt`. Para instalar todas as dependências necessárias, execute:

```
pip install -r requirements.txt
```

## Participantes do Grupo

- 98469 - Pedro Duarte Farias
- 98413 - Matheus Castro
- 551322 - Gabriel Caverzan
- 551582 - Leonardo Valencio Dourado
- 97796 - Henrique Oliveira Baptista

## Contribuições

Contribuições são bem-vindas! Por favor, abra uma issue para discutir mudanças maiores antes de submeter um pull request.

## Agradecimentos

Agradecemos à Olist por disponibilizar o dataset utilizado neste projeto. O conjunto de dados original pode ser encontrado em:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Autor do Notebook

Este notebook foi desenvolvido por Henrique Baptista.

[Link do Repositorio do Projeto](https://github.com/henriquebap/CustomerForecast_ML_EDA_Predict)

### Contato

- **LinkedIn**: [Henrique Baptista](https://www.linkedin.com/in/henrique-baptista777/)
- **GitHub**: [henriquebap](https://github.com/henriquebap)
- **Email**: [henriquebaptista2003@gmail.com](mailto:henriquebaptista2003@gmail.com)

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
