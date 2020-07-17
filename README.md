### Comparação de modelos e transformação de dados para análise de crédito

O objetivo deste foi comparar quatro abordagens distintas para modelagem de informações de crédito, considerando bases balanceados, desbalanceadas e preditoras trsnformadas por WOE, bem como em sua escala originais. No processo de modelagem foram utilizados os algoritmos de Random Forest, Redes Neurais, AdaBoost, Gradient Boosting e Regressão Logística, em cada um destes casos foram realizadas permutações nos hiperparâmetros dos modelos(tuning), com o intuito de selecionar o melhor modelo para cada um dos quatro cenários.

<img align="center" width="600" height="400"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/donut3.png">

Como é possível verificar a distribuição da variável targe é relativamente desbalanceada, deste modo, foi realizada um undersampling na base, para 

<img align="center" width="800" height="500"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/hist3.png">

<img align="center" width="800" height="500"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/Box3.png">

<img align="center" width="600" height="400"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/cor1.png">

<img align="center" width="800" height="1300"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/WOE2.png">

<img align="center" width="500" height="300"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/balanc.png">

<img align="center" width="800" height="700"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/ordena.png">

<img align="center" width="800" height="1900"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/ranks.png">

<img align="center" width="800" height="400"  src="https://github.com/WOLFurriell/BehaviorScorePython/blob/master/plots/compara.png">

