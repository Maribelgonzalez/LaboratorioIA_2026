# LaboratorioIA_2026
Laboratorio de Inteligencia_Artificial
# Clasificador de Comentarios con Redes Neuronales (NLP)

## Descripción del Proyecto

El presente proyecto consiste en el desarrollo de una aplicación web que implementa una red neuronal para clasificar comentarios de usuarios sobre productos tecnológicos en dos categorías: positivo y negativo.

La solución utiliza la librería Gentle-ai e integra conceptos fundamentales de procesamiento de lenguaje natural (NLP) para analizar texto y generar predicciones con un nivel de confianza asociado.

---

## Objetivo

Desarrollar un modelo de red neuronal capaz de analizar comentarios escritos por usuarios y determinar su polaridad (positiva o negativa), mostrando además el porcentaje de confianza de la predicción.

---

## Tecnologías Utilizadas

* HTML5 para la estructura de la aplicación
* CSS3 (Flexbox y Grid) para el diseño de la interfaz
* Tailwind CSS (vía CDN) para la estilización
* JavaScript para la lógica de la aplicación
* Gentle-ai (basado en TensorFlow.js) para la implementación del modelo
* JSON para la gestión del dataset
* OpenCode como entorno de desarrollo

---

## Dataset de Entrenamiento

Ejemplo de datos utilizados:

```json id="d8k3sl"
[
  { "texto": "El servidor Proxmox es muy estable", "etiqueta": "positivo" },
  { "texto": "El despliegue en Docker falló por memoria", "etiqueta": "negativo" }
]
```

Los datos son preprocesados mediante técnicas de tokenización utilizando las funciones proporcionadas por Gentle-ai.

---

## Arquitectura del Modelo

El modelo implementado sigue una arquitectura secuencial compuesta por:

* Capa de entrada (Embedding)
* Capa oculta (Densa)
* Capa de salida (Sigmoid o Softmax)

---

## Entrenamiento del Modelo

Durante el entrenamiento se ajustaron los siguientes hiperparámetros:

* Learning rate
* Número de epochs

Asimismo, se monitorean métricas como la función de pérdida (loss) y la precisión (accuracy) para evaluar el desempeño del modelo.

---

## Funcionalidades

* Campo de texto para ingresar comentarios
* Botón para ejecutar el análisis del texto
* Visualización del resultado con porcentaje de confianza (por ejemplo: 98% positivo)

---

## Limitaciones

El modelo presenta limitaciones en escenarios como:

* Interpretación de lenguaje sarcástico
* Ambigüedad en las expresiones
* Insuficiencia de datos de entrenamiento

Estas situaciones están relacionadas con la incertidumbre en los modelos de inteligencia artificial, la cual se refleja en valores de confianza cercanos al 50%.

---

## Reto Académico

Se realizaron pruebas modificando los hiperparámetros del modelo (learning rate y número de epochs) con el fin de analizar su impacto en la precisión durante el entrenamiento.

---

## Competencias Desarrolladas

* Implementación de redes neuronales
* Análisis y ajuste de datos de entrada
* Evaluación del desempeño de modelos de inteligencia artificial
* Identificación de incertidumbre en predicciones

---

## Instrucciones de Ejecución

1. Clonar el repositorio:

```bash id="k3s92l"
git clone https://github.com/tu-usuario/tu-repositorio.git
```

2. Abrir el proyecto en el navegador o en OpenCode

3. Ejecutar la aplicación

---

## Conclusiones

Este laboratorio permite comprender el funcionamiento de una red neuronal aplicada al análisis de texto, así como la importancia del preprocesamiento de datos y la selección de hiperparámetros en el rendimiento del modelo.

---

## Información Académica

* Curso: Inteligencia Artificial
* Tema: Redes Neuronales y Procesamiento de Lenguaje Natural
* Catedrático: Ing. M. Sc. Richard David Ortiz Sasvin
* Duración estimada: 1 hora 45 minutos

---

## Estado del Proyecto

En desarrollo / Finalizado (ajustar según corresponda)

---
