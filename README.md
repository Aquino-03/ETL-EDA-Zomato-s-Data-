# 📊 Zomato Market Analysis - Análise Exploratória de Dados

Este repositório contém o desenvolvimento do **Projeto Aplicado I**, cujo foco é a aplicação de técnicas de Análise Exploratória de Dados (EDA) utilizando a linguagem Python. O projeto analisa o mercado de *FoodTech* através da plataforma Zomato, com o objetivo de compreender as dinâmicas de avaliação, custo e sucesso dos restaurantes.

## 🎯 Problema de Pesquisa

Num mercado altamente competitivo, o que faz um estabelecimento ter sucesso ou ser bem avaliado?
A análise procura responder à seguinte questão de negócio: **Quais os fatores (como tipo de culinária, custo médio e entrega online) que mais influenciam a nota de avaliação (rating) e a popularidade dos restaurantes cadastrados na plataforma?**

## 🗂️ Fonte dos Dados

* **Origem:** Dados extraídos automaticamente via API do Kaggle.
* **Dataset:** [Zomato Market Analysis](https://www.kaggle.com/datasets/srisyra02/zomato-market-analysis)
* **Volume:** 9.551 registos e 21 variáveis (incluindo identificadores, localização, tipos de culinária, custos e avaliações).

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python 3.x
* **Ambiente:** Jupyter Notebook (`.ipynb`)
* **Manipulação de Dados:** `pandas`
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Extração de Dados:** `kagglehub`, `os`

## ⚙️ Pipeline de Dados (ETL)

1. **Extração (Extract):** Download automatizado do dataset em formato `.csv` diretamente do Kaggle para o ambiente local através da biblioteca `kagglehub`.
2. **Transformação e Limpeza (Transform):** Inspeção de dados ausentes (NAs), cálculo de medidas de dispersão (variância e desvio padrão) e identificação de *outliers* através de métodos estatísticos.
3. **Análise Exploratória (EDA):** Geração de resumos estatísticos descritivos e visualizações gráficas (Histogramas e Boxplots) para entender as distribuições das notas de avaliação e dos custos médios.

## 🚀 Como Executar o Projeto

1. Faça o clone deste repositório para a sua máquina local:
```bash
git clone https://github.com/Aquino-03/ETL-EDA-Zomato-s-Data-.git

```


2. Aceda ao diretório do projeto:
```bash
cd NOME-DO-REPOSITORIO

```


3. Instale as dependências necessárias através do ficheiro `requirements.txt`:
```bash
pip install -r requirements.txt

```


4. Abra o ficheiro `analise_zomato.ipynb` no seu ambiente Jupyter (VS Code, Jupyter Lab ou Google Colab) e execute as células sequencialmente. O download do dataset será feito automaticamente na primeira célula de código.

## 👥 Autor

* David Aquino da Trindade

---

*Projeto desenvolvido para a unidade curricular de Projeto Aplicado I - Outubro de 2026.*