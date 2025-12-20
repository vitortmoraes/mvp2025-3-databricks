# 🚀 Projeto MVP: Análise de Rotatividade de Funcionários (HR Attrition) - PUC-Rio
# Sprint: Engenharia de Dados (40530010057_20250_02)

## 🌟 Visão Geral do Projeto

Este projeto implementa um **Pipeline de Dados em Nuvem (Data Engineering)** utilizando o ambiente Databricks para analisar a rotatividade de funcionários. O objetivo é transformar dados brutos em um **Data Warehouse Dimensional (Esquema Estrela)** para identificar fatores de risco e prescrever ações estratégicas para o RH.

O MVP cobre todo o ciclo de vida do dado: **Ingestão, Modelagem Dimensional (Star Schema), Pipeline ETL (Delta Lake), Qualidade (DMBOK) e Análise OLAP/BI**.

---

## 📺 Apresentação em Vídeo

Assista à explicação detalhada do projeto, percorrendo desde a arquitetura de engenharia de dados até os insights finais apresentados no Dashboard:

[![Apresentação do Projeto - HR Attrition](https://img.youtube.com/vi/k55CvqxFAtI/0.jpg)](https://www.youtube.com/watch?v=k55CvqxFAtI)

> 💡 **Instruções:** Clique na imagem acima para abrir o vídeo no YouTube. O vídeo demonstra o funcionamento do notebook e a lógica das análises.

---

## 📊 Dashboard de BI (Resultados Visuais)

Para uma visualização executiva dos insights, foi desenvolvido um dashboard interativo no Databricks. Você pode conferir a estrutura completa e os gráficos no arquivo PDF disponível no repositório:

👉 **[Acesse aqui o Dashboard em PDF](./Dashboard%20HR%20Attrition.pdf)**

---

## 🛠️ Guia de Configuração Rápida (Pré-requisitos)

Para reproduzir este projeto, siga os passos abaixo:

### 1. Criação da Conta no Databricks
O projeto foi desenvolvido na **Databricks Community Edition (Grátis)**.
1. Acesse o [site oficial da Databricks](https://www.databricks.com/try-databricks) e crie sua conta Community.

### 2. Vinculação com o GitHub
1. No Databricks, vá em **User Settings** > **Git Integration** e conecte seu GitHub via **Personal Access Token**.
2. No menu lateral, clique em **Workspace** > **Repos** > **Add Repo** e cole a URL deste repositório.

---

## 🏗️ Arquitetura e Governança

| Área | Tecnologia/Conceito | Descrição |
| :--- | :--- | :--- |
| **Cloud Engine** | **Databricks (Spark)** | Processamento distribuído e escalável. |
| **Modelagem** | **Star Schema** | Fato (FACT_HR_MOVEMENT) e Dimensões (EMPLOYEE, JOB_INFO). |
| **Armazenamento**| **Delta Lake** | Formato ACID para garantir integridade e performance. |
| **Governança** | **Qualidade (DMBOK)**| Testes de completude e validade semântica implementados no código. |

---

## 🔍 Diagnóstico e Recomendações (Insights de Negócio)

A análise confirmou que a rotatividade é um **risco financeiro e localizado**:

* **Setor Crítico:** O departamento de **Vendas (Sales)** apresenta a maior taxa (**20.63%**).
* **Fator Financeiro:** Funcionários que saíram possuem renda média de **R$ 4.787,09**, significativamente inferior aos que ficaram (R$ 6.832,74).
* **Perfil Comportamental:** Perda de talentos com **Satisfação Média (3)** e **Baixo Envolvimento (1)**.

### ✅ Ações Prescritivas sugeridas:
1.  **Revisão Salarial:** Ajustar políticas para faixas abaixo de R$ 5.000,00.
2.  **Gestão de Clima:** Investigação operacional profunda no setor de Vendas.

---

## 🚀 Trabalhos Futuros

1.  **MLOps:** Implementar modelo preditivo de Attrition para antecipar saídas voluntárias.
2.  **DataOps:** Automatizar o pipeline via Workflows do Databricks para atualização em tempo real.

---

## 📁 Estrutura do Repositório

* `MVP 2025-3 PUC-Rio.ipynb`: Notebook com todo o desenvolvimento técnico.
* `Dashboard_HR_Attrition.pdf`: Documento com as evidências visuais do Dashboard de BI.
* `README.md`: Documentação do projeto.

---

## 📌 Como Executar
1. Clone este repositório em sua máquina local:
    ```bash
    git clone https://github.com/vitortmoraes/vitormoraes_mvp_2025-1.git
    ```

2. Abra o **notebook_mvp.ipynb** no **Google Colab** ou em um ambiente local com suporte a Jupyter Notebooks.

3. Execute as células do notebook para reproduzir o trabalho de análise e pré-processamento.

---

## 👨‍💻 Autor
- **Vitor Moraes**  
  <img src="https://i.pinimg.com/1200x/1e/2a/03/1e2a033d11daf6346c6ce1df6f8b2dbb.jpg" alt="Foto de Vitor" width="150" height="150">

- **LinkedIn**: [https://www.linkedin.com/in/vitor-moraes-2801ba340/](https://www.linkedin.com/in/vitor-moraes-2801ba340/)
- **E-mail**: [vitor.tm@gmail.com](mailto:vitor.tm@gmail.com)

## 💡 Agradecimentos

Agradeço ao curso de **Pós Graduação em Ciência de Dados e Analytics** da **PUC-RIO** e aos recursos disponíveis que tornaram este trabalho possível.

---

<img src="https://reari.uff.br/wp-content/uploads/sites/171/2023/09/pucrio.png" alt="Foto de Vitor" width="150" height="150">
