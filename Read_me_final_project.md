# Proyecto Final Ironhack
## Andrea Evrard

Este proyecto consiste en la creación de un modelo de clasificación para predecir si un paciente va a sufrir un infarto o no. Se parte de un dataset de la web "Kaggle", y en los diferentes documentos se procede a analizar y crear el modelo.

El dataset cuenta con los siguientes **atributos**, y se encuentra en la carpeta "dataset" ubicada en el repositorio del proyecto:
- id : unique identifier
- gender : "Male", "Female" or "Other"
- age : age of the patient
- hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- heart_disease : 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- ever_married : "No" or "Yes"
- work_type : "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
- Residence_type : "Rural" or "Urban"
- avg_glucose_level : average glucose level in blood
- bmi : body mass index
- smoking_status : "formerly smoked", "never smoked", "smokes" or "Unknown"*
- stroke : 1 if the patient had a stroke or 0 if not

En el documento *"Explore_dataset_&_model.ipynb"* se puede encontrar la limpieza de datos y la creación del modelo. En este documento se procede a entender los datos, limpiar los nulls, outliers... eliminar alguna columna que no es relevante y, básicamente proceder con la exploración de datos hasta dejar un dataset limpio y preparado para el modelo. Además, este documento también contiene los diferentes modelos entrenados y testearlos hasta conseguir un modelo que se adecúe al objetivo de este proyecto. El documento de "*SQL.ipynb*" contiene algunas consultas rápidas utilizadas para aplicar cambios al modelo.

Por otro lado, el documento *"Explore_dataset_&_model.html"* es el mismo documento que el anterior, pero en modo presentación.

El documento de *"power_bi_visualization.pbix"* es el documento que contiene los insights más significativos en modo gráficas para que sea más visual y se pueda entender mejor. 

Por último, el documento "*Project_presentation*" es la presentación utilizada para exponer este proyecto.

Es un proyecto muy trabajado y, a pesar de no obtener los resultados deseados al principio, he podido aprender mucho y palpar más de cerca un caso real de Data Analytics.