# Análise de Dados: Violência Contra a Mulher em Minas Gerais (2010–2025)

Este repositório contém um projeto de Análise Exploratória de Dados (EDA) desenvolvido para um **Projeto Extensionista** acadêmico. O objetivo principal é utilizar dados abertos para fundamentar discussões sobre a evolução da violência doméstica no estado de Minas Gerais e apoiar debates universitários.

---

## 📊 Origem dos Dados

Os dados utilizados neste projeto foram extraídos diretamente do Portal de Transparência do Governo de Minas Gerais.

* **Fonte Original dos Dados:** [Portal da Transparência do Estado de Minas Gerais](https://github.com/transparencia-mg/ses_violencia_contra_mulher/tree/main)
* **Volume:** ~500.000+ registros consolidados abrangendo o período de 2010 a 2025 (SINAN/SES-MG).

---

## 🔍 Principais Achados da Análise

A partir do tratamento e consolidação das notificações, os dados revelam padrões críticos sobre a realidade da violência contra a mulher no estado:

1. **Reincidência Elevada:** A maioria esmagadora das ocorrências notificadas aponta que a vítima já havia sofrido episódios de violência anteriores, evidenciando o ciclo contínuo de agressão antes da intervenção formal.
2. **Ambiente Doméstico como Principal Foco:** A residência da vítima figura como o local primário das ocorrências, superando significativamente vias públicas e outros estabelecimentos.
3. **Crescimento das Notificações:** O histórico temporal mostra um aumento expressivo no volume de registros ao longo dos anos, refletindo tanto o aumento do fluxo de denúncias quanto a consolidação dos sistemas de notificação de saúde pública.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.12
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização de Dados:** Matplotlib, Seaborn
* **Controle de Versão:** Git & GitHub (Seguindo padronização *Conventional Commits*)

---

## 📁 Estrutura do Repositório

```text
├── dados_consolidados.csv       # Dataset tratado e unificado (~62 MB)
├── analise_violencia_mg.ipynb   # Jupyter Notebook com pipeline de ingestão e gráficos
├── 01_evolucao_historica_casos.png # Gráfico de evolução temporal em alta resolução (300 DPI)
├── 02_taxa_reincidencia_violencia.png # Gráfico de reincidência
├── 03_locais_ocorrencia.png     # Gráfico dos principais locais de agressão
└── README.md                    # Documentação do projeto