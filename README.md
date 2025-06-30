# Text_Mining
detección de profesiones mencionadas en textos publicados en Twitter durante la pandemia de COVID19. Con esos datos, deberás desarrollar un clasificador binario que, dado un tweet, determine si menciona al menos una profesión (etiqueta 1) o no ( etiqueta 0)


El propósito de este ejercicio es aplicar los conocimientos adquiridos sobre análisis exploratorio de datos
textuales y entrenamiento de modelos supervisados, utilizando datos reales extraídos de redes sociales.
Trabajarás con datos de la shared-task ProfNER, específicamente con los de la Tarea 1, que se centra en la
detección de profesiones mencionadas en textos publicados en Twitter durante la pandemia de COVID19. Con esos datos, deberás desarrollar un clasificador binario que, dado un tweet, determine si menciona
al menos una profesión (etiqueta 1) o no ( etiqueta 0). Esta tarea permite identificar contenido
relacionado con ocupaciones, con el objetivo de analizar qué profesiones podrían haber sido más
vulnerables durante la crisis sanitaria.
Recursos proporcionados
• Un notebook de Google Colab con la estructura básica del ejercicio. Incluye funciones y celdas
predefinidas que no deben ser modificadas.
• Un conjunto de datos en formato dataset de Hugging Face, que contiene:
o Datos de entrenamiento: con identificadores, texto y etiquetas.
o Datos de validación: con la misma estructura que el conjunto de entrenamiento.
o Datos de prueba (test): solo incluye identificadores y texto (sin etiquetas)1
.
Tareas a llevar a cabo:
1. Análisis Exploratorio de Datos:
• Calcular estadísticas básicas: número de documentos, distribución de clases, longitud de
los textos, etc.
• Crear visualizaciones (por ejemplo, wordclouds) para entender mejor el contenido del
dataset.
2. Selección y justificación del modelo
• Elegir un modelo preentrenado de HuggingFace adecuado para el idioma y la naturaleza
de los datos.
• Justificar claramente por qué se ha seleccionado ese modelo.
3. Entrenamiento del clasificador.
• Entrenar el modelo de forma reproducible.
• Evaluar su rendimiento sobre el conjunto de validación.
4. Generación de predicciones sobre el test
• Aplicar el modelo entrenado sobre el conjunto de test.
• Guardar las predicciones en un archivo -tsv
