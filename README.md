
## Estudiante
Aaron Elizondo Vargas
# Adult Income
El objetivo de este proyecto es crear un modelo capaz de identificar el ingreso de la población adulta, siendo el objetivo determinar si es menor o igual a 50k o mayor a 50k.



## Herramientas de Software

Las siguientes bibliotecas de Python han sido utilizadas en el proyecto
 - pandas as pd
 - seaborn as sns
 - matplotlib as plt
 - os
 - numpy
 - math



## Conjunto de Datos

El conjunto de datos es una rica colección de 32561 registros y 14 variables o columnas que incluyen:

- age: una medida continua de la edad.
- workclass: una clasificación del tipo de trabajo que incluye   categorías como Privado, Autoempleo, Gobierno, entre otros.
- fnlwgt: una medida continua del peso final.
- education: una clasificación del nivel de educación que abarca desde preescolar hasta doctorado.
- education-num: una medida continua del número de años de educación.
- marital-status: una representación del estado civil y el papel familiar.
- occupation: una clasificación del tipo de ocupación.
- relationship: una representación del papel familiar.
- race: una clasificación de la raza.
- sex: una clasificación del género.
- capital-gain: una medida continua de las ganancias de inversión.
- capital-loss: una medida continua de las pérdidas de inversión.
- hours-per-week: una medida continua de las horas trabajadas por semana.
- native-country: una clasificación del país de origen.

## Objetivo del Proyecto
El objetivo es predecir la variable Income, que puede ser menor o igual a 50k o mayor a 50k.

## Modelos de Aprendizaje Automático Implementados
Se exploraron varios modelos de aprendizaje automático, incluyendo:

- LogisticRegression
- DecisionTreeClassifier
- SVC
- KNeighborsClassifier
- RandomForestClassifier.

Finalmente, KNeighborsClassifier y RandomForestClassifier demostraron ser los más prometedores, alcanzando puntuaciones máximas de 90 y 91 respectivamente.
