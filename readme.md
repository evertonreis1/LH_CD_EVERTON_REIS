# Análise Cinematográfica e Previsão de Nota IMDb

## 📝 Descrição do Projeto

Este projeto consiste na resolução de um desafio de Ciência de Dados proposto pela Indicium. O objetivo é realizar uma análise exploratória em um banco de dados cinematográfico para orientar um estúdio de Hollywood sobre qual tipo de filme desenvolver.

A análise inclui a limpeza e visualização dos dados, a resposta a perguntas de negócio e a construção de um modelo de Machine Learning para prever a nota do IMDb de um filme com base em suas características.

## 🛠️ Tecnologias Utilizadas

* **Python 3.10+**
* **Pandas:** Para manipulação e análise de dados.
* **Matplotlib & Seaborn:** Para visualização de dados.
* **WordCloud:** Para a criação de nuvens de palavras.
* **Scikit-learn:** Para a construção dos modelos de Machine Learning (Regressão e Classificação).
* **Jupyter Notebook:** Como ambiente de desenvolvimento e para a apresentação do relatório final.

## 📁 Estrutura do Repositório

```
.
├── analise_filmes_imdb.ipynb   # Notebook com toda a análise, códigos e respostas.
├── imdb_rating_model.pkl       # Modelo de regressão treinado e salvo.
├── desafio_indicium_imdb.csv   # O conjunto de dados original.
├── requirements.txt            # Lista de dependências do projeto.
└── README.md                   # Este arquivo.
```

## 🚀 Como Instalar e Executar o Projeto

Siga os passos abaixo para configurar o ambiente e executar a análise.

### 1. Clone o Repositório

```bash
git clone https://github.com/evertonreis1/LH_CD_EVERTON_REIS.git
cd LH_CD_EVERTON_REIS
```

### 2. Crie um Ambiente Virtual

É uma boa prática criar um ambiente virtual para isolar as dependências do projeto.

```bash
# Para Windows
python -m venv venv
venv\Scripts\activate

# Para macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Instale as Dependências

Instale todos os pacotes necessários listados no arquivo `requirements.txt`.

```bash
pip install -r requirements.txt
```

### 4. Execute o Jupyter Notebook

Com as dependências instaladas, inicie o Jupyter Notebook para visualizar a análise.

```bash
jupyter notebook analise_filmes_imdb.ipynb
```

Ao abrir o notebook, você pode executar todas as células para replicar a análise e gerar o arquivo `imdb_rating_model.pkl`.

## 👨‍💻 Autor

**Everton Reis**