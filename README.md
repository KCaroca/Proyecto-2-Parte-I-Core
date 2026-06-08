# Proyecto 2 – Análisis Inicial y Selección de Problema

## Descripción

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre distintos conjuntos de datos relacionados con salud y educación, con el fin de identificar sus características, calidad de datos, posibles desafíos y oportunidades de aplicación en ciencia de datos. A partir de este análisis se selecciona un conjunto de datos y una problemática específica para desarrollar en etapas posteriores mediante técnicas de aprendizaje automático.

## Conjuntos de Datos Analizados

### 1. Salud Mental en Jóvenes

Este conjunto de datos contiene información relacionada con variables demográficas, hábitos de vida, condiciones académicas y factores asociados a la salud mental de jóvenes, permitiendo estudiar posibles factores de riesgo y patrones asociados a trastornos psicológicos.

### 2. Rendimiento Académico de Estudiantes

El dataset reúne antecedentes académicos, familiares, sociales y personales de estudiantes, incluyendo calificaciones, ausencias, hábitos de estudio y una variable objetivo relacionada con el riesgo de depresión.

### 3. Riesgo Materno en Gestantes

Este conjunto de datos contiene información clínica y demográfica de mujeres embarazadas, permitiendo evaluar factores asociados al riesgo materno durante la gestación.

### 4. Fetal Health

El dataset contiene registros cardiotocográficos utilizados para evaluar el estado de salud fetal, permitiendo clasificar los casos en normales, sospechosos o patológicos.

## Resumen del EDA Inicial

### Salud Mental en Jóvenes

Se identificaron variables categóricas y numéricas relevantes para el análisis de salud mental. Se detectaron valores faltantes y distribuciones heterogéneas que requerirán preprocesamiento. Asimismo, se observaron posibles asociaciones entre factores personales, académicos y la variable objetivo.

### Rendimiento Académico de Estudiantes

Se identificaron valores nulos en algunas variables categóricas, ausencia de registros duplicados y presencia de variables académicas, familiares y sociales potencialmente relacionadas con el riesgo de depresión.

### Riesgo Materno en Gestantes

El conjunto presenta variables clínicas relevantes para la evaluación del riesgo durante el embarazo. Se observaron diferencias importantes entre grupos de riesgo que podrían ser aprovechadas mediante modelos predictivos.

### Fetal Health

El dataset presenta variables biomédicas derivadas del monitoreo fetal. Se identificaron algunas clases con menor representación, aspecto que deberá considerarse en etapas posteriores de modelado.

## Problema Seleccionado

### Descripción del problema

El problema seleccionado consiste en predecir el riesgo asociado a alteraciones en la salud mental de jóvenes utilizando variables demográficas, hábitos de vida, condiciones académicas y factores psicosociales. El objetivo es construir un modelo capaz de clasificar a los individuos según su nivel de riesgo, permitiendo identificar tempranamente factores asociados a problemas de salud mental.

### Justificación

Tras analizar los cuatro conjuntos de datos disponibles, se seleccionó el dataset **Salud Mental en Jóvenes** debido a la creciente relevancia de los problemas de salud mental en la población juvenil y a la diversidad de variables disponibles para su estudio.

Durante el análisis exploratorio se identificó una variable objetivo claramente definida, junto con múltiples variables explicativas relacionadas con hábitos de vida, condiciones académicas, factores demográficos y características psicosociales. Asimismo, el conjunto de datos presenta desafíos comunes en proyectos reales de ciencia de datos, incluyendo valores faltantes, variables categóricas y numéricas, así como posibles relaciones complejas entre los distintos factores asociados a la salud mental.

Estas características lo convierten en un caso adecuado para desarrollar un problema de clasificación supervisada mediante técnicas de aprendizaje automático.

## Objetivos Específicos

- Explorar las variables asociadas al estado de salud mental de los jóvenes.
- Identificar factores demográficos, académicos y de estilo de vida relacionados con la variable objetivo.
- Aplicar técnicas de limpieza y preprocesamiento de datos.
- Construir y comparar modelos de clasificación para predecir el riesgo asociado a problemas de salud mental.
- Evaluar el desempeño de los modelos utilizando métricas apropiadas de clasificación.

## Instrucciones para Ejecutar

- Clonar o descargar el repositorio.
- Instalar las librerías necesarias (`pandas`, `numpy`, `matplotlib` y `seaborn`).
- Abrir los notebooks de Jupyter incluidos en el proyecto.
- Ejecutar las celdas en orden para reproducir el análisis exploratorio.
- Revisar los resultados y conclusiones obtenidas.

## Autor

Karla Caroca

## Licencia

Proyecto desarrollado con fines académicos y educativos.
