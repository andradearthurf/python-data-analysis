# Análise de Dados com Python

Repositório com intuito de estudar análise de dados com Python, abordando data frames e casos fictícios/reais. 


## Caso 1 - House Rocket Company

A House Rocket (empresa fictícia) é uma plataforma digital que tem como modelo de negócio, a compra e a venda de imóveis usando tecnologia. 

Dessa forma, o que se espera desse projeto é que seja feita uma análise de dados para essa empresa, com intuito de descrever, por meio de gráficos, algumas questões relevantes a serem respondidas, tendo em vista o respectivo dataframe da empresa. Essas questões são:

1. Quantas casas tem nenhum, um ou mais de um quarto?
2. Quantas casas tem um ou mais de um andar?
3. Quantas casas estão em perfeitas ou em péssimas condições?
4. Quantos quartos, em média, as casas possuem?
5. Qual o preço médio das casas?
6. Qual o desvio padrão do preço?
7. Quais são os 1Q e 3Q dos preços?
8. Existem preços de casas que são outliers?
9. Qual a relação entre o preço médio das casas e a quantidade de quartos?
10. Qual foi o crescimento do preço dos imóveis ano após ano?
11. Qual foi o crescimento do preço dos imóveis mês após mês?

As respostas das questões acima e toda a construção da análise de dados para a House Rocket, podem ser encontrados neste repositório, no seguinte arquivo:  [data_analysis_HouseRocket](https://github.com/andradearthurf/python-data-analysis/blob/main/cases/data_analisys_HouseRocket.ipynb)


## Caso 2 - Análise dos Microdados do ENEM 2019

Este projeto tem como intuito, mostrar de forma clara, a análise de dados do ENEM 2019, que compara os aspectos dos candidatos sem deficiência e candidatos com baixa visão. Além disso, também tem-se como finalidade destacar as principais diferenças tanto da nota tirada em cada prova, quanto dos acertos em cada prova, isto é, de ciências da natureza, ciências humanas, linguagens e matemática. Não busquei focar nas características socioeconômicas dos participantes, pois o critério das análise é verificar se os participantes foram bem ou não na prova, a julgar pela visão (normal e baixa visão).

Quais análises esperam ser feitas?
1. Comparação das notas das provas do ENEM 2019 de participantes com visão normal e baixa visão
2. Comparação dos acertos das provas AZUL e ROSA do ENEM 2019 dos participantes com visão normal e baixa visão

Os resultados das análises acima e toda a contrução da análise de dados para os MICRODADOS do ENEM 2019, podem ser encontrados neste repositório, no seguinte arquivo:
[data_analysis_ENEM](https://github.com/andradearthurf/python-data-analysis/blob/main/cases/data_analisys_ENEM.ipynb)


## Caso 3 - Brazilian E-commerce Public Dataset 

Este conjunto de dados foi generosamente fornecido pela Olist, a maior loja de departamentos dos marketplaces brasileiros. A Olist conecta pequenas empresas de todo o Brasil a canais sem complicações e com um único contrato. Esses comerciantes podem vender seus produtos através da Olist Store e enviá-los diretamente aos clientes usando os parceiros de logística da Olist. 

Dessa forma a Olist gera uma base de dados com todas as informações de pagamentos e vendas, por exemplo, dos comerciantes e lojas. E é em cima dessa base de dados que eu irei realizar a análise exploratória dos dados.

Toda a análise exploratória e toda a contrução das análises de dados para o Brazilian E-commerce Public Dataset, podem ser encontrados neste repositório, no seguinte arquivo:
[data_analysis_BrazilianE-Commerce](https://github.com/andradearthurf/python-data-analysis/blob/main/cases/data_analisys_BrazilianE-Commerce.ipynb)

O dataset principal foi retirado do Kaggle, no seguinte link: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

Todas as análise feitas podem ser encontradas na pasta "cases", cujo a pasta é: [cases](https://github.com/andradearthurf/python-data-analysis/tree/main/cases)

Já os dataframes, para as respectivas análises, se encontram na pasta "data", cujo a pasta é: [data](https://github.com/andradearthurf/python-data-analysis/tree/main/data)


Além disso, foram utilizados arquivos em Jupyter Notebook para facilitar a visualização de toda a construção das análises.

---

O presente repositório está utilizando as seguintes bibliotecas em Python:
- Pandas
- NumPy
- Matplotlib
- Seaborn
