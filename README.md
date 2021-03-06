# Anonimización de Informes Médicos
Proyecto dedicado a la anonimización de los informes médicos obtenidos de la tarea MEDDOCAN (en español).

El proyecto se compone de:

1. Memoria del trabajo (MemoriaTFM.pdf). Se explica todo el proceso realizado para llevar a cabo la anonimización de informes médicos.

2. CódigoTFM. Se encuentra el código realizado para el proyecto y los documentos utilizados. 
  Se ha realizado en Python 3.7. Se apoya principalmente en la librería de spaCy para PLN que usa el corpus AnCora y WikiNER como entrenamiento para textos en español, y la librería CRFsuite para entrenamiento de un modelo de Conditional Random Field.

# Resumen

El presente trabajo propone un modelo supervisado que usa los CRFs (Conditional Random Fields) junto con indicaciones específicas, expresiones regulares y diccionarios para la identificación de información de salud protegida (Protected Health Information o PHI) en los informes de la tarea de desafío de MEDDOCAN. Finalmente, el sistema de este trabajo ha obtenido un F1-score de 0.94, frente al 0.97491 de Bosch Center for Artificial Intelligence (Germany) ganador de esta tarea. Por tanto, podríamos considerar que la propuesta no ha estado mal encaminada. 
