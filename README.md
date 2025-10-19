Análise Exploratória: “Obesity or CVD risk” (Kaggle)
Autores

Juan de Souza Holanda

Matheus de Castro Vieira

Diego Duarte de Lima

Mateus Andrade Maia

Sobre o trabalho

Este repositório contém um estudo de Análise Exploratória de Dados (EDA) sobre o dataset “Obesity or CVD risk (Classify/Regressor/Cluster)”, do Kaggle.
O objetivo foi pré-processar os dados e extrair insights a partir de diferentes técnicas descritivas e visuais, incluindo:

Análise monovariada (visões marginais por variável);

Análise condicional por classe (comparações por níveis de obesidade);

Análise bivariada (correlações, dispersões com coloração por classe);

PCA (Principal Component Analysis) para síntese multivariada e visualização em componentes principais.

O notebook também padroniza variáveis, aplica codificação para atributos categóricos quando necessário e organiza as visualizações para apoiar interpretações epidemiologicamente coerentes (hábitos de vida, medidas antropométricas e níveis de obesidade).

Estrutura do repositório

main.ipynb — notebook principal com todo o fluxo (carregamento, limpeza, EDA, PCA e geração de figuras).

ObesityDataSet.csv — arquivo de dados utilizado no notebook (do dataset Kaggle “Obesity or CVD risk”).

(Opcional) figures/ — pasta para exportar os gráficos gerados.

Principais bibliotecas

pandas, numpy, matplotlib, seaborn, scipy (e eventualmente scikit-learn para utilidades compatíveis com PCA/padronização, caso desejado).

Como executar (Google Colab)

Baixe os arquivos main.ipynb e ObesityDataSet.csv deste repositório.

Acesse Google Colab
