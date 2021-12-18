# Metrica_ROC_AUC

A métrica Receiver Operating Characteristic (**ROC**)  avalia a qualidade de saída de um classificador (por exemplo: Regressão logística).

As curvas ROC normalmente apresentam taxa de verdadeiro positivo no eixo Y e taxa de falso positivo no eixo X. Isso significa que o canto superior esquerdo do gráfico é o ponto “ideal” - uma taxa de falso positivo de zero e uma taxa de verdadeiro positivo de um. Isso não é muito realista, mas significa que uma área maior sob a curva (**AUC**) geralmente é melhor.

A “inclinação” das curvas ROC também é importante, pois é ideal para maximizar a taxa de verdadeiro positivo enquanto minimiza a taxa de falso positivo.

As curvas ROC são normalmente usadas na classificação binária para estudar a saída de um classificador. Para estender a curva ROC e a área ROC para a classificação multi-rótulo, é necessário binarizar a saída. Uma curva ROC pode ser desenhada por rótulo, mas também se pode traçar uma curva ROC considerando cada elemento da matriz do indicador de rótulo como uma previsão binária (micro-média).

Outra medida de avaliação para a classificação de vários rótulos é a macro-média, que atribui peso igual à classificação de cada rótulo.

Links de estudo:

* [link1](https://medium.com/bio-data-blog/entenda-o-que-%C3%A9-auc-e-roc-nos-modelos-de-machine-learning-8191fb4df772)

* https://www.youtube.com/watch?v=vS6bQy45rdE&t=294s
