# Telecom X – Análisis y Predicción de Cancelación 

##  Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de clientes (churn) en Telecom X y desarrollar modelos de Machine Learning capaces de predecir qué clientes tienen mayor probabilidad de abandonar el servicio.

El análisis combina limpieza de datos, transformación de variables, modelado predictivo e interpretación estratégica de resultados.

## Objetivos

- Identificar los principales factores que influyen en la cancelación.
- Construir modelos predictivos para anticipar el churn.
- Comparar el rendimiento de distintos modelos.
- Proponer estrategias de retención basadas en los resultados obtenidos.

## Metodología

### Limpieza y Preparación de Datos
- Eliminación de variables irrelevantes (customerID).
- Conversión de variables numéricas.
- Manejo de valores nulos.
- Codificación de variables categóricas con `get_dummies`.
- Normalización de variables numéricas para modelos lineales.

### División del Dataset
- 70% entrenamiento
- 30% prueba
- Estratificación para mantener proporción de churn

### Modelos Implementados
- Regresión Logística
- Random Forest

## Resultados

### Regresión Logística
- Accuracy: 80%
- Recall (clientes que cancelan): 54%
- Mejor desempeño general para este problema.

### Random Forest
- Accuracy: 79%
- Recall (clientes que cancelan): 48%

La Regresión Logística mostró mejor capacidad para detectar clientes con riesgo de cancelación.

## Principales Factores que Aumentan el Churn

- Contrato mensual (Month-to-month)
- Servicio de fibra óptica
- Pago mediante electronic check
- Facturación electrónica
- Cargos totales elevados

## Factores que Reducen el Churn

- Mayor tiempo de permanencia (tenure)
- Contratos de uno o dos años
- Servicios de soporte técnico
- Servicios de seguridad en línea

El tiempo de permanencia fue el factor más determinante.

## Recomendaciones Estratégicas

- Implementar programas de fidelización en los primeros meses del cliente.
- Incentivar contratos a largo plazo.
- Ofrecer soporte técnico como valor agregado.
- Analizar experiencia del servicio de fibra óptica.
- Crear alertas tempranas para clientes de alto riesgo.

## Tecnologías Utilizadas

- Python
- Pandas
- Scikit-learn
- Google Colab

## Impacto del Proyecto

Este proyecto demuestra la capacidad de:

- Transformar datos en decisiones estratégicas.
- Aplicar modelos de Machine Learning a problemas reales de negocio.
- Interpretar resultados más allá de métricas técnicas.
