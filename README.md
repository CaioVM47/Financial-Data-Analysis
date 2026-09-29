# 📊 Global Sales Performance & EDA

Análise Exploratória de Dados (EDA) desenvolvida em Python para avaliar o desempenho financeiro e operacional de vendas globais. O projeto abrange desde o tratamento de dados brutos até a consolidação de indicadores-chave de desempenho (KPIs) estratégicos para suporte à tomada de decisão.

# 🎯 Objetivos da Análise
Inspecionar e Limpar: Identificar dados ausentes, duplicados e inconsistências de tipos de dados no histórico de vendas.

Engenharia de Atributos: Extrair dimensões temporais (Ano, Mês) para análise de sazonalidade e tendências de receita.

Métricas Financeiras (KPIs): Calcular Faturamento Total, Custo Operacional, Lucro Líquido e Margem de Lucro Média.

Segmentação de Negócio: Avaliar a performance de vendas por Região Geográfica, Categoria de Produto e Canal de Venda (Online vs. Offline).

# 🛠️ Tecnologias Utilizadas
Linguagem: Python 3.10+

Manipulação de Dados: Pandas, NumPy

Visualização de Dados: Matplotlib, Seaborn

Ambiente de Desenvolvimento: Jupyter Notebook / Google Colab

# 📈 Principais Insights Obtidos
Desempenho por Região: Identificação de regiões com maior margem de lucro relativa vs. maior volume de receita bruta.

Canais de Distribuição: Comparativo do custo operacional por transação entre os canais de vendas Online e Offline.

Sazonalidade das Vendas: Mapeamento de picos de faturamento ao longo dos meses do ano para identificação de tendências operacionais.

# 🚀 Como Executar o Projeto
Clone o repositório:

Bash
git clone [https://github.com/SEU-USUARIO/global-sales-analysis.git](https://github.com/SEU-USUARIO/global-sales-analysis.git)
cd global-sales-analysis
Crie um ambiente virtual e instale as dependências:

Bash
python -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate
pip install -r requirements.txt
Inicie o Jupyter Notebook:

Bash
jupyter notebook
