# Análisis de Rendimiento de Medicamentos

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar y modelar el **rendimiento de medicamentos** a partir de evaluaciones reportadas por usuarios/pacientes. El enfoque principal es evaluar la efectividad, facilidad de uso y nivel de satisfacción de distintos fármacos según la condición médica tratada.

El proyecto se centra en análisis de datos y modelos predictivos con fines académicos y analíticos, sin reemplazar recomendaciones médicas profesionales.

## Objetivos

* Analizar evaluaciones de medicamentos según distintas condiciones médicas.
* Identificar patrones de efectividad y satisfacción.
* Construir modelos predictivos para estimar el rendimiento de un medicamento.
* Comparar medicamentos dentro de una misma condición clínica.

## Conjunto de Datos

El dataset contiene información estructurada sobre medicamentos y sus evaluaciones. Las variables incluidas son:

* **Condition**: Condición médica tratada
* **Drug**: Nombre del medicamento
* **Indication**: Indicación terapéutica
* **Type**: Tipo de medicamento
* **Reviews**: Número de reseñas
* **Effective**: Nivel de efectividad percibida
* **EaseOfUse**: Facilidad de uso
* **Satisfaction**: Nivel de satisfacción del usuario

Las variables de salida pueden ser:

* **Satisfaction** (regresión)
* **Effective** (clasificación o regresión)

## Metodología

1. **Preprocesamiento de Datos**

   * Limpieza y normalización de variables
   * Manejo de valores faltantes
   * Codificación de variables categóricas

2. **Análisis Exploratorio de Datos (EDA)**

   * Distribución de calificaciones
   * Comparación de medicamentos por condición
   * Relación entre efectividad y satisfacción

3. **Modelado Predictivo**

   * División del dataset en entrenamiento y prueba
   * Modelos utilizados:

     * Regresión Lineal / Ridge / Lasso
     * Random Forest
     * Gradient Boosting

4. **Evaluación del Modelo**

   * R2: 80%
   * Error Cuadratico Medio (MSE): 22%

## Tecnologías Utilizadas

* Python 
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
