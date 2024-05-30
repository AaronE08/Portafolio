1.**Descripcion:**
El objetivo del proyecto es crear un modelo capaz de identificar el ingreso de la poblacion adulta siendo el objetivo menor o igual a 50k o mayor a 50k.

**bibliotecas utilizadas en el proyecto:**

-import pandas as pd

-import matplotlib as plt

-import seaborn as sns

-import os

-import numpy as np

-import math as mat

2.**Características**

age: continuo.

workclass: Privado, Autoempleo no incluido, Autoempleo incluido, Gobierno federal, Gobierno local, Gobierno estatal, Sin remuneración, Nunca trabajado.

fnlwgt: peso final, continuo.

education: Licenciatura, Alguna universidad, 11.°, Graduado de secundaria, Escuela profesional, Assoc-acdm, Assoc-voc, 9.°, 7.°-8.°, 12.°, Maestría, 1.°-4.°, 10.°, Doctorado, 5.°-6.°, Preescolar.

education-num: continuo.

marital-status: Representa el papel de la unidad que responde en la familia. Casado-cónyuge civil, Divorciado, Nunca casado, Separado, Viudo, Casado-cónyuge ausente, Casado-cónyuge AF.

occupation: Soporte técnico, Reparación de embarcaciones, Otros servicios, Ventas, Ejecutivo-gerencial, Profe-especialidad, Manipuladores-limpiadores, Inspección de máquinas, Adm-administrativo, Agricultura-pesca, Transporte-mudanza, Servicio privado , Servicio de protección, Fuerzas Armadas.

relationship: Representa el papel de la unidad que responde en la familia. Esposa, Hijo propio, Marido, No perteneciente a la familia, Otro pariente, Soltero.

race: Blanco, asiático-isleño del Pacífico, amer-indio-esquimal, otro, negro.

sex: Mujer hombre.

capital-gain: ingresos procedentes de fuentes de inversión, aparte de sueldos/salarios, continuos.

capital-loss: pérdidas por fuentes de inversión, aparte de sueldos/salarios, continuas.

hours-per-week: continuo.

native-country: Estados Unidos, Camboya, Inglaterra, Puerto Rico, Canadá, Alemania, Estados Unidos periféricos (Guam-USVI-etc), India, Japón, Grecia, Sur, China, Cuba, Irán, Honduras, Filipinas, Italia, Polonia, Jamaica, Vietnam, México, Portugal, Irlanda, Francia, República-Dominicana, Laos, Ecuador, Taiwán, Haití, Colombia, Hungría, Guatemala, Nicaragua, Escocia, Tailandia, Yugoslavia, El-Salvador, Trinadad&Tobago, Perú, Hong, Holanda- Países Bajos.

3.**Objetivo:**
-Income(menor o igual a 50k o mayor a 50k)

4.**Se utilizaron los siguientes modelos:**

-LogisticRegression

-DecisionTreeClassifier

-SVC

-KNeighborsClassifier

-RandomForestClassifier.

Se eligio solamente KNeighborsClassifier y RandomForestClassifier con una puntuacion maxima de 90 para -KNeighborsClassifiery 91 para RandomForestClassifier

5.**El conjunto de datos consta de 32561 y 14 columnas**




