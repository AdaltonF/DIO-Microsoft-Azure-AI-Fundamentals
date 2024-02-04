# Trabalhando com Machine Learning

A seguir, há imagens do passo a passo apresentado no vídeo e na [documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#create-an-azure-machine-learning-workspace).

Todas as intruções seguidas estão documentadas no link acima.

## Criando um espaço de trabalho no Azure Machine Learning

Inicialmente, é criado o workspace(espaço de trabalho) no Portal Azure. Podendo ser acessado como na imagem abaixo.

![Imagem 0](../img/01/0.png)

## Usando ML Automatizado para treinar um modelo

Como o workspace criado, é possível utilizar o ML Automatizado para obter o melhor modelo de acordo com a base de dados fornecida.

![Imagem 1](../img/01/1.png)

## Revisando melhor modelo

É feita a avaliação do melhor modelo encontrado, como na imagem abaixo.

![Imagem 2](../img/01/2.png)

Algumas métricas estão disponíveis para análise de cada modelo. Abaixo, é possível visualizar o gráfico que representa a acurácia da predições obtidas por meio da regressão.

![Imagem 3](../img/01/3.png)

## Implementado(deploy) o modelo

Cria um serviço Web para que seja possível utilizar o modelo treinado.

![Imagem 4](../img/01/4.png)

## Teste do serviço implementado

É feito um teste obtendo o resultado ```362.49143675357624```.

![Imagem 5](../img/01/5.png)