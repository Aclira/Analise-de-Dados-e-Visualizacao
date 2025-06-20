# Desafio de Analise de Dados e Visualização

## Desafio 3: 
Este arquivo tem o objetivo de explicar a execução da etapa 3 do desafio de análise de dados. Essa etapa foi construída no Jupyter Notebook online (Google Colab).


### Etapa 3 – Análise Exploratória com Python + SQL

**Objetivo:** Avaliar sua familiaridade com ferramentas de análise programática e manipulação de dados.

**Tarefas:**

1. **Extração:**
   - Utilize os dados presentes no diretório `/etapa_3/data/`.

2. **Armazenamento e Consulta:**
   - Salve os dados em um **banco SQLite**.
   - Realize consultas utilizando **SQL** diretamente nesse banco.

3. **Análise Exploratória:**
   - Utilize **pandas** e comandos SQL para explorar os dados.
   - Exiba **indicadores e visualizações** com bibliotecas gráficas como matplotlib, seaborn, plotly ou dash.
   - Comente e documente seu código adequadamente para facilitar o entendimento.
   - Fique livre para adicionar quaisquer features ou melhorias.

---

## Instruções para Execução
### 1. Estrutura de Pastas Esperada
Para que o notebook funcione corretamente, é necessário criar uma pasta chamada `etapa3` na raiz do projeto e adicionar nela os 9 arquivos `.csv` utilizados nas etapas anteriores:
etapa3/
###### ├── avaliacoes_pedidos.csv
###### ├── categorias_produtos.csv
###### ├── clientes.csv
###### ├── geolocalizacao.csv
###### ├── itens_pedidos.csv
###### ├── pedidos.csv
###### ├── pedidos_pagamentos.csv
###### ├── produtos.csv
###### └── vendedores.csv

### 2. Execute o notebook na ordem dos blocos, seguindo os passos abaixo:
- Bloco 1: importa todas as bibliotecas necessárias.

- Bloco 2: carrega os arquivos CSV da pasta etapa3/ e cria o banco SQLite (etapa3.db) com todas as tabelas.

- Demais blocos: executam consultas SQL e geram gráficos com os dados prontos.

### 3. Tarefas Realizadas
- Carregamento dos dados em um banco SQLite usando pandas e to_sql.
- Consultas SQL para gerar indicadores como:
  - Total de pedidos por estado
  - Vendas por mês e ano
  - Ticket médio por estado
  - Categorias mais vendidas
  - Distribuição de formas de pagamento
  - Média de avaliações
  - Distribuição de Pedidos por vendedor
  - TOP 5 categorias mais vendidas
  - Visualizações com seaborn, matplotlib e plotly.express.
