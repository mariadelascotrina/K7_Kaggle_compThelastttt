# K7_Kaggle_compThelastttt

![image](https://user-images.githubusercontent.com/92324979/144813155-4c22611f-8eef-45c3-be50-8d4226e09774.png)


# ¿Qué?
El objetivo de este proyecto es hacer Machine Learning. Todos los alumnos fuimos convocados a un concurso de Kaggle, en el que, a partir de unos datos ptevios sobre las caracteristicas y el precio de unos diamantes, debíamos predecir el precio de otro grupo de diamantes.
La competición de kaggle fue la siguiente:
https://www.kaggle.com/c/diamonds-datamad1021-rev/overview

# ¿Cómo? 
A partir de dos jupyter notebooks:
1. Clean --> dejamos preparados los datos para poder hacer las predicciones (i) combatimos la colinealidad (a partir del borrado de las columnas que tenían gran correlación, (ii) cambio de los datos de las columnas cualitativas, para poder tener información cuantitativa


2. Prediction --> una vez con los datos preparados para establecer modelos, hacemos (i) un Train test Split para poder "jugar" con los datos que tenemos y saber cómo de verca o lejos estamos de esa predicción. Después (ii) comparamos el rmse (error cuadrático medio) de los diferentes modelos para saber cuál es el mejor. A partir de esto, (iii) sabemos que el Rains Forest es el modelo más óptimo, por lo que procedemos a hacer la predicción con él.


# ¿Qué conseguimos?
Conseguimos un dataser con dos columnas donde la primera es el ID del diamante y la segunda el precio estipulado a través de nuestro modelo. Con esto ¡ya estamos listos para competir!


# Librerías utilizadas
- pandas
- numpy
- seaborn
- sklearn
-          preprocessing
-          train_test_split 
-          LinearRegression as LinReg
-          metrics
-          LogisticRegression
-          accuracy_score, precision_score, recall_score, f1_score, fbeta_score, confusion_matrix
-          balanced_accuracy_score
-          LinearDiscriminantAnalysis
-          KNeighborsClassifier
-          GaussianNB
-          DecisionTreeClassifier
-          SVC
-          Ridge, Lasso
-          SGDRegressor
-          GradientBoostingRegressor
-          SVR
-          RandomForestRegressor
