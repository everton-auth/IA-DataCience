 # Matriz de confusão.

> A partir dessa matriz, calcula-se a acurácia, precisão, score e a sensibilidade do modelo.


 Forma de imaginação clássica da matriz confusa =>

~~~~     
          ["CLASSE ATUAL" ]
          [     | P  | N  ]
 [CLASSE  [   P | TP | FP ]
 PREDITA] [   N | FN | TN ]
~~~~



  + P = Positivo 
  + N = Negativo
  + TP = Positivo Verdadeiro (True Positive) => pessoas que testaram positivo para diabetes e que o sistema previu positivo.
  + FP = Falso Positivo (False Positive) => pessoas que testaram negativo para diabetes e que o sistema previu positivo.
  + TN = Negativos Verdadeiros (False True) => pessoas que testaram negativo para diabetes e que o sistema previu negativo.
  + FN = Verdadeiros Negativos (true False) => pessoas que testaram positivo para diabetes e que o sistema previu negativo.

 ## Cálculo de acurácia.
![(TP + TN) / (TP + FP + TN + FN)](../assets/accuracy.png)


## Cálulo de taxa de erro.
![1 - accuracy](../assets/error-rate.png)

## Cálculo de precisão.
![TP / (TP + FP)](../assets/precision.png)

## Cálculo de sensibilidade.
![TP / (TP + FN)](../assets/sensibility.png)

## Cálculo de especificidade.
![TN / (TN + FP)](../assets/specitivity.png)

## Cálculo de F1-Score (média harmônica)
![(2 * (precision * sensibility)) / (precision + sensibility )](../assets/F1-score.png)

## Sensibilidade VS Especificidade
![](../assets/peso-de-decisao.png)
