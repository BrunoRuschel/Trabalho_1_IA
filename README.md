# Trabalho 1 - Inteligência Artificial
|  Nome | Cartão | Turma |
|---|---|---|
| Marthyna Luiza Weber | 00318166 | B |
| Bruno Tadielo Ruschel | 00550170 | B |
|   |   |   |

## Exercício 1: Regressão Linear
Valores iniciais que resultaram na melhor execução:
- `b` e `w`: iniciados aleatoriamente;
- `alpha`: 0.2;
- `num_iterations`: 150, após isso o erro estabiliza.

Melhor erro quadrático médio obtido: `0.0148`

### Comentários:
Normalizar os dados, (escalar os valores para que fiquem entre 0 e 1) ajudou o modelo a aprender melhor e mais rápido pois quando as features estão na mesma escala, o modelo consegue ajustar os parâmetros b e w com mais equilíbrio, sem deixar uma feature com valores muito grandes atrapalhar o aprendizado das outras e convergindo mais rápido para um erro menor. Os melhores hiperparâmetros dentre os testados foram estimados por tentativa e erro.

## Exercício 2: Tensorflow/Keras
### Características dos datasets:
**MNIST** 
- Número de classes: 10;
- Número de amostras: 60000 imagens de treino e 10000 imagens de teste;
- Tamanho : 28x28x1.

**Fashion MNIST**
- Número de classes: 10;
- Número de amostras: 60000 imagens de treino e 10000 imagens de teste;
- Tamanho : 28x28x1.

**CIFAR-10**
- Número de classes: 10;
- Número de amostras: 50000 imagens de treino e 10000 imagens de teste;
- Tamanho : 32x32x3.

**CIFAR-100**
- Número de classes: 100;
- Número de amostras: 50000 imagens de treino e 10000 imagens de teste;
- Tamanho : 32x32x3.

### 2.1
**MNIST**: é o dataset mais fácil em razão de ter 10 classes, com apenas uma canal de cor e com imagens relativamente simples de serem distinguidas e classificadas após realizada uma convolução. Além disso, possui fundo homogêneo e tem um número de amostras mais do que suficiente para treinamento.

**Fashion MNIST**: é mais difícil que o MNIST pela maior complexidade intrínseca das imagens, uma vez que é mais complicado distinguir peças de roupas por possuírem mais sutilezas do que números manuscritos (MNIST). Ainda assim, é mais simples do que os outros datasets, pois possui apenas 10 classes, um canal de cor e características das imagens mais simples que as demais.

**CIFAR-10**: é mais difícil que os dois anteriores, pois, apesar de ter apenas 10 classes, as imagens possuem uma complexidade intrínseca maior, por se tratarem de objetos mais detalhados e do mundo real, com três canais de cores, não padronizadas e com diferentes posições e iluminações. 

**CIFAR-100**: é o mais complexo de todos. As imagens possuem a mesma complexidade do CIFAR-10, porém há 100 classes e relativamente poucas imagens de treino por classe (500), o que torna mais desafiador para o modelo aprender a distinguir todas as classes com precisão.


## Referências
Frei, Lukas. “Machine Learning from Scratch: Linear Regression - Lukas Frei - Medium.” Medium, Lukas Frei, 23 Dec. 2018, medium.com/lukasfrei/machinelearningfromscratch-linear-regression-b3640d90d7a7. Accessed 22 Oct. 2024.

GeeksforGeeks. “How to Implement a Gradient Descent in Python to Find a Local Minimum ?” GeeksforGeeks, 29 Aug. 2021, www.geeksforgeeks.org/how-to-implement-a-gradient-descent-in-python-to-find-a-local-minimum/.

---. “Hyperparameter Tuning in Linear Regression.” GeeksforGeeks, 1 July 2024, www.geeksforgeeks.org/hyperparameter-tuning-in-linear-regression/.

---. “Python | Mean Squared Error - GeeksforGeeks.” GeeksforGeeks, 28 June 2019, www.geeksforgeeks.org/python-mean-squared-error/.

Moy, Tan. “Multivariate Linear Regression in Python without Scikit-Learn.” Medium, We Are Orb, 17 Dec. 2017, medium.com/we-are-orb/multivariate-linear-regression-in-python-without-scikit-learn-7091b1d45905. Accessed 22 Oct. 2024.

Randunu Galhena. “Select Best Parameters for Regression Model Using Gridsearch.” Stack Overflow, 26 Dec. 2019, stackoverflow.com/questions/59489830/select-best-parameters-for-regression-model-using-gridsearch. Accessed 22 Oct. 2024.

Saturn Cloud. “How to Create a Conda Environment with a Specific Python Version | Saturn Cloud Blog.” Saturncloud.io, 24 Oct. 2023, saturncloud.io/blog/how-to-create-a-conda-environment-with-a-specific-python-version/. Accessed 22 Oct. 2024.

Stack Overflow. “Normalize Dataset in Python.” Stack Overflow, 26 Nov. 2020, stackoverflow.com/questions/65029540/normalize-dataset-in-python. Accessed 22 Oct. 2024.

Krizhevsky, Alex. "CIFAR-10 and CIFAR-100 datasets". Department of Computer Science, University of Toronto, 8 Apr. 2009, https://www.cs.toronto.edu/~kriz/cifar.html. Accessed 30 Oct. 2024.

TensorFlow Datasets. "mnist | Tensorflow Datasets". TensorFlow, 1st Jun. 2023, https://www.tensorflow.org/datasets/catalog/mnist. Accessed 30 Oct. 2024.

TensorFlow Datasets. "fashion_mnist | Tensorflow Datasets". TensorFlow, 23 Nov. 2022, https://www.tensorflow.org/datasets/catalog/mnist. Accessed 30 Oct. 2024.
Stack Overflow. “Normalize Dataset in Python.” Stack Overflow, 26 Nov. 2020, stackoverflow.com/questions/65029540/normalize-dataset-in-python. Accessed 22 Oct. 2024.
