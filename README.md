**Description**

¡Hola a todos! ¡Bienvenidos al IA Project 1!
Clasificación de Enfermedad Cardíaca

Este proyecto de datos tiene como objetivo la detección de enfermedad cardiaca mediante el análisis de un conjunto de datos que contiene información sobre múltiples pacientes con diferentes grados de enfermedad o ausencia de la misma.

Esta tarea parece sencilla, sin embargo, debemos ser conscientes de la importancia de proporcionar una solución a este tipo de problemas y el gran avance que supone en la práctica clínica. La detección temprana de enfermedades cardiovasculares en el momento del ingreso o la consulta médica puede salvar o mejorar la calidad de vida de los pacientes, por ello, desarrollar modelos precisos y eficientes puede ayudar a los profesionales médicos en la toma de decisiones clínicas y en la personalización de los tratamientos.

Este desafío consiste en entrenar un modelo de aprendizaje automático que pueda predecir la presencia de enfermedad en el corazón basándose en las características recogidas en diferentes pruebas médicas como variables clínicas.

**Evaluation**
F1 Score (micro)

**Etiquetas**
El conjunto de datos se proporciona en formato CSV (train.csv) y contiene información sobre 732 pacientes con diferentes grados de enfermedad (1-4) o ausencia de la misma (0). Este dato puede obtenerse de la columna 'label'

**Características**
Además, el conjunto de datos está compuesto por 13 características adicionales que describen las condiciones de salud de cada uno de los pacientes. Estas características se describen a continuación:

- age: edad del paciente

- sex: sexo del paciente
    - 0: mujer
    - 1: hombre

- cp: tipo de dolor de pecho:
  - 1 : angina típica
  - 2 : angina atípica
  - 3 : dolor no-anginoso
  - 4 : asintomático

- trestbps: presión arterial en reposo (en mm Hg al ingreso en el hospital)

- chol: colesterol sérico en mg/dl

- fbs: dolor provocado por el esfuerzo (1 = sí; 0 = no)

- restecg: resultados electrocardiográficos en reposo
0: normal
1: presenta anormalidad de la onda ST-T
2: presenta probable o definida hipertrofia ventricular izquierda

- thalach: frecuencia cardiaca en reposo

- exang: angina inducida por el ejercicio (1 = sí; 0 = no)

- oldpeak: depresión del ST inducida por el ejercicio en relación con el reposo

- slope: la pendiente del segmento ST en ejercicio máximo
1: pendiente ascendente
2: plano
3: pendiente descendente

- ca: número de vasos mayores (0-3) coloreados por flouroscopia

- thal:
3: normal
6: defecto fijo
7: defecto reversible
