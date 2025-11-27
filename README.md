# 🎬 Projeto de Regressão de Notas IMDb: **Previsão de Sucesso no Cinema** 🍿

---

## 🎯 Introdução

Este projeto implementa um modelo de **Regressão Linear** para prever a nota (rating) de filmes no IMDb, utilizando o conjunto de dados fornecido (`desafio_indicium_imdb.csv`). O objetivo é demonstrar a análise exploratória, o treinamento e o carregamento do modelo.


## Descrição dos Diretórios

### **📁 data/**
- **raw/**: Contém os dados brutos originais do desafio
  - `desafio_indicium_imdb.csv` - Dataset principal

### **📁 notebooks/**
- `Analise Exploratoria dos Dados.ipynb` - Análises exploratórias e visualizações

### **📁 src/**
- `Codigo de Treino do Modelo.ipynb` - Desenvolvimento e treinamento do modelo

### **📁 models/**
- `modelo_regressao_final.pkl` - Modelo de regressão linear treinado (serializado)

### **📄 Arquivos de Configuração**
- `requirements.txt` - Dependências e bibliotecas do projeto
- `README.md` - Documentação principal

## ⚙️ 1. Instalação e Configuração



Para rodar este projeto, é recomendável criar um ambiente virtual Python (utilizando `venv` ou `conda`).



1. **Crie e Ative o Ambiente Virtual:**



    ```bash

    # Se estiver usando venv:

    python -m venv venv

    source venv/bin/activate  # macOS/Linux

    venv\Scripts\activate     # Windows



    # OU se estiver usando conda (versão - 25.7.0):

    conda create -n desafio-indicium python=3.13.5

    conda activate desafio-indicium

    ```



2. **Instale as Dependências:**



    Instale todas as bibliotecas necessárias listadas no `requirements.txt`:



    ```bash

    pip install -r requirements.txt

    ```



---



## 🚀 2. Como Executar



O código principal de treinamento e análise pode ser encontrado nos Notebooks:



* **`notebooks/Analise Exploratoria dos Dados.ipynb`**: Contém a limpeza inicial e a visualização dos dados.

* **`notebooks/Codigo de Treino do Modelo.ipynb`**: Contém o carregamento do modelo salvo (`models/modelo_regressao_final.pkl`) e exemplos de uso para novas predições.