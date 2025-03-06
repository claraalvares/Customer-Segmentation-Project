# Segmentação de Usuários
## Usando RFM Model and K-means Clustering

### Sobre o Projeto

O projeto tem como objetivo identificar os perfis de consumidores de um e-commerce. A partir da análise do histórico de transações, foi realizada a segmentação dos clientes, buscando entender seus comportamentos e preferências. O produto foi o desenvolvimento de diretrizes estratégicas para orientar a equipe de marketing na criação de campanhas mais direcionadas e eficazes.

### Dados

- **Fonte**: `ecommerce_dataset_us.csv`  
- **Composição**:
  - `InvoiceNo`: identificador de pedido  
  - `StockCode`: identificador de item  
  - `Description`: nome de item  
  - `Quantity`: quantidade de itens  
  - `InvoiceDate`: data do pedido  
  - `UnitPrice`: preço por item  
  - `CustomerID`: identificador do cliente
- **Período**: 2018-11-29 a 2019-12-07 (AAAA-MM-DD)

### Método

A segmentação de clientes foi realizada utilizando o modelo **RFM (Recency, Frequency, Monetary)** seguido pela aplicação de **K-means Clustering**. A segmentação RFM ajuda a categorizar os clientes com base em três critérios:
- **Recency** (Recência): Quando o cliente fez a última compra?
- **Frequency** (Frequência): Com que frequência o cliente compra?
- **Monetary** (Monetário): Quanto o cliente gasta?

Após a análise RFM, o K-means Clustering foi utilizado para agrupar os clientes em segmentos distintos.

### Etapas de Trabalho

1. **Análise Exploratória dos Dados**: Inspeção e limpeza dos dados, identificação de padrões e outliers.
2. **Segmentação dos Usuários**: Aplicação do modelo RFM para segmentar os clientes.
3. **Testes de Hipóteses**: Verificação de hipóteses sobre o comportamento dos clientes.
4. **Elaboração de Orientações para o Departamento de Marketing**: Desenvolvimento de estratégias de marketing baseadas nos segmentos identificados.

### Ferramentas Utilizadas

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas**: Manipulação e análise de dados
- **Matplotlib**: Visualização de dados
- **Seaborn**: Visualização de dados
- **Scikit-learn**: Modelagem e clustering (K-means, MinMaxScaler)
- **SciPy**: Estatísticas e testes de hipóteses

### Como Executar o Projeto

1. Clone o repositório;
2. Navegue até o diretório do projeto;
3. Abra o projeto no seu IDE favorito;
4. Instale as dependências;
5. Execute o script principal.
   
### Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

------------

# Customer Segmentation
## Using RFM Model and K-means Clustering

### About the Project

The project aims to identify consumer profiles in an e-commerce platform. Based on transaction history analysis, customer segmentation was performed to understand their behaviors and preferences. The outcome was the development of strategic guidelines to help the marketing team create more targeted and effective campaigns.

### Data

- **Source**: `ecommerce_dataset_us.csv`  
- **Composition**:
  - `InvoiceNo`: order identifier  
  - `StockCode`: item identifier  
  - `Description`: item name  
  - `Quantity`: quantity of items  
  - `InvoiceDate`: order date  
  - `UnitPrice`: price per item  
  - `CustomerID`: customer identifier
- **Period**: 2018-11-29 to 2019-12-07 (YYYY-MM-DD)

### Method

Customer segmentation was performed using the RFM (Recency, Frequency, Monetary) model, followed by the application of K-means Clustering. The RFM segmentation helps categorize customers based on three criteria:
- **Recency**: When did the customer make their last purchase?
- **Frequency**: How often does the customer purchase?
- **Monetary**: How much does the customer spend?

After the RFM analysis, K-means Clustering was used to group customers into distinct segments.

### Work Steps

1. **Exploratory Data Analysis**: Data inspection and cleaning, pattern and outlier identification.
2. **Customer Segmentation**: Applying the RFM model to segment customers.
3. **Hypothesis Testing**: Verifying hypotheses about customer behavior.
4. **Development of Marketing Guidelines**: Creating marketing strategies based on the identified segments.

### Tools Used

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **Seaborn**: Data visualization
- **Scikit-learn**: Modeling and clustering (K-means, MinMaxScaler)
- **SciPy**: Statistics and hypothesis testing

### How to Run the Project

1. Clone the repository;
2. Navigate to the project directory;
3. Open the project in your preferred IDE;
4. Install the dependencies;
5. Run the main script.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

