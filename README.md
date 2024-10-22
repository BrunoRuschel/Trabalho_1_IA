# Trabalho 1 - Inteligência Artificial
|  Nome | Cartão | Turma |
|---|---|---|
| Marthyna Luiza Weber | 00318166 | B |
|   |   |   |
|   |   |   |
## Exercício 1: Regressão Linear
Valores iniciais que resultaram na melhor execução:
- `b` e `w`: iniciados aleatoriamente;
- `alpha`: 0.2;
- `num_iterations`: 150, após isso o erro estabiliza.

Melhor erro quadrático médio obtido: `0.0148`

### Comentários:
Normalizar os dados, (escalar os valores para que fiquem entre 0 e 1) ajudou o modelo a aprender melhor e mais rápido pois quando as features estão na mesma escala, o modelo consegue ajustar os parâmetros b e w com mais equilíbrio, sem deixar uma feature com valores muito grandes atrapalhar o aprendizado das outras e convergindo mais rápido para um erro menor. Os melhores hiperparâmetros dentre os testados foram estimados por tentativa e erro.

## Referências
Frei, Lukas. “Machine Learning from Scratch: Linear Regression - Lukas Frei - Medium.” Medium, Lukas Frei, 23 Dec. 2018, medium.com/lukasfrei/machinelearningfromscratch-linear-regression-b3640d90d7a7. Accessed 22 Oct. 2024.

GeeksforGeeks. “How to Implement a Gradient Descent in Python to Find a Local Minimum ?” GeeksforGeeks, 29 Aug. 2021, www.geeksforgeeks.org/how-to-implement-a-gradient-descent-in-python-to-find-a-local-minimum/.

---. “Hyperparameter Tuning in Linear Regression.” GeeksforGeeks, 1 July 2024, www.geeksforgeeks.org/hyperparameter-tuning-in-linear-regression/.

---. “Python | Mean Squared Error - GeeksforGeeks.” GeeksforGeeks, 28 June 2019, www.geeksforgeeks.org/python-mean-squared-error/.

Moy, Tan. “Multivariate Linear Regression in Python without Scikit-Learn.” Medium, We Are Orb, 17 Dec. 2017, medium.com/we-are-orb/multivariate-linear-regression-in-python-without-scikit-learn-7091b1d45905. Accessed 22 Oct. 2024.

Randunu Galhena. “Select Best Parameters for Regression Model Using Gridsearch.” Stack Overflow, 26 Dec. 2019, stackoverflow.com/questions/59489830/select-best-parameters-for-regression-model-using-gridsearch. Accessed 22 Oct. 2024.

Saturn Cloud. “How to Create a Conda Environment with a Specific Python Version | Saturn Cloud Blog.” Saturncloud.io, 24 Oct. 2023, saturncloud.io/blog/how-to-create-a-conda-environment-with-a-specific-python-version/. Accessed 22 Oct. 2024.

Stack Overflow. “Normalize Dataset in Python.” Stack Overflow, 26 Nov. 2020, stackoverflow.com/questions/65029540/normalize-dataset-in-python. Accessed 22 Oct. 2024.