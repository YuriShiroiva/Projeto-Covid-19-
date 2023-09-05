---

# Analise dos dados do Covid-19

![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)&nbsp; 

Projeto do curso _Criando modelos com Python e Machine Learning para prever a evolução do COVID-19 no Brasil_, promovido pela [Digital Innovation One](https://web.digitalinnovation.one/home).

Neste projeto é feito uma análise exploratória dos dados do COVID-19 no Brasil, no período inicial da pandemia, utilizando as bibliotecas [Pandas](https://pandas.pydata.org/) e [Plotly](https://plotly.com/) (visualização de dados).

---

Além disso, são feitas previsões sobre as séries temporais dos números de _casos confirmados_ e _novos casos por dia_ utilizado as bibliotecas [pmdARIMA](https://pypi.org/project/pmdarima/) e [Prophet](https://facebook.github.io/prophet/docs/quick_start.html).

![taxa_crescimento](https://github.com/YuriShiroiva/Projeto-Covid-19-/blob/main/img/taxa_crescimento_diario.png)

---

## Setup

Escrito em Python 3.9 (Versão compatível com o fbprophet). Não esqueça da virtualenv. Os comandos`python` a baixo serão para instalação e execução.

Primeiro é necessário instalar os requirements.

```bash
python -m pip install -r requirements.txt
```
Ou
```bash
conda install --file requirements.txt -p ./lib
```
Recomendo a utilização do Conda, pois são muitas "gambs" para instalar o fbprophet via pip, não compensando o esforço. 


## Run
Os dados são inseridos em variáveis do próprio código, bastando executá-lo.

---
