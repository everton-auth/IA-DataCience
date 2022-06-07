 # Matriz de confusão.

> A partir dessa matriz, calcula-se a acurácia, precisão, score e a sensibilidade do modelo.


 Forma de imaginação clássica da matriz confusa =>

~~~~     
          ["CLASSE ATUAL" ]
          [     | P  | N  ]
 [CLASSE  [   P | TP | FP ]
 PREDITA] [   N | FN | TN ]
~~~~


Cálculo de acurácia => 

Accuracy = (TP + TN) / (TP + FP + TN + FN)


  + P = Positivo
  + N = Negativo
  + TP = Positivo Verdadeiro (True Positive)
  + FP = Falso Positivo (False Positive)
  + TN = Negativos Verdadeiros (False True)
  + TN = Verdadeiros Negativos (true False)



[   60 || 13   ]
[   05 || 58   ]