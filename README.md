# Proyecto 2 – Análisis Inicial y Selección de Problema

## Descripción

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre distintos conjuntos de datos relacionados con problemáticas de salud y educación, con el fin de identificar sus características, evaluar la calidad de los datos y detectar oportunidades para la aplicación de técnicas de ciencia de datos y aprendizaje automático. A partir de este análisis, se selecciona un conjunto de datos y una problemática específica para desarrollar en etapas posteriores del proyecto.

## Conjuntos de Datos Analizados

### 1. Salud Mental en Jóvenes

Este conjunto de datos contiene información relacionada con variables demográficas, hábitos de vida, condiciones académicas y factores asociados a la salud mental de jóvenes. Permite estudiar posibles factores de riesgo y patrones relacionados con alteraciones en el bienestar psicológico.

### 2. Rendimiento Académico de Estudiantes

El dataset reúne antecedentes académicos, familiares y sociales de estudiantes, incluyendo hábitos de estudio, ausencias y desempeño académico, facilitando el análisis de variables relacionadas con el rendimiento y el bienestar estudiantil.

### 3. Riesgo Materno en Gestantes

Este conjunto de datos contiene información clínica y demográfica de mujeres embarazadas, permitiendo evaluar factores asociados al riesgo materno durante la gestación y apoyar la identificación temprana de casos de mayor complejidad.

### 4. Fetal Health

El dataset contiene registros cardiotocográficos utilizados para evaluar el estado de salud fetal. Su objetivo es clasificar los casos en categorías normales, sospechosas o patológicas a partir de variables biomédicas.

## Resumen del EDA Inicial

### Salud Mental en Jóvenes

Se identificaron variables numéricas y categóricas relevantes para el análisis. Se detectó la presencia de valores faltantes y posibles relaciones entre factores personales y la variable objetivo, lo que sugiere la necesidad de aplicar técnicas de preprocesamiento y modelado.

### Rendimiento Académico de Estudiantes

Se observaron variables académicas y familiares potencialmente asociadas con el desempeño estudiantil. No se detectaron duplicados relevantes y se identificaron algunos valores faltantes que requerirán tratamiento.

### Riesgo Materno en Gestantes

El conjunto presenta variables clínicas relevantes para la evaluación del riesgo durante el embarazo. Se identificaron diferencias entre grupos que podrían ser aprovechadas mediante modelos predictivos.

### Fetal Health

El dataset incluye variables biomédicas derivadas del monitoreo fetal. Se observaron algunas categorías con menor representación, aspecto importante a considerar en futuras etapas de modelado.

## Problema Seleccionado

### Descripción del problema

El problema seleccionado consiste en predecir el riesgo asociado a alteraciones en la salud mental de jóvenes utilizando información demográfica, hábitos de vida y factores académicos. El objetivo es desarrollar un modelo de clasificación capaz de identificar tempranamente a individuos con mayor probabilidad de presentar problemas relacionados con su salud mental.

### Justificación

Se seleccionó este conjunto de datos debido a la relevancia actual de la salud mental en la población juvenil y a la diversidad de variables disponibles para el análisis. Además, el dataset presenta desafíos propios de proyectos reales de ciencia de datos, como la existencia de valores faltantes, variables categóricas y numéricas, y posibles relaciones complejas entre distintos factores explicativos.

### Objetivos Específicos

* Explorar las variables asociadas al estado de salud mental de los jóvenes.
* Identificar factores demográficos, académicos y de estilo de vida relacionados con la variable objetivo.
* Aplicar técnicas de limpieza y preprocesamiento de datos.
* Construir y comparar modelos de clasificación para predecir el riesgo asociado a problemas de salud mental.
* Evaluar el desempeño de los modelos utilizando métricas apropiadas de clasificación.

## Instrucciones para Ejecutar

1. Clonar o descargar el repositorio.
2. Instalar las librerías necesarias: `pandas`, `numpy`, `matplotlib` y `seaborn`.
3. Abrir los notebooks de Jupyter incluidos en el proyecto.
4. Ejecutar las celdas en orden para reproducir el análisis exploratorio.
5. Revisar las visualizaciones, resultados y conclusiones obtenidas.

## Autores

* Karla Caroca – Desarrollo del análisis exploratorio, selección del problema y documentación del proyecto.

## Licencia

Este proyecto fue desarrollado con fines académicos y educativos.

