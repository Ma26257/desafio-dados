📊 Análise de Vendas 

🎯 Propósito da Análise

O objetivo deste projeto é realizar uma análise exploratória das vendas da Alura Store, identificando padrões de comportamento de clientes, desempenho de produtos, custos de frete e tendências gerais de faturamento. A análise permite:

Identificar os produtos mais e menos vendidos por loja.

Avaliar a rentabilidade e eficiência logística através do custo médio de frete.

Detectar padrões de compras ao longo do tempo.

Gerar insights que apoiem decisões estratégicas para aumento de vendas e otimização de processos.

alura_store/
│
├─ notebooks/
│   └─ analise_alura_store.ipynb       # Notebook principal com todas as análises
│
├─ data/
│   ├─ vendas.csv                      # Dados de vendas da loja
│   └─ clientes.csv                    # Dados dos clientes (se houver)
│
├─ images/
│   └─ graficos/                       # Gráficos gerados durante a análise
│
├─ README.md                           # Este arquivo
└─ requirements.txt                    # Dependências do projeto


📈 Exemplos de Gráficos e Insights Obtidos
1. Faturamento por Loja

Insight: Identificação das lojas com maior desempenho em vendas.

2. Produtos Mais e Menos Vendidos

Insight: Produtos que se destacam em cada loja e produtos que precisam de atenção.

3. Custo Médio de Frete

Insight: Avaliação da eficiência logística e áreas para otimização.

4. Tendência de Vendas ao Longo do Tempo

Insight: Períodos de maior movimentação e sazonalidade.

🚀 Como Executar o Notebook no Google Colab

Abra o Google Colab: https://colab.research.google.com/

Faça upload do notebook analise_alura_store.ipynb ou abra diretamente do GitHub:

Vá em Arquivo → Abrir notebook → GitHub e cole o link do repositório.

Certifique-se de que os arquivos CSV estão acessíveis no Colab:

from google.colab import files
uploaded = files.upload()  # Faça upload de vendas.csv e clientes.csv


Instale dependências (se necessário):

!pip install pandas matplotlib seaborn


Execute as células do notebook para gerar análises e gráficos.

🛠 Tecnologias Utilizadas

Python

Pandas

Matplotlib / Seaborn

Jupyter Notebook / Google Colab
