# PowerBI
# 🏆 Dashboard Campeonato Brasileiro - Power BI + Python (Scikit-learn)

Este projeto é um dashboard interativo desenvolvido no **Power BI Desktop**, com integração de **Python (Scikit-learn)** para gerar **previsões de pontuação final**, identificar o **provável campeão**, e os **principais artilheiros** do Campeonato Brasileiro 2025.

---

## 📌 Objetivo

Criar um dashboard dinâmico e visualmente atrativo que:

- Exiba **a classificação atual** do Campeonato Brasileiro
- Mostre os **principais artilheiros**
- Liste os **próximos jogos**
- Faça **projeções estatísticas** com Python, estimando:
  - Pontuação final de cada time
  - Prováveis **Top 3 times** ao fim do campeonato
  - Goleador mais provável da temporada

---

## 🛠️ Tecnologias utilizadas

- **Power BI Desktop**
- **Power Query (M Language)**
- **DAX**
- **Python (com integração no Power BI)**:
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `seaborn`

---

## 📊 Fontes de dados

- Dados obtidos via **Web** (página oficial do Campeonato Brasileiro ou sites como GE.globo, SofaScore, etc.)
- Atualizados manualmente a cada rodada *(ou por meio de Web Scraping automatizado futuramente)*

---

## 🔮 Previsão com Python

Foram criados scripts em Python diretamente no Power BI para projetar:

- **Pontos Finais** por time com base na média atual por jogo
- **Top 3 times mais prováveis de vencer o campeonato**
- **Artilheiro mais provável**, com projeção linear de gols

> A modelagem foi feita usando **Regressão Linear Simples** com `Scikit-learn` e visualizações com `matplotlib`.

---

## 🖼️ Screenshots

*Adicione aqui imagens do seu dashboard (print das páginas no Power BI).*

---

## 🚀 Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/dash-brasileirao.git
