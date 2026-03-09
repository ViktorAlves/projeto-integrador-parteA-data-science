# Projeto Integrador - Ciência de Dados da Superstore

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte de um trabalho integrador da disciplina de **Ciência de Dados**, com o objetivo de analisar os dados de uma superstore (loja de varejo) e extrair insights que possam apoiar decisões estratégicas e operacionais. A base de dados utilizada contém informações sobre vendas, lucros, descontos, categorias de produtos e segmentos de clientes.

## 📁 Estrutura do Repositório
├── data/
│
└── Superstore.csv # Base de dados original

├── relatorio/
│ 
└── Projeto_integrador.pdf # Relatório completo com análises e conclusões

└── notebook/

└── Projeto_integrador.ipynb # Código em Python com todas as análises realizadas

## 🎯 Perguntas de Negócio

O projeto buscou responder às seguintes perguntas:

1. Quais foram as categorias que mais venderam?
2. Quais foram os 10 produtos que mais geraram lucros?
3. Qual segmento de clientes gera maior lucro?
4. A quantidade de vendas mudou ao longo do tempo?
5. Os descontos afetam o lucro?

## 🔍 Metodologia

### 1. Compreensão dos Dados
- **Estrutura:** 9.994 linhas e 21 colunas
- **Tipos de variáveis:** 6 numéricas (int e float), 15 categóricas/texto
- **Tratamentos:** Conversão de datas (estavam como object), remoção de colunas não relevantes para análises numéricas (ID e Postal Code)

### 2. Análise Exploratória
- Estatísticas descritivas (média, mediana, mínimo, máximo, desvio padrão)
- Matriz de correlação entre variáveis numéricas
- Visualizações: histogramas, boxplots, scatterplots e heatmap

### 3. Identificação de Padrões e Outliers
- Detecção de outliers em vendas, lucros e descontos
- Análise de correlações (destaque para a relação entre descontos e lucro)

## 📊 Principais Insights

- **Descontos e Lucro:** Existe uma correlação negativa entre descontos e lucro, indicando que descontos elevados podem comprometer a margem de lucro. A empresa deve revisar sua política de descontos.

- **Vendas com Prejuízo:** Nem todas as vendas geram lucro, sendo necessário monitorar transações negativas e avaliar custos associados.

- **Desempenho por Categoria:** Há diferenças significativas no lucro médio entre categorias de produtos, sugerindo a priorização de investimentos nas categorias mais rentáveis.

- **Sazonalidade:** O volume de vendas varia ao longo do tempo, o que pode ser utilizado para planejamento de estoque e campanhas promocionais.

## 🛠️ Tecnologias Utilizadas

- **Python** (pandas, seaborn, matplotlib)
- **Google Colab** para desenvolvimento do código

## 🤖 Uso de IAs

Durante o desenvolvimento, utilizamos ferramentas de IA (Deepseek e ChatGPT) para:
- Tirar dúvidas pontuais sobre a análise
- Detectar correções necessárias no código

## ▶️ Como Reproduzir a Análise

1. Clone este repositório
2. Acesse a pasta `Notebook/` e abra o arquivo `.ipynb` no Google Colab ou Jupyter Notebook
3. Certifique-se de que o arquivo `Superstore.csv` está no caminho correto ou ajuste o path no código
4. Execute todas as células para reproduzir as análises e gráficos

## 👥 Equipe

- Ana Gierse
- Erica Gonçalves
- Luana Domingos
- Victor Alves

Este projeto foi desenvolvido para fins acadêmicos.
