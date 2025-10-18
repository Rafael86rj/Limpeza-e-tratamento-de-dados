# 📊 Limpeza e Tratamento de Dados

Este repositório documenta um projeto prático focado nas etapas essenciais de **Limpeza e Tratamento de Dados** (Data Wrangling), utilizando as bibliotecas padrão da comunidade Python: **Pandas** e **NumPy**. O objetivo é transformar uma base de dados bruta em um formato limpo e estruturado, pronta para a análise.

## 🎯 Objetivo do Projeto

Realizar um processo completo de limpeza e tratamento em uma base de dados para garantir sua qualidade e confiabilidade.

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python**
* **Pandas** (Principal biblioteca para manipulação de dados)
* **NumPy** (Suporte para operações numéricas)
* **Seaborn/Matplotlib** (Para visualizações como Boxplot)

## 📋 Tópicos Abordados (Checklist de Tarefas)

O projeto engloba as seguintes técnicas e operações cruciais no tratamento de dados:

### 1. Leitura e Estruturação de Dados

* [ ] Fazer a leitura da base de dados no formato **JSON**.
* [ ] Utilizar o método `json_normalize` em um Pandas DataFrame.
* [ ] Aplicar o método `json_normalize` em um objeto JSON.
* [ ] Utilizar o método `info()` para obter informações iniciais dos dados.

### 2. Conversão e Inserção de Dados

* [ ] Fazer o *cast* (conversão de tipo) de uma coluna.
* [ ] Inserir valores em uma coluna.

### 3. Tratamento de Valores Faltantes e Duplicados

* [ ] Filtrar as *strings* vazias em uma coluna.
* [ ] Remover as *strings* vazias de uma coluna.
* [ ] Identificar e remover dados duplicados.
* [ ] Identificar dados nulos.
* [ ] Inserir dados no lugar de dados nulos.
* [ ] Remover dados nulos.

### 4. Tratamento de Outliers (Valores Extremos)

* [ ] Identificar *outliers* com o método **IQR (Intervalo Interquartil)**.
* [ ] Reconhecer possíveis candidatos a *outliers* com o **Boxplot**.
* [ ] Substituir valores para os *outliers*.
* [ ] Remover amostras consideradas *outliers*.

### 5. Tratamento de Variáveis Categóricas

* [ ] Identificar variáveis categóricas.
* [ ] Substituir os valores das variáveis categóricas binárias.
* [ ] Aplicar a técnica de **One Hot Encoder** (para variáveis nominais).

---

# 📚 Referências e Materiais de Apoio

| Material | Tipo | Idioma | Conteúdo Chave |
| :--- | :--- | :--- | :--- |
| **Python para análise de dados** | Livro (Pago) | Português | Guia completo sobre manipulação, processamento, limpeza e análise de dados com NumPy, Pandas e Matplotlib. |
| **[Melhorando a análise com o boxplot (Alura)](https://www.alura.com.br/artigos/melhorando-a-analise-com-o-boxplot)** | Artigo (Gratuito) | Português | Explica o uso do boxplot (quartis) como recurso estatístico para melhorar a análise e identificar outliers, com exemplos em Python e Seaborn. |
| **[API Reference (Pandas)](https://pandas.pydata.org/docs/reference/index.html)** | Documentação (Gratuito) | Inglês | Documentação oficial com exemplos de códigos e detalhes de todas as funcionalidades da biblioteca Pandas. |


## 🔎 Visualizar o Projeto Completo

Para ver o **código completo**, as **saídas das células** e a **análise detalhada** de cada etapa de limpeza e tratamento, acesse o notebook do projeto:

* [**Abrir o Notebook: Limpeza e Tratamento de Dados.ipynb**](https://github.com/Rafael86rj/Limpeza-e-tratamento-de-dados/blob/8af46ef56cf738372e9b9cb1fc3db749cbc5cbfe/Limpeza%20e%20Tratamento%20de%20Dados.ipynb)
