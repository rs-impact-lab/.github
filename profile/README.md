
# Lab Big Data Analytics: RS Impact

Este é o repositório oficial do projeto  **RS Impact** , uma iniciativa de análise de dados desenvolvida no curso de Análise e Desenvolvimento de Sistemas (ADS) da Estácio Aracaju.

## Sobre o Projeto

O **RS Impact** analisa a resiliência econômica do Rio Grande do Sul pós-desastre de 2024. A pesquisa correlaciona microdados do CAGED (mercado de trabalho) com índices pluviométricos do INMET para identificar o *lag time* de recuperação e os impactos setoriais da catástrofe.

* **Desenvolvedores:** Lucas Paiva Santos de Oliveira (@lucaspaiva-lp) e Rodrigo Moraes dos Santos (@RodrigoDevBack).
* **Orientação:** Prof. Max Castor Rodrigues Junior.
* **Status:** Concluído.

## Pipeline de Dados

O projeto segue um fluxo de trabalho estruturado para processamento de Big Data:

* **Ingestão:** Coleta automatizada de dados CAGED e relatórios pluviométricos.
* **Transformação:** Limpeza, filtragem geográfica (RS) e padronização temporal.
* **Análise:** Extração de correlações estatísticas entre eventos climáticos e flutuações de emprego.

## Stack Tecnológico

O desenvolvimento foi realizado com foco em performance e análise estatística:

| **Categoria**         | **Tecnologias**               |
| --------------------------- | ----------------------------------- |
| **Processamento**     | Apache Spark, PySpark, MapReduce    |
| **Análise de Dados** | Python, Pandas, NumPy, Scikit-Learn |
| **Visualização**    | Matplotlib, Seaborn, Plotly         |
| **Ambientes**         | Jupyter Notebooks, VS Code, Git     |
