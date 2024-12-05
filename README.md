# Segmentação de Usuários / Customer Segmentation
## Using RFM Model and K-means Clustering**

### Sobre o Projeto

O projeto tem como objetivo identificar os perfis de consumidores da Everything Plus, uma loja online de utensílios domésticos. A partir da análise do histórico de transações, será realizada a segmentação dos clientes, buscando entender seus comportamentos e preferências. Como resultado, serão desenvolvidas diretrizes estratégicas para orientar a equipe de marketing na criação de campanhas mais direcionadas e eficazes.

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

A segmentação de clientes será realizada utilizando o modelo **RFM (Recency, Frequency, Monetary)** seguido pela aplicação de **K-means Clustering**. A segmentação RFM ajuda a categorizar os clientes com base em três critérios:
- **Recency** (Recência): Quando o cliente fez a última compra?
- **Frequency** (Frequência): Com que frequência o cliente compra?
- **Monetary** (Monetário): Quanto o cliente gasta?

Após a análise RFM, o K-means Clustering é utilizado para agrupar os clientes em segmentos distintos.

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
