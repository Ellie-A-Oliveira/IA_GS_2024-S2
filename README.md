# Relatório Técnico: Previsão da Demanda Energética em Comunidades Remotas

## Descrição do Problema
A gestão da demanda energética em comunidades remotas é um desafio significativo, especialmente para aquelas que dependem de fontes de energia renováveis, como solar e eólica. O objetivo deste projeto é prever a demanda de energia para essas comunidades, utilizando dados históricos de consumo e variáveis econômicas.

## Metodologia Utilizada
### Etapas do Projeto
1. **Coleta de Dados:** Dados sobre consumo de energia, PIB, população e feriados foram coletados.
2. **Pré-processamento:** Tratamento de valores ausentes, conversão de formatos e engenharia de atributos.
3. **Modelo de Machine Learning:** Utilização do `HistGradientBoostingRegressor` para prever o consumo de energia.
4. **Validação:** Avaliação do modelo usando as métricas MAE e RMSE.

### Modelo
- **Algoritmo:** HistGradientBoostingRegressor
- **Métricas:**
  - MAE: 239,856.27
  - RMSE: 493,944.55

## Resultados Obtidos
Os resultados indicam que o modelo apresenta um desempenho razoável, mas ainda com um erro significativo. As métricas obtidas mostram que o modelo pode ser melhorado para aplicações em comunidades remotas.

## Conclusões
A solução proposta tem grande potencial para ser utilizada em comunidades remotas, mas é necessário aprimorar o modelo para reduzir os erros de previsão. O uso de fontes renováveis, como solar e eólica, se beneficia de uma gestão otimizada da demanda, e o modelo proposto pode ajudar a alcançar essa otimização.
