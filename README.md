# Desafio Técnico - Programa Trainee triggo.ai 2025

Este repositório contém a solução para o desafio técnico do processo seletivo para o **Programa Trainee de Excelência em Engenharia de Dados e DataOps 2025** da [triggo.ai](https://triggo.ai).

## 🧠 Descrição do Projeto

O objetivo do desafio é realizar uma análise exploratória dos dados (EDA) utilizando o **Brazilian E-commerce Public Dataset by Olist**, disponível no Kaggle, com foco na extração de **insights estratégicos** para um negócio de e-commerce.

Neste cenário simulado, atuo como Engenheiro de Dados Júnior em uma empresa brasileira de e-commerce, utilizando **Python, SQL e conhecimentos de banco de dados** para entregar valor através de dados.

## 📦 Descrição dos Datasets

- **Fonte**: [Brazilian E-commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
- **Período**: 2016 a 2018  
- **Tamanho**: ~100.000 pedidos  
- **Dados disponíveis**:  
  - **olist_customers_dataset.csv** — informações dos clientes (ID, localização, etc.)  
  - **olist_order_items_dataset.csv** — detalhes dos itens em cada pedido (produto, quantidade, preço)  
  - **olist_order_payments_dataset.csv** — informações sobre pagamentos (método, valor, parcelas)  
  - **olist_order_reviews_dataset.csv** — avaliações feitas pelos clientes (nota, comentário)  
  - **olist_orders_dataset.csv** — dados gerais dos pedidos (status, datas)  
  - **olist_products_dataset.csv** — informações dos produtos (categoria, descrição)  
  - **olist_sellers_dataset.csv** — dados dos vendedores (localização, ID)  
  - **product_category_name_translation.csv** — tradução dos nomes das categorias dos produtos  
  - **olist_geolocation_dataset.csv** — dados geográficos (latitude, longitude de clientes e vendedores)  

## ⚙️ Tecnologias Utilizadas

- Python 3.x  
- Jupyter Notebook  
- Pandas / NumPy / Matplotlib / Seaborn / Folium / Geopy / Unidecode / ipywidgets  
- Visual Studio Code  

## 🗂 Estrutura do Repositório

```plaintext
📁 triggoai-2025-olist-ecommerce-analysis
│
├── 📄 README.md                        # Documentação do projeto
├── 📄 requirements.txt                 # Lista de dependências do projeto
├── 📊 olist_ecommerce_analysis.ipynb  # Notebook com a análise exploratória
├── 📁 data                            # Dados originais do dataset Olist
│   ├── olist_customers_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   └── product_category_name_translation.csv
└── 📁 outputs                         # Resultados e visualizações
    └── mapa_vendas.html
