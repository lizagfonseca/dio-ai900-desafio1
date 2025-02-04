# dio-ai900-desafio1
> Criação de modelo de regressão `bike-rentals` através do Microsoft Azure ML

### Passo-a-passo da tarefa
1. O _workspace_ foi configurado através do [Azure portal](https://portal.azure.com)
2. No [Azure ML Studio](https://ml.azure.com/?azure-portal=true) foi então criado um trabalho ML automatizado para determinar o preço de aluguel de bicicletas, utilizando o dataset `bike-rentals`, disponibilizado pela Microsoft. Foram configurados os modelos `RandomForest` e `LightGBM` para a regressão, tendo como métrica primária `NormalizedRootMeanSquaredError` e separando 90% do dataset para treino e 10% para validação. O restante da configuração está disponível no tutorial da [Microsoft Learn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html).
4. Com o modelo treinado, o melhor conjunto de parâmetros foi selecionado para ser implementado.
5. Ao testar o modelo utilizando o _template_ JSON disponibilizado na página do tutorial, foi obtido e salvo o JSON de resultado.

### Conclusão
Com esse desafio, foi possível aprender como utilizar o ambiente do Azure ML para treinar, implementar e testar um modelo de aprendizado de máquina, configurando os parâmetros e observando as métricas de resultado para verificar a eficácia do modelo.
