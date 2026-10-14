# Jose Rene García Aroca

# Lab 3.5: Machine Learning Pipeline with Amazon SageMaker

![Evidencia 1](Pantallazos/Imagen%203.5.1.png)

Inicialmente se verificó el estado del repositorio con git status, se agregó el archivo 3_5-machinelearning_es.ipynb con git add para prepararlo para su registro y luego se realizó un commit para guardar los cambios en el historial del repositorio; finalmente, se ejecutó git push origin dev_jogarcia38, con el fin de enviar el notebook actualizado al repositorio remoto y dejar almacenada la actividad desarrollada en SageMaker.

# Importación de los datos

![Evidencia 1](Pantallazos/Imagen%203.5.2.png)

![Evidencia 1](Pantallazos/Imagen%203.5.3.png)

Seguidamente se configuró el modelo XGBoost en Amazon SageMaker, estableciendo los parámetros de configuración y los datos de entrenamiento y validación, con el fin de preparar el modelo para su aprendizaje; luego, se ejecutó el entrenamiento y se verificó que el proceso finalizara correctamente.

# Paso 1: Alojar el modelo

![Evidencia 1](Pantallazos/Imagen%203.5.4.png)

A continuación se utilizaron los datos de entrenamiento y validación previamente almacenados en Amazon S3, para ejecutar el entrenamiento del modelo XGBoost y comprobar que el proceso finalizara correctamente; posteriormente, se inició el alojamiento del modelo mediante Amazon SageMaker, con el fin de dejarlo disponible para realizar predicciones con nuevos datos.

# Paso 2: Realizar predicciones

![Evidencia 1](Pantallazos/Imagen%203.5.5.png)

![Evidencia 1](Pantallazos/Imagen%203.5.6.png)

En esta etapa del laboratorio se revisaron los datos de prueba para conocer su estructura y seleccionar los valores que se utilizarían en la evaluación, asimismo se preparó una fila excluyendo la columna class y se convirtió al formato requerido para enviarla al modelo XGBoost alojado en Amazon SageMaker, con el fin de realizar una predicción, donde se obtuvo el resultado generado por el modelo.

# Paso 3: Terminar el modelo implementado

![Evidencia 1](Pantallazos/Imagen%203.5.7.png)

