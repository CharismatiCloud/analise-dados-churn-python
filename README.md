# Análise de Cancelamento de Clientes (Churn Analysis) 📊📉

Este projeto analisa uma base de dados com mais de 50 mil clientes para identificar os principais padrões e motivos de cancelamento de serviços. O objetivo é extrair insights estratégicos para reduzir a taxa de churn e aumentar a retenção de clientes.

## 📁 Estrutura do Projeto
- `main.ipynb`: Contendo todo o passo a passo da análise, desde a importação até a geração de gráficos.
- `cancelamentos.csv`: (Opcional) Base de dados utilizada para a análise.

## 🛠️ Tecnologias e Bibliotecas
- **Python 3**
- **Pandas**: Para tratamento, limpeza e manipulação dos dados brutos.
- **Plotly**: Para criação de gráficos interativos que facilitam a visualização dos insights.

## 🔍 Etapas da Análise
1. **Importação e Limpeza**: Remoção de colunas desnecessárias (como IDs de clientes) e tratamento de valores nulos para evitar distorções estatísticas.
2. **Análise de Churn Global**: Identificação da porcentagem de clientes que cancelaram o serviço.
3. **Análise por Categoria**: Cruzamento da taxa de cancelamento com outras variáveis (tipo de contrato, dias de atraso, score de crédito, etc).
4. **Geração de Insights**: Identificação de gargalos operacionais e comportamentais.

## 💡 Principais Insights Obtidos
Através dos gráficos gerados, foi possível identificar:
- **Contratos Mensais**: Clientes com contrato mensal possuem uma taxa de cancelamento drasticamente superior aos demais.
- **Atrasos no Pagamento**: Clientes com mais de 20 dias de atraso sistematicamente cancelam o serviço.
- **Tipo de Serviço**: Identificação de planos ou serviços específicos com baixa adesão ou alta taxa de reclamação.

## ⚙️ Como Executar
1. Instale o Jupyter Notebook ou utilize o VS Code com a extensão Jupyter.
2. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas plotly nbformat
3. Execute as células do arquivo main.ipynb em sequência.

<img width="924" height="450" alt="newplot" src="https://github.com/user-attachments/assets/f4b09726-282d-49ea-9167-164a47615799" />
<img width="924" height="450" alt="newplot" src="https://github.com/user-attachments/assets/ccb91b02-bef4-4d85-a749-18b9caf67079" />
<img width="924" height="450" alt="newplot" src="https://github.com/user-attachments/assets/4d719918-ef45-4856-ba31-19ed86ef7ec8" />

