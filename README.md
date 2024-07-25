# Cat or Dog
Quiero compartir contigo mi primer proyecto de redes neuronales, en el cual he aplicado *transfer learning*. Los resultados obtenidos son realmente sorprendentes, logrando una precisión superior al 90% en el modelo de clasificación de imágenes.

<p align="center">
  <img src="https://github.com/IsmaDeveloper16/CaTorDog_Tranfer_Learning/blob/main/Proyecto%20CatorDog/imagenes/Presentaci%C3%B3n%20Inteligencia%20Artificial%20Tecnol%C3%B3gica%20Ilustrada%20Azul%20y%20Amarillo%20(1).gif" width="800" height="400" />
</p>

## Objetivo
Este proyecto tiene como objetivo demostrar habilidades en el área de visión por computadora mediante el desarrollo de un clasificador de imágenes utilizando técnicas de transfer learning. El desafío principal es identificar y clasificar imágenes de gatos y perros con alta precisión.

## Características

-  Clasificación de Imágenes: Clasificación binaria de imágenes en las categorías "gatos" y "perros".

-  Transfer Learning: Aplicación de un modelo preentrenado para mejorar la precisión y eficiencia del clasificador.

-  Visualizaciones: Análisis del rendimiento del modelo mediante gráficos de líneas por épocas y matrices de confusión.

## Datos
Los datos para este proyecto fueron proporcionados por la academia INOVE e incluyen:

-  Imágenes de Entrenamiento: 1000 imágenes de gatos y perros.
-  Imágenes de Validación: 500 imágenes de gatos y perros.

### Las imágenes fueron preprocesadas utilizando ImageDataGenerator, que permitió realizar:

-  Reescalado: Ajuste del tamaño de las imágenes a 200x200 píxeles.
-  Generación por Lotes: Manejo eficiente de las imágenes durante el entrenamiento.
-  Normalización: Escalado de los valores de píxeles para mejorar la convergencia del modelo.

Aunque no se aplicó aumento de datos en este proyecto, se identificó como una posible mejora para futuras implementaciones.

## Metodología
-  Transfer Learning: Se utilizó un modelo preentrenado para transferir el aprendizaje y ajustar el clasificador a las imágenes específicas del proyecto.
-  Entrenamiento, Evaluación y prueba: El modelo fue entrenado y evaluado utilizando las imágenes proporcionadas. Tambien realice una prueba con imagenes de algunas mascotas de mis conocidos.
-  Visualizaciones: Se crearon gráficos utilizando matplotlib y seaborn para visualizar el rendimiento del modelo durante el entrenamiento, incluyendo gráficos de líneas por épocas y una matriz de confusión para evaluar la precisión de las clasificaciones.

<p align="center">
  <img src="https://github.com/IsmaDeveloper16/CaTorDog_Tranfer_Learning/blob/main/Proyecto%20CatorDog/imagenes/Presentaci%C3%B3n%20Inteligencia%20Artificial%20Tecnol%C3%B3gica%20Ilustrada%20Azul%20y%20Amarillo%20(1).gif" width="800" height="400" />
</p>
