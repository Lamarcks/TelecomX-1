<div align="center">

# 📡 Telecom X — Análise de Evasão de Clientes

### Data Science aplicada à análise de Churn e retenção de clientes

Projeto desenvolvido durante minha formação em **Data Science no programa Oracle Next Education (ONE) + Alura**, com foco na aplicação de **ETL, Análise Exploratória de Dados (EDA) e visualização de dados** para investigar os fatores relacionados ao cancelamento de clientes de uma empresa de telecomunicações.

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0?style=for-the-badge)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge\&logo=googlecolab\&logoColor=white)

</div>

---

## 📌 Sobre o projeto

A **Telecom X** enfrenta um elevado índice de cancelamento de clientes e precisa compreender quais fatores estão relacionados à evasão, também conhecida como **Churn**.

Neste projeto, os dados foram coletados, tratados e analisados utilizando **Python e suas principais bibliotecas de análise de dados**, buscando identificar padrões comportamentais, financeiros e contratuais associados ao cancelamento dos serviços.

O resultado da análise fornece insights que podem apoiar **estratégias de retenção de clientes e futuras aplicações de Machine Learning**.

---

## 🎯 Objetivo

O principal objetivo foi compreender o comportamento dos clientes e identificar características associadas ao Churn.

A análise buscou:

* 📉 Identificar padrões relacionados à evasão
* 👥 Compreender o perfil dos clientes que cancelam
* 💰 Avaliar fatores financeiros relacionados ao Churn
* 📄 Comparar diferentes tipos de contrato
* 📦 Investigar a influência de serviços adicionais
* 💳 Analisar métodos de pagamento
* 📊 Gerar insights para estratégias de retenção

---

## 🔄 Processo de ETL

O projeto utilizou um fluxo completo de **Extração, Transformação e Carga — ETL**.

```text
Extração dos dados via API
          ↓
Exploração inicial
          ↓
Limpeza e tratamento
          ↓
Padronização das variáveis
          ↓
Transformação dos dados
          ↓
Análise Exploratória
          ↓
Visualização dos resultados
          ↓
Insights e recomendações
```

### 📥 Extração

* Importação dos dados brutos para o ambiente de análise.
* Leitura e exploração inicial da estrutura do dataset.

### 🔧 Transformação

* Tratamento de valores ausentes.
* Padronização das variáveis categóricas.
* Conversão de variáveis binárias.
* Ajuste dos tipos de dados.
* Criação de métricas auxiliares para análise.

### 📤 Carga

* Preparação do conjunto de dados tratado para análise exploratória e visualização.

---

## 🔎 Análise Exploratória de Dados

Durante a **EDA — Exploratory Data Analysis**, diferentes características dos clientes foram comparadas com a variável de evasão.

Entre as principais análises:

* ⏳ Tempo de contrato × Churn
* 💵 Valor mensal × Churn
* 💰 Gasto total × Churn
* 📄 Tipo de contrato × Churn
* 📦 Serviços adicionais × Churn
* 👥 Gênero × Churn
* 💳 Método de pagamento × Churn
* 🔗 Correlação entre variáveis

---

## 📊 Visualização de Dados

Foram utilizadas as bibliotecas **Matplotlib e Seaborn** para transformar os resultados das análises em visualizações de fácil interpretação.

As visualizações permitiram comparar diferentes grupos de clientes e identificar padrões associados à evasão.

---

## 💡 Principais Insights

A análise identificou alguns fatores relevantes relacionados ao cancelamento dos serviços:

### ⏳ Tempo de contrato

Clientes com **menor tempo de permanência** apresentaram maior tendência ao Churn.

### 📄 Tipo de contrato

Clientes com **contratos mensais** apresentaram maior taxa de cancelamento em comparação aos contratos de maior duração.

### 💵 Valores cobrados

Valores mensais mais elevados mostraram associação com maior ocorrência de evasão.

### 📦 Serviços adicionais

Clientes com maior utilização de serviços adicionais apresentaram tendência de maior permanência na empresa.

### 💳 Método de pagamento

O método de pagamento apresentou relação relevante com o Churn, especialmente entre clientes que utilizavam **cheque eletrônico**.

### 👥 Gênero

O gênero, isoladamente, não demonstrou ser um fator determinante para a evasão.

---

## 🎯 Recomendações de Negócio

Com base nos padrões identificados, algumas estratégias podem contribuir para a redução do Churn:

* Criar ações de retenção durante os primeiros meses do contrato.
* Incentivar clientes a migrarem para contratos de maior duração.
* Desenvolver ofertas personalizadas para clientes com mensalidades elevadas.
* Criar pacotes que incentivem a contratação de serviços adicionais.
* Estimular a utilização de métodos de pagamento automáticos.
* Utilizar os dados tratados como base para criação de modelos preditivos de Churn.

---

## 🛠️ Tecnologias utilizadas

| Tecnologia                 | Aplicação                                               |
| -------------------------- | ------------------------------------------------------- |
| **Python**                 | Linguagem principal da análise                          |
| **Pandas**                 | Extração, tratamento, transformação e análise dos dados |
| **Matplotlib**             | Construção de visualizações                             |
| **Seaborn**                | Visualizações estatísticas e comparações                |
| **Google Colab / Jupyter** | Desenvolvimento e execução do notebook                  |
| **Git & GitHub**           | Versionamento e documentação do projeto                 |

---

## 📂 Estrutura do projeto

```text
TelecomX-1/
│
├── TelecomX_(1).ipynb
└── README.md
```

### `TelecomX_(1).ipynb`

Notebook contendo todo o fluxo do projeto:

**extração → tratamento → transformação → análise exploratória → visualização → conclusões.**

---

## 🚀 Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/Lamarcks/TelecomX-1.git
```

### 2. Acesse a pasta

```bash
cd TelecomX-1
```

### 3. Abra o notebook

```text
TelecomX_(1).ipynb
```

O projeto pode ser executado utilizando:

* **Google Colab**
* **Jupyter Notebook**
* **Visual Studio Code com suporte a Jupyter**

---

## 📚 Conhecimentos desenvolvidos

Durante o projeto foram aplicados conhecimentos importantes para análise de dados:

* Extração de dados
* Processos ETL
* Limpeza e padronização de datasets
* Manipulação de dados com Pandas
* Análise Exploratória de Dados
* Análise de correlação
* Visualização com Matplotlib e Seaborn
* Identificação de padrões
* Interpretação de indicadores
* Desenvolvimento de recomendações orientadas por dados

---

## 🚀 Próxima etapa

Os dados tratados e os insights obtidos neste projeto criam uma base para uma etapa mais avançada:

```text
Análise Exploratória
        ↓
Feature Engineering
        ↓
Machine Learning
        ↓
Modelos de Classificação
        ↓
Previsão de Churn
        ↓
Estratégias de Retenção
```

---

## ✅ Status do projeto

**Concluído ✅**

Projeto desenvolvido como parte da formação em **Data Science — Oracle Next Education (ONE) + Alura**.

---

## 👨‍💻 Autor

**Ihago Lamarcks**

Estudante de **Análise e Desenvolvimento de Sistemas**, com foco em **Python, Dados, Inteligência Artificial e Cloud Computing**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ihago%20Lamarcks-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/ihago-lamarcks1/)

---

<div align="center">

### 📡 Transformando dados de clientes em insights para redução de Churn.

**Python • Data Science • ETL • EDA • Oracle Next Education**

</div>
