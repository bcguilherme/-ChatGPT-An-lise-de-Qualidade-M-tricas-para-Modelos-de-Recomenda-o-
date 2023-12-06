
# Análise de Qualidade: Métricas para Modelos de Recomendação

Este notebook realiza uma avaliação abrangente da qualidade de recomendações de diversos modelos, incluindo Top, ItemKNN e FunkSVD. Utilizando a biblioteca Rexmex, examinamos métricas como acurácia, cobertura, ranqueamento, classificação e avaliação.

## Conjunto de Dados

- **Metadados dos Itens:** [movies.parquet]
- **Métricas do Conjunto de Validação:** [valid_metrics.parquet]

## Definição de Ranking

A análise inclui a relação entre o tamanho da lista recomendada e as métricas de avaliação.

## Cobertura de Itens

Analisamos a cobertura de itens na recomendação, considerando o tamanho da lista recomendada.

## Métricas de Acurácia

### Personalização e Acurácia de Ranqueamento

Examinamos a recomendação como um problema de ranqueamento, incluindo métricas como MRR (Mean Reciprocal Rank) e personalização.

### Acurácia de Classificação

A recomendação é tratada como um problema de classificação, com métricas como precisão e recall.

### Acurácia de Feedback (Rating)

Analisamos a recomendação como um problema de regressão, avaliando métricas como RMSE (Root Mean Squared Error) e MAE (Mean Absolute Error).

---

**Observação:** Para visualizar os resultados completos, é recomendado explorar o notebook interativamente.
