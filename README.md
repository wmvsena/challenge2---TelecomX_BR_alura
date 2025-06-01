# Análise de Evasão de Clientes (Churn) - TelecomX

## Visão Geral

O objetivo desta análise é explorar o dataset da empresa de telecomunicações TelecomX_BR  para entender os fatores que contribuem para a evasão de clientes (Churn). A evasão de clientes, ou *churn*, é um problema crítico no setor, pois a perda de clientes impacta diretamente a receita e a sustentabilidade do negócio. Esta análise busca identificar padrões e variáveis que influenciam o churn, fornecendo insights acionáveis para estratégias de retenção de clientes.

O dataset contém informações sobre clientes, incluindo características demográficas (gênero, idade, estado civil), serviços contratados (telefone, internet, etc.), tipo de contrato, método de pagamento e informações financeiras (cobranças mensais e totais). A variável alvo é `Churn`, que indica se o cliente cancelou o serviço ("yes") ou não ("no").

O projeto é implementado em um Jupyter Notebook (`Relatorio_Analise_Churn.ipynb`), que inclui:
- Limpeza e tratamento de dados.
- Análise exploratória com visualizações (gráficos de barras, histogramas, boxplots e heatmap de correlação).
- Análise de correlação entre variáveis, como `Contas Diárias` e quantidade de serviços contratados.
- Conclusões, insights e recomendações para reduzir o churn.

## Estrutura do Projeto

- **`Relatorio_Analise_Churn.ipynb`**: Notebook principal contendo o relatório completo com introdução, limpeza de dados, análise exploratória, análise de correlação, conclusões e recomendações.
- **`TelecomX_Data_Conta_diarias.csv`**: Dataset com informações sobre clientes, serviços contratados, contratos, pagamentos e churn.
- **`README.md`**: Este arquivo, com instruções e visão geral do projeto.

## Pré-requisitos
Para executar o projeto, você precisa das seguintes dependências:

- Python 3.8 ou superior
- Bibliotecas Python:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `IPython`
