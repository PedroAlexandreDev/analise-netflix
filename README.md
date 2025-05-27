# 📊 Análise de Dados da Netflix

Este projeto realiza uma análise exploratória de dados (EDA) sobre o catálogo da Netflix, utilizando Python com as bibliotecas Pandas e Plotly. O objetivo é entender melhor os padrões de lançamento, popularidade por país, gêneros mais comuns e distribuição entre filmes e séries.

---

## 📁 Dataset

- **Fonte:** Kaggle - [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Formato:** CSV
- **Tamanho:** ~6.2 MB
- **Total de registros:** ~8800 títulos

---

## ⚙️ Tecnologias Utilizadas

- Python 3.x
- Pandas
- Plotly Express
- Jupyter Notebook

---

## 🧹 Limpeza de Dados

As seguintes colunas apresentavam valores nulos e foram tratadas:

- `director`, `cast`, `country`, `date_added`, `rating`, `duration`
- Foram preenchidas com valores padrão como `"No Director"`, `"No Cast"` etc.

---

## 📊 Análises Realizadas

### 1. 🎬 Distribuição por Tipo de Conteúdo
- Gráfico de pizza mostrando proporção de Filmes vs Séries.

### 2. 🌎 Top 10 Países com Mais Títulos
- Análise dos países com maior volume de produções no catálogo.

### 3. 📈 Títulos por Ano de Lançamento
- Linha do tempo mostrando o número de lançamentos por ano.

### 4. 🎭 Gêneros Mais Frequentes
- Identificação dos gêneros mais comuns usando a coluna `listed_in`.

---

## 📌 Principais Insights

- A maioria do conteúdo da Netflix é composta por **Filmes**, com menor proporção de Séries.
- **Estados Unidos**, **Índia** e **Reino Unido** são os países com mais produções disponíveis.
- O número de lançamentos teve um **aumento gradual até 2019**, caindo ligeiramente nos anos seguintes.
- Os gêneros mais comuns são **Dramas**, **Comédias** e **Documentários**.

---

## 📁 Estrutura do Projeto

```
📦 Netflix Analysis
│
├── netflix_titles.csv        # Dataset original
├── netflix_analysis.ipynb    # Código da análise em Python
└── README.md                 # Este arquivo
```

---

## 📌 Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/netflix-analysis.git
```

2. Instale as dependências (opcional):
```bash
pip install pandas plotly
```

3. Abra o notebook no Jupyter:
```bash
jupyter notebook netflix_analysis.ipynb
```

---

## 💡 Possíveis Extensões

- Separar análises entre filmes e séries
- Explorar a coluna `date_added` para ver tendências de adição à plataforma
- Análise de diretores mais frequentes
- Dashboard interativo com Streamlit ou Dash

---

## 🧠 Autor

- **Seu Nome**
- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- LinkedIn: [seu-linkedin](https://linkedin.com/in/seu-usuario)

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.
