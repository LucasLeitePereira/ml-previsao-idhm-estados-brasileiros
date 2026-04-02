# 📊 Previsão de IDHM dos Estados Brasileiros com Machine Learning

Projeto de aprendizado de máquina para análise e previsão do **Índice de Desenvolvimento Humano Municipal (IDHM)** dos estados brasileiros, utilizando regressão linear com Python e scikit-learn.

---

## 🎯 Objetivo

Treinar um modelo de regressão para prever o IDHM de estados brasileiros com base em indicadores socioeconômicos históricos, explorando o pipeline completo de um projeto de ML: coleta de dados, análise exploratória, treinamento do modelo e avaliação de resultados.

---

## 🗂️ Estrutura do Repositório

```
ml-previsao-idhm-estados-brasileiros/
│
├── ml_idhm.ipynb             # Notebook principal com todo o pipeline de ML
├── data.csv                  # Dataset com dados de IDHM dos estados brasileiros
├── data_cidades_rj.csv       # Dataset auxiliar com dados de cidades do Rio de Janeiro
├── requirements.txt          # Dependências do projeto
├── LICENSE                   # Licença MIT
└── README.md
```

---

## 🧰 Tecnologias Utilizadas

| Biblioteca | Versão | Uso |
|---|---|---|
| `pandas` | 3.0.2 | Manipulação e análise dos dados |
| `scikit-learn` | 1.8.0 | Treinamento e avaliação do modelo de ML |
| `matplotlib` | 3.10.8 | Visualização dos dados e resultados |

---

## ⚙️ Como Executar

### Pré-requisitos

- Python 3.10+
- pip

### 1. Clone o repositório

```bash
git clone https://github.com/LucasLeitePereira/ml-previsao-idhm-estados-brasileiros.git
cd ml-previsao-idhm-estados-brasileiros
```

### 2. Crie um ambiente virtual (recomendado)

```bash
python -m venv venv
source venv/bin/activate       # Linux/macOS
venv\Scripts\activate          # Windows
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Execute o notebook

```bash
jupyter notebook ml_idhm.ipynb
```

---

## 📁 Sobre os Dados

- **`data.csv`** — Contém dados socioeconômicos e de IDHM dos 26 estados brasileiros + Distrito Federal, abrangendo variáveis como renda per capita, expectativa de vida e índice de educação.
- **`data_cidades_rj.csv`** — Dataset auxiliar com dados das cidades do estado do Rio de Janeiro, utilizado para análises regionais complementares.

---

## 🤖 Pipeline de Machine Learning

O notebook `ml_idhm.ipynb` segue as seguintes etapas:

1. **Carregamento e exploração dos dados** — leitura dos CSVs e análise estatística descritiva
2. **Pré-processamento** — tratamento de valores ausentes e normalização das features
3. **Análise Exploratória (EDA)** — visualizações para entender a distribuição e correlação das variáveis
4. **Divisão treino/teste** — separação dos dados para validação do modelo
5. **Treinamento do modelo** — regressão linear com scikit-learn
6. **Avaliação** — métricas de desempenho (ex: R², MAE, RMSE) e visualização das previsões vs. valores reais

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 👤 Autor

**Lucas Leite Pereira**  
[github.com/LucasLeitePereira](https://github.com/LucasLeitePereira)
