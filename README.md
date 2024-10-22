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