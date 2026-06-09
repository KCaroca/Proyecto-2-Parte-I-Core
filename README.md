# Proyecto 2 – Análisis Inicial y Selección de Problema

## Descripción

El presente proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre distintos conjuntos de datos provenientes de diferentes dominios, con el propósito de comprender sus características, evaluar la calidad de la información disponible e identificar posibles problemáticas susceptibles de ser abordadas mediante técnicas de ciencia de datos y aprendizaje automático. La correcta selección del problema constituye una etapa fundamental para el desarrollo posterior de modelos predictivos y la generación de conocimiento útil para la toma de decisiones.

## Conjuntos de Datos Analizados

### 1. Salud Mental en Jóvenes

**Fuente:** Kaggle.

Este conjunto de datos contiene información relacionada con variables demográficas, hábitos de vida, condiciones académicas y factores asociados a la salud mental de jóvenes, permitiendo estudiar posibles factores de riesgo y patrones relacionados con alteraciones en el bienestar psicológico.

### 2. Rendimiento Académico de Estudiantes

**Fuente:** Kaggle.

El dataset reúne antecedentes académicos, familiares y sociales de estudiantes, incluyendo hábitos de estudio, ausencias y desempeño académico, facilitando el análisis de variables relacionadas con el rendimiento y el bienestar estudiantil.

### 3. Riesgo Materno en Gestantes

**Fuente:** Kaggle.

Este conjunto de datos contiene información clínica y demográfica de mujeres embarazadas, permitiendo evaluar factores asociados al riesgo materno durante la gestación y apoyar la identificación temprana de casos de mayor complejidad.

### 4. Fetal Health

**Fuente:** Kaggle.

El dataset contiene registros cardiotocográficos utilizados para evaluar el estado de salud fetal. Su objetivo es clasificar los casos en categorías normales, sospechosas o patológicas a partir de variables biomédicas.

## Resumen del EDA Inicial

### Salud Mental en Jóvenes

Se identificaron variables numéricas y categóricas relevantes para el análisis. Sin embargo, durante la exploración inicial se observaron distribuciones excesivamente simétricas y estadísticas descriptivas poco consistentes con la variabilidad esperada en este tipo de fenómenos, lo que generó dudas respecto de la representatividad del conjunto de datos para etapas posteriores de modelado predictivo.

### Rendimiento Académico de Estudiantes

Se observaron variables académicas y familiares potencialmente asociadas con el desempeño estudiantil. Asimismo, se identificaron algunos valores faltantes que requerirán tratamiento previo al análisis predictivo.

### Riesgo Materno en Gestantes

El conjunto presenta variables clínicas relevantes para la evaluación del riesgo durante el embarazo. Se identificaron diferencias entre grupos de riesgo, ausencia de valores extremos problemáticos y una variable objetivo claramente definida, características que favorecen la construcción de modelos de clasificación supervisada.

### Fetal Health

El dataset incluye variables biomédicas derivadas del monitoreo fetal. Se observaron algunas categorías con menor representación, aspecto que deberá considerarse durante etapas posteriores de modelado para evitar sesgos en la clasificación.

## Problema Seleccionado

### Descripción del problema

El problema seleccionado consiste en predecir el nivel de riesgo materno durante la gestación utilizando información clínica y demográfica de mujeres embarazadas. El objetivo es desarrollar un modelo de clasificación capaz de identificar tempranamente gestantes con mayor probabilidad de presentar complicaciones, apoyando la toma de decisiones preventivas y la priorización de la atención en salud.

### Tipo de problema

**Clasificación supervisada.**

### Justificación

Tras realizar el análisis exploratorio de los cuatro conjuntos de datos, se seleccionó el dataset de **Riesgo Materno en Gestantes** debido a su relevancia práctica, la calidad aparente de los datos y la existencia de una variable objetivo claramente definida.

A diferencia de otros conjuntos analizados, este dataset presenta características coherentes con el fenómeno estudiado y variables clínicas directamente relacionadas con la problemática de interés. Asimismo, el problema posee una importante utilidad social, ya que la identificación temprana del riesgo durante el embarazo puede contribuir al desarrollo de estrategias preventivas y a una mejor asignación de recursos sanitarios.

Desde la perspectiva de la ciencia de datos, este conjunto constituye un escenario apropiado para la aplicación de técnicas de clasificación supervisada, incorporando procesos de preprocesamiento, optimización de modelos y evaluación comparativa mediante distintas métricas de desempeño.

## Objetivos específicos

* Explorar las variables clínicas y demográficas asociadas al riesgo materno durante la gestación.
* Identificar factores potencialmente relacionados con la clasificación del nivel de riesgo.
* Aplicar técnicas de limpieza y preprocesamiento de datos.
* Construir y comparar modelos de clasificación para predecir el riesgo materno.
* Evaluar el desempeño de los modelos utilizando métricas apropiadas para problemas de clasificación.

## Instrucciones para Ejecutar

1. Clonar o descargar el repositorio desde GitHub.
2. Instalar las librerías necesarias: pandas, numpy, matplotlib y seaborn.
3. Abrir los notebooks de Jupyter incluidos en el proyecto.
4. Ejecutar las celdas en el orden establecido para reproducir los análisis exploratorios.
5. Revisar las visualizaciones, resultados y conclusiones obtenidas en cada notebook.

## Autora

**Karla Caroca Henríquez**

Responsable del análisis exploratorio, selección del problema y documentación del proyecto.

## Licencia

Este proyecto fue desarrollado exclusivamente con fines académicos y educativos.
