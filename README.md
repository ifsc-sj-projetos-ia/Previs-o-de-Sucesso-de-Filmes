#  Predição do Sucesso Financeiro de Filmes utilizando Aprendizado de Máquina

##  Descrição

Este projeto foi desenvolvido para a disciplina de Inteligência Computacional e Dados do curso de Análise e Desenvolvimento de Sistemas do IFSC.

O objetivo é aplicar técnicas de Aprendizado de Máquina para prever o faturamento de filmes a partir de características presentes em uma base de dados cinematográfica.

---

##  Autora

**Ingridy Vitória Aragão Alves**
Curso Superior de Tecnologia em Análise e Desenvolvimento de Sistemas – IFSC
3º semestre

**Professor Orientador:** Ramon Mayor

---

##  Objetivo

Desenvolver modelos de aprendizado de máquina capazes de estimar o faturamento de filmes utilizando informações como:

* Orçamento do filme;
* Popularidade;
* Média das avaliações;
* Quantidade de votos;
* Gênero.

---

##  Base de Dados

Foi utilizada a base de dados **IMDBMovies**, contendo informações sobre diversos filmes e seus desempenhos financeiros.

Variáveis utilizadas:

* Movie_budget
* Movie_revenue
* vote_average
* vote_count
* popularity
* gender

---

##  Tecnologias Utilizadas

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Modelos Utilizados

* Regressão Linear
* Random Forest

---

##  Análise Exploratória

Foram realizadas análises estatísticas e gráficas dos dados, incluindo:

* Matriz de correlação;
* Gráfico de dispersão entre orçamento e faturamento;
* Avaliação das relações entre as variáveis.

Os resultados mostraram que a quantidade de votos e a popularidade possuem forte influência sobre o faturamento dos filmes.

---

##  Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/projeto-filmes.git
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Abra o Jupyter Notebook:

```bash
jupyter notebook
```

4. Execute o arquivo:

```text
Previsao_de_Sucesso_de_Filmes.ipynb
```

---

##  Estrutura do Projeto

```text
projeto-filmes/
│
├── data/
│   └── IMDBmovies.xlsx
│
├── notebooks/
│   └── Previsao_de_Sucesso_de_Filmes.ipynb
│
├── images/
│   ├── correlacao.png
│   └── dispersao.png
│
├── README.md
├── LICENSE
└── requirements.txt
```

---

##  Limitações

* A base de dados possui quantidade limitada de variáveis.
* Fatores como marketing, críticas e tendências culturais não foram considerados.
* O modelo não deve ser utilizado como único critério para tomada de decisões financeiras.

---

##  Trabalhos Futuros

* Utilizar bases de dados maiores.
* Aplicar redes neurais.
* Incluir análise de críticas e comentários.
* Utilizar técnicas de Processamento de Linguagem Natural.

---

##  Licença

Este projeto utiliza a licença MIT.

---

##  Repositório

Link do GitHub: *(adicionar após publicar o projeto).*
