# 📈 Regressão Linear para Estimar o Preço das Casas  

Este projeto utiliza **Regressão Linear** em **R** para prever o preço de venda de casas com base em diversas variáveis.  

## 📌 Objetivo  
Desenvolver um modelo preditivo para estimar o **preço de venda das casas** a partir das características fornecidas.  

## 📊 Variáveis Utilizadas  

- **`SalePrice`**: Preço de venda da casa (em dólares) 💲  
- **`Basement_Area`**: Área do porão (em pés quadrados) 🏠  
- **`Lot_Area`**: Tamanho do lote (em pés quadrados) 📏  
- **`Heating_QC`**: Qualidade e condição do sistema de aquecimento 🔥  
- **`Season_Sold`**: Estação do ano em que a casa foi vendida 🍂❄️🌷☀️  
- **`Gr_Liv_Area`**: Área habitável acima do solo (em pés quadrados) 🏡  
- **`Garage_Area`**: Tamanho da garagem (em pés quadrados) 🚗  
- **`Deck_Porch_Area`**: Área total de decks e varandas (em pés quadrados) 🌿  
- **`Age_Sold`**: Idade da casa no momento da venda (em anos) ⏳  
- **`Bedroom_AbvGr`**: Número de quartos acima do nível do solo 🛏️  
- **`Total_Bathroom`**: Número total de banheiros (meio banheiro conta como 10%) 🚿  

## 🛠️ Bibliotecas Utilizadas  

Este projeto foi desenvolvido em **R** utilizando as seguintes bibliotecas:  

```r
library(readr)          # Leitura de arquivos CSV  
library(openxlsx)       # Exportação para Excel  
library(haven)          # Importação de arquivos SPSS, Stata e SAS  
library(readxl)         # Leitura de arquivos Excel  
library(tidyverse)      # Conjunto de pacotes para manipulação de dados  
library(yardstick)      # Métricas para avaliação de modelos  
library(lmtest)        # Teste de homogeneidade de variância  
library(car)           # Cálculo do VIF (Variance Inflation Factor)  
library(ggraph)        # Visualização de grafos  
library(plotly)        # Gráficos interativos  
library(ggstance)      # Extensão para gráficos no ggplot2  
library(jtools)        # Ferramentas para regressão  
library(olsrr)         # Diagnóstico de regressão OLS  
library(PerformanceAnalytics) # Análise de desempenho de modelos  
library(correlation)   # Cálculo de correlações  
library(dplyr)         # Manipulação de dados  

📁 RegressaoLinearCasas  
 ├── 📄 README.md  # Este arquivo  
 ├── 📂 data       # Base de dados  
 ├── 📂 codigo_R   # Scripts em R   
 └── 📂 analises_conclusoes  # Análises exploratórias e conclusões (.pdf) 
