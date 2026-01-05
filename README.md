## Análise de Funil de Vendas Digital
SQL | Python | Power BI

## 📌 Objetivo
Este projeto tem como objetivo analisar um funil de vendas digital, desde a primeira interação do usuário até a conversão em compra, identificando taxas de conversão, pontos de abandono e comportamento de receita.

O foco é demonstrar um fluxo completo de análise de dados, contemplando extração, preparação, modelagem e visualização dos dados.

## 🧠 Contexto de Negócio
A análise do funil digital é essencial para:

- Entender o comportamento dos visitantes
- Identificar gargalos entre as etapas do funil
- Otimizar fontes de tráfego
- Avaliar eficiência de conversão e monetização


## 🗄️ Fonte dos Dados
Dataset: Google Analytics Sample Dataset
Origem: Google BigQuery
Período: Um trimestre
Tipo de dados: Interações digitais e dados de e-commerce
🔧 Ferramentas e Tecnologias
SQL – Extração e seleção dos dados (Google BigQuery)
Python (Pandas) – Limpeza, preparação e transformação dos dados
Power BI – Modelagem de dados, DAX e visualização em dashboard
🔄 Pipeline de Dados
Extração dos Dados (SQL)

Seleção de campos relevantes relacionados a:
Visitantes
Origem e mídia do tráfego
Etapas do funil
Transações e receita
Estruturação do dataset para análise
Limpeza e Preparação (Python)

Tratamento de valores nulos
Padronização de tipos de dados
Otimização de uso de memória
Categorização das fontes de tráfego
Geração do dataset analítico final
Modelagem e Visualização (Power BI)

- Criação de colunas calculadas e medidas em DAX
- Construção de métricas de funil e KPIs
- Desenvolvimento de dashboard executivo
  
📊 Principais Métricas e KPIs:
Total de Visitas
Visitantes Únicos
Total de Transações
Receita Total
Taxa de Conversão
Taxa de Rejeição
Receita por Visitante (RPV)
Ticket Médio por Transação
Ticket Médio por Visitante

## 🔍 Principais Insights
Uma pequena parcela dos visitantes é responsável por grande parte da receita
O funil apresenta quedas significativas entre etapas específicas
A eficiência de monetização é mais impactada pelo valor do visitante do que apenas pelo volume
Algumas fontes de tráfego apresentam alto RPV mesmo com menor taxa de conversão

## 📈 Dashboard
O dashboard no Power BI apresenta:

KPIs principais para visão executiva
Gráfico de funil de visitantes
Análise de conversão por fonte de tráfego
Métricas de eficiência e monetização
🔗 Link do dashboard:
*(https://shre.ink/qkvX)*

📂 Dataset
O dataset tratado utilizado neste projeto está disponível neste repositório:

digital_funnel_clean.csv
🚀 Conclusão
Este projeto demonstra um fluxo completo de análise de dados, integrando SQL, Python e Power BI para transformar dados brutos de marketing digital em insights acionáveis de negócio.

Ele reflete cenários reais enfrentados por analistas de dados e profissionais de Business Intelligence.
