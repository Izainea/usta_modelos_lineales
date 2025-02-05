# 📘 Modelos Lineales: De los Datos a las Decisiones

## 🎯 Objetivo

Este curso proporciona una comprensión profunda de los **Modelos Lineales**, desde sus fundamentos teóricos hasta aplicaciones prácticas, utilizando **Python** como herramienta principal. El enfoque es transformar datos en conocimiento para tomar decisiones estratégicas.

## 📚 Contenido del Curso

### 1. El Poder de los Datos
- Importancia de los datos en la era actual
- Aplicaciones en diversos campos
- Papel de los modelos lineales en la interpretación de datos
- Herramientas y conceptos fundamentales

### 2. Regresión Lineal Simple
- Conceptos fundamentales
  - Variable dependiente e independiente
  - Estimación de parámetros (β₀, β₁)
  - Interpretación geométrica
- Implementación en Python
```python
import numpy as np
import statsmodels.api as sm
import matplotlib.pyplot as plt

# Ejemplo básico
X = sm.add_constant(X)  # Añadir intercepto
model = sm.OLS(y, X)
results = model.fit()
```
- Visualización de relaciones
- Interpretación de resultados

### 3. Regresión Múltiple
- Extensión a múltiples variables
- Selección de variables predictoras
- Interpretación de coeficientes
- Casos prácticos
- Diagnóstico del modelo

### 4. Validación y Diagnóstico
- Análisis de residuales
- Detección de outliers
- Pruebas de supuestos
  - Normalidad
  - Homocedasticidad
  - Independencia
- Técnicas de validación cruzada

### 5. Inferencia Bayesiana
- Fundamentos de estadística bayesiana
- Incorporación de información previa
- Actualización de modelos
- Ventajas en situaciones de incertidumbre
- Implementación con PyMC3

### 6. Análisis de Varianza (ANOVA)
- Descomposición de la variabilidad
- ANOVA de una vía
- ANOVA factorial
- Interpretación y diagnóstico
- Aplicaciones prácticas

## 🛠️ Herramientas y Tecnologías

### Bibliotecas Principales
```python
import numpy as np              # Computación numérica
import pandas as pd            # Manipulación de datos
import matplotlib.pyplot as plt # Visualización
import seaborn as sns          # Visualización estadística
import statsmodels.api as sm   # Modelado estadístico
import scipy.stats as stats    # Pruebas estadísticas
```

## 👥 Público Objetivo

Este curso está diseñado para:
- Estudiantes de estadística y ciencia de datos
- Profesionales que requieren análisis cuantitativos
- Investigadores que necesitan herramientas de modelado
- Analistas de datos buscando profundizar en modelos lineales

## 📊 Metodología

- Aprendizaje basado en problemas
- Ejemplos prácticos con datos reales
- Implementaciones en Python
- Ejercicios guiados y proyectos

## ✅ Requisitos Previos

Se recomienda tener conocimientos básicos de:
- Estadística descriptiva
- Probabilidad básica
- Python fundamental
- Álgebra lineal básica

## 📞 Contacto

Para consultas y más información:
- **Profesor**: Carlos Isaac Zainea
- **Email**: carloszainea@usta.edu.co

---

```{note}
Este curso combina teoría estadística con implementaciones prácticas, permitiendo una comprensión profunda de los modelos lineales y su aplicación en problemas reales.
```
