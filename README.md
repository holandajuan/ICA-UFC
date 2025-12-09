# HW 1 — Análise Exploratória: "Obesity or CVD risk" (Kaggle)

## Autores

- Juan de Souza Holanda
- Matheus de Castro Vieira
- Diego Duarte de Lima
- Mateus Andrade Maia

---

## Sobre o trabalho (HW 1 — EDA)

Este repositório contém inicialmente um estudo de **Análise Exploratória de Dados (EDA)** sobre o dataset **"Obesity or CVD risk (Classify/Regressor/Cluster)"**, do Kaggle.

O objetivo do HW 1 foi **pré-processar os dados** e **extrair insights iniciais** a partir de diferentes técnicas estatísticas descritivas e visuais, incluindo:

- **Análise monovariada** (distribuições, histogramas, boxplots);
- **Análise condicional por classe** (comparações por níveis de obesidade);
- **Análise bivariada** (correlações, gráficos de dispersão com coloração por classe);
- **PCA (Principal Component Analysis)** para síntese **multivariada** e visualização em componentes principais.

O notebook realiza a padronização das variáveis, aplica codificação para atributos categóricos quando necessário e organiza as visualizações de forma a permitir interpretações epidemiologicamente coerentes (hábitos de vida, medidas antropométricas e níveis de obesidade).

---

## Estrutura do repositório

- **`main.ipynb`** — notebook principal com todo o fluxo de EDA, PCA e geração das figuras.
- **`ObesityDataSet.csv`** — arquivo de dados utilizado (dataset Kaggle "Obesity or CVD risk").
- **`HWS/`** — pasta contendo os trabalhos e implementações complementares da disciplina.
- **`figures/`** — pasta para exportação dos gráficos.

---

## Principais bibliotecas

`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `scikit-learn`

---

## Como executar (Google Colab)

1. **Baixe** os arquivos `main.ipynb` e `ObesityDataSet.csv` deste repositório.
2. **Acesse** o [Google Colab](https://colab.research.google.com/) e **abra** o arquivo `main.ipynb`.
3. No Colab, no painel **Arquivos**, **faça o upload** do `ObesityDataSet.csv`.
4. **Execute as células na ordem em que aparecem.**

---

## Resultados esperados — HW 1 (EDA)

- Caracterização das distribuições (tendência central, dispersão, assimetria);
- Comparações por classe de obesidade para variáveis-chave;
- Correlações bivariadas relevantes;
- Projeção PCA evidenciando eixos latentes de adiposidade e estilo de vida.

---

# HW 2 — Modelos de Regressão e Aprendizado Supervisionado

## Objetivo da HW 2

O HW 2 tem como objetivo a **modelagem preditiva da variável alvo** a partir das variáveis explicativas do dataset, empregando **modelos de regressão clássicos e métodos baseados em redução de dimensionalidade**.

Busca-se:
- Avaliar o desempenho preditivo dos modelos;
- Comparar implementações **manuais (do zero)** com bibliotecas de referência;
- Analisar estabilidade, erro médio e capacidade de generalização.

---

## Modelos Implementados

No HW 2 são estudados e comparados os seguintes modelos:

- **Regressão Linear Múltipla**
- **Regressão Ridge** (com regularização L2)
- **Regressão por Componentes Principais (PCR)**
- **Partial Least Squares (PLS)**
- **Redes Neurais para Regressão**

Cada modelo é analisado por meio de:
- Erro Quadrático Médio (RMSE);
- Coeficiente de Determinação (R²);
- Comparação entre valores reais e preditos;
- Validação cruzada.

---

## Metodologia Geral do HW 2

1. Separação dos dados em **conjunto de treino (80%) e teste (20%)**;
2. **Padronização das variáveis** (quando aplicável);
3. Treinamento dos modelos;
4. Avaliação no conjunto de teste;
5. Comparação entre:
   - Implementação manual (Scratch);
   - Implementação com `scikit-learn`.

---

## Resultados Esperados — HW 2

- Verificação da capacidade preditiva dos modelos;
- Avaliação do impacto da redução de dimensionalidade (PCR e PLS);
- Análise da influência da regularização na regressão Ridge;
- Comparação de desempenho entre métodos lineares e redes neurais.

---

## Referência do Dataset

- **Kaggle** — [Obesity or CVD risk (Classify/Regressor/Cluster)](https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster)

