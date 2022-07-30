# book_training

# Machine learning na prática

Exercícios práticos do livro **Hands-on: ML with Scikit-learn, Keras and TensorFlow** - Aurélien Géron - 2nd Editiion

**Repositório do autor** [GitHub 2nd Edition](https://github.com/ageron/handson-ml2) [Github 3rd edition](https://github.com/ageron/handson-ml3)

Em desenvolvimento alguns exercícios com os procedimentos de machine learning, sendo reestruturados para prática.

# **Capítulo 1**
O exercício 1, explora-se a definição de um simples modelo de regressão, medindo a indice de satisfação de vida e o PIB per capita


## Regressão linear – Em termo gerais
Equação

### ŷ= θ_0+θ_1 x_1+θ_2 x_2+⋯+θ_n x_n 

Nessa equação temos:

ŷ – valor previsto

n – número de característica

xi – Valor da iésima características

θj – o j-ésimo parâmetro do modelo, incluindo o viés θ_0 e os pesos θ_1', ... θ_n'. 

Busca-se investigar se o dinheiro traz felicidades as pessoas, com os dados de índice de vida melhor no site da OCDE e dos dados sobre o PIB e da renda per capita no site do FMI.

**Equação direta – forma fechada, Abordagem otimizada iterativa e Regressão polinomial**

Modelagem dos dados

Estimação do modelo de regressão simples

Ajustar os dados

Estimação de modelo linear com dados ajustado

Comparação de modelos

# Capitulo 2

## Nesta seção apresenta-se o processo de estimação de ponta a ponta

### Análise do panorama geral
>Nesta tarefa criaremos um modelo de preços para o setor imobiliário usando dados censo da Califórnia. Os dados possuem indicadores para cada grupo de bairros como população, renda média e preço médio do imóvel. Os grupos de bairros serão abreviados por regiões.
>Este modelo propõe aprendizado com os dados e a possibilidade de realizar previsão de preço médio do imóvel considerando todos os indicadores e em qualquer região.
>O objetivo é apresentar uma predição do preço médio dos imóveis para alimentar outros sistemas que recebem outros sinais, onde estabelecerá se vale a pena ou não investir em determinada região.
>Como medida de desempenho utiliza-se a raiz do erro quadrático médio (RMSE), para se ter uma base dos erros gerados pelo sistema nas predições

### Obtenção dos dados

>Dados obtidos no repositório do autor [Github 3rd edition](https://github.com/ageron/handson-ml3)

### Identificar e visualizar os dados para coletar as informações relevantes

### Preparar os dados para o algoritimo

### Selecionar e treinar o modelo

### Aperfeiçoar o modelo

### Apresentar uma solução

### Disponibilizar em produção, monitorar e fazer manutenção do sistema
