# Projeto - Ensaio de Machine Learning

![Ensaio de Machine Learning](/img/andrea-de-santis-zwd435-ewb4-unsplash.jpg)
## 1. Problema de Negócio

  * Descrição
    
    A empresa Data Money acredita que a expertise no treinamento e ajuste fino dos algoritmos, feito pelos Cientistas de Dados da empresa, é o principal motivo dos ótimos resultados que as consultorias vem entregando aos seus clientes.

  * Objetivo

    O objetivo desse projeto será realizar ensaios com algoritmos de Classificação, Regressão e Clusterização, para estudar a mudança de comportamento da performance, medida que os valores dos parâmetros de controle de overfitting e underfitting mudam.

## 2. Planejamento da Solução

 * Produto Final

    O produto final será 7 tabelas mostrando a performance dos algoritmos, avaliados usando múltiplas métricas, para 3 conjuntos de dados diferentes: Treinamento, validação e teste.

 * Algoritmos Ensaiados

   ### Classificação
   ---
   Algoritmos: KNN, Decision Tree, Random Forest e Logistic Regression.

   Métricas de performance: Accuracy, Precision, Recall e F1-Score.

   ### Regressão
   ---
   Algoritmos: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polynomial Regression, Linear Regression Lasso, Linear Regression Ridge, Linear Regresion Elastic Net, Polynomial Regression Lasso, Polynomial Regression Ridge e Polynomial Regression Elastic Net.

   Métricas de performance: R2, MSE, RMSE, MAE e MAPE.

   ### Clustering
   ---
   Algoritmos: K-Means e Affinity Propagation.

   Métricas de performance: Silhouette Score.

* Ferramentas Utilizadas
  Python 3.11 e Scikit-Learn

## 3. Desenvolvimento
* Estratégia de Solução
  
  Para o objetivo de ensaiar os algoritmos de Machine Learning, eu vou escrever os códigos utilizando a linguagem Python, para treinar cada um dos algoritmos e vou variar seus principais parâmetros de ajuste de overfitting e observar a métrica final.

  O conjunto de valores que fizerem os algoritmos alcançarem a melhor performance, serão aqueles escolhidos para o treinamento final do algoritmo.

  <details>
  <summary>Passo a Passo</summary>
   Passo 1 -> Divisão dos dados em treino, teste e validação.


   Passo 2 -> Treinamento dos algoritmos com os dados de treinamento, utilizando os parâmetros “default”.
  
   Passo 3 -> Medir a performance dos algoritmos treinados com o parâmetro default, utilizando o conjunto de dados de treinamento.
  
   Passo 4 -> Medir a performance dos algoritmos treinados com o parâmetro “default”, utilizando o conjunto de dados de validação.
  
   Passo 5 -> Alternar os valores dos principais parâmetros que controlam o overfitting do algoritmo até encontrar o conjunto de parâmetros apresente a melhor performance dos algoritmos.
  
   Passo 6 -> Unir os dados de treinamento e validação
  
   Passo 7 -> Retreinar o algoritmo com a união dos dados de treinamento e validação, utilizando os melhores valores para os parâmetros de controle do algoritmo.
  
   Passo 8 -> Medir a performance dos algoritmos treinados com os melhores parâmetro, utilizando o conjunto de dados de teste.
  
   Passo 9 -> Avaliar os ensaios e anotar os 3 principais Insights que se destacaram.
  </details>

## 4. Os top 3 Insights

### Insight Top 1
Os algoritmos baseados em árvores possuem uma performance melhor em todas as métricas, quando aplicados sobre os dados de teste, no ensaio de classificação.

### Insight Top 2
A performance dos algoritmos de classificação sobre os dados de validação ficou bem próxima da performance sobre os dados de teste.

### Insight Top 3
Todos os algoritmos de regressão não apresentam boas métricas de performance, o que mostra uma necessidade de uma seleção de atributos e uma preparação melhor das variáveis dependentes do conjunto de dados.

## 5. Resultados
Os resultados serão povoados aqui conforme a evolução do projeto e dos estudos, onde cada algoritmo será avaliado separadamente.

### Ensaio de Classificação
<details>
  <summary>Sobre os Dados de Treinamento</summary>
  
  | Algorithm            | Accuracy | Precision | Recall  | F1_score |
  |----------------------|----------|-----------|---------|----------|
  | KNN                  | x | x  | x|      x    |x
  | Decision Tree        | x | x  | x|          |
  | Random Forest        | x | x
</details>

<details>
  <summary>Sobre os Dados de Validação</summary>
  
  | Algorithm            | Accuracy | Precision | Recall  | F1_score |
  |----------------------|----------|-----------|---------|----------|
  | KNN                  | x | x  | x|      x    |x
  | Decision Tree        | x | x  | x|          |
  | Random Forest        | x | x
</details>

<details>
  <summary>Sobre os Dados de Teste</summary>
  
  | Algorithm            | Accuracy | Precision | Recall  | F1_score |
  |----------------------|----------|-----------|---------|----------|
  | KNN                  | x | x  | x|      x    |x
  | Decision Tree        | x | x  | x|          |
  | Random Forest        | x | x
</details>

---

### Ensaio de Regressão
<details>
  <summary>Sobre os Dados de Treinamento</summary>
  
  | Algorithm                        | R2        | MSE       | RMSE      | MAE       | MAPE      |
  |----------------------------------|-----------|-----------|-----------|-----------|-----------|
  | Baseline                         | x  | x| x | x |           |
  | Linear Regression                | x  | x| x | x |           |
  | Decision Tree                    | x  | x| x | x |           |
  | Random Forest                    | x  | x | x  | x  |           |
  | Polynomial Regression            | x  | x| x | x |           |
  | Linear Regression Lasso           | x  | x| x | x |           |
  | Linear Regression Ridge           | x  | x|x | x |           |
  | Linear Regression Elastic Net     | x  | x| x | x |           |
  | Polynomial Regression Lasso       | x  | x| x | x |           |
  | Polynomial Regression Ridge       | x  | x| x | x |           |
  | Polynomial Regression Elastic Net | x  | x| x | x |           |
  
</details>

<details>
  <summary>Sobre os Dados de Validação</summary>
  
  | Algorithm                        | R2        | MSE       | RMSE      | MAE       | MAPE      |
  |----------------------------------|-----------|-----------|-----------|-----------|-----------|
  | Baseline                         | x  | x| x | x |           |
  | Linear Regression                | x  | x| x | x |           |
  | Decision Tree                    | x  | x| x | x |           |
  | Random Forest                    | x  | x | x  | x  |           |
  | Polynomial Regression            | x  | x| x | x |           |
  | Linear Regression Lasso           | x  | x| x | x |           |
  | Linear Regression Ridge           | x  | x|x | x |           |
  | Linear Regression Elastic Net     | x  | x| x | x |           |
  | Polynomial Regression Lasso       | x  | x| x | x |           |
  | Polynomial Regression Ridge       | x  | x| x | x |           |
  | Polynomial Regression Elastic Net | x  | x| x | x |           |
  
</details>

<details>
  <summary>Sobre os Dados de Teste</summary>
  
  | Algorithm                        | R2        | MSE       | RMSE      | MAE       | MAPE      |
  |----------------------------------|-----------|-----------|-----------|-----------|-----------|
  | Baseline                         | x  | x| x | x |           |
  | Linear Regression                | x  | x| x | x |           |
  | Decision Tree                    | x  | x| x | x |           |
  | Random Forest                    | x  | x | x  | x  |           |
  | Polynomial Regression            | x  | x| x | x |           |
  | Linear Regression Lasso           | x  | x| x | x |           |
  | Linear Regression Ridge           | x  | x|x | x |           |
  | Linear Regression Elastic Net     | x  | x| x | x |           |
  | Polynomial Regression Lasso       | x  | x| x | x |           |
  | Polynomial Regression Ridge       | x  | x| x | x |           |
  | Polynomial Regression Elastic Net | x  | x| x | x |           |
  
</details>

---

### Ensaio sobre Clusterização

<details>
  <summary>Sobre os Dados de Treinamento</summary>
  
  | Algorithm             | Clusters | Silhouette Score |
  |-----------------------|----------|------------------|
  | KMeans                | x       |                  |
  | AffinityPropagation   | x       |                  |
  
</details>


## 6. Conclusões
  Nesse ensaio de Machine Learning, consegui adquirir experiência e entender melhor sobre os limites dos algoritmos entre os estados de underfitting e overfitting.

  Algoritmos baseados em árvores são sensíveis quanto a profundidade do crescimento e do número de árvores na floresta, fazendo com que a escolha correta dos valores desses parâmetros impeçam os algoritmos de entrar no estado de overfitting.

  Os algoritmos de regressão, por outro lado, são sensíveis ao grau do polinômio. Esse parâmetro controla o limite entre o estado de underfitting e overfitting desses algoritmos.

  Esse ensaio de Machine Learning foi muito importante para aprofundar o entendimento sobre o funcionamento de diversos algoritmos de classificação, regressão e clusterização, e quais os principais parâmetros de controle entre os estados de underfitting e overfitting.

## 7. Próximos Passos
  Os próximos passos são: 
  1. Aprimorar esse Ensaio ao longo do tempo, junto com os estudos e o avanço do projeto para cada algoritmo de Machine Learning.

  2. Trazer funções visuais para o Ensaio, facilitando a visão de resultados por recrutadores/comunidade.
