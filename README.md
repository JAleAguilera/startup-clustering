# Proyecto: Análisis de Startups y Predicción de Éxito

Este repositorio contiene el trabajo realizado en el marco del diplomado de Machine Learning.  
El proyecto busca analizar factores financieros y estructurales que influyen en el éxito de las startups, utilizando técnicas de análisis exploratorio, clustering y modelos predictivos.

---

## Estructura del repositorio

- **notebook_1_EDA.ipynb**  
  Análisis exploratorio de datos (EDA).  
  Incluye:
  - Revisión inicial del dataset de startups.
  - Limpieza y preprocesamiento de variables.
  - Construcción de ratios financieros y transformaciones logarítmicas.
  - Visualización y análisis de distribuciones.

- **notebook_2_Clustering.ipynb**  
  Aplicación de técnicas de clustering no supervisado.  
  Incluye:
  - K-Means, K-Modes, K-Prototypes, DBSCAN y clustering jerárquico.
  - Evaluación con métricas: Silhouette, Calinski-Harabasz y Davies-Bouldin.
  - Identificación de perfiles financieros de startups.

- **notebook_3_ModeloPredictivo.ipynb** 
  Desarrollo de modelos supervisados para predecir éxito (profitable / no profitable).  
  Se implementarán:
  - Regresión logística (L1 y L2).
  - Comparación de métricas y validación.

---

## Requisitos

El proyecto está desarrollado en Python 3.  
Principales librerías utilizadas:
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`
- `kmodes`
- `scipy`

Se recomienda usar un entorno virtual (ej: `venv` o `poetry`) para instalar las dependencias.

---

## Ejecución

1. Clonar el repositorio:  
   ```bash
   git clone <URL_DEL_REPO>
   cd <NOMBRE_DEL_REPO>
2. Instalar dependencias:
```bashbash
Copiar código
pip install -r requirements.txt
```
3. Abrir las notebooks en Jupyter o VSCode y ejecutar paso a paso.
---
## Resultados esperados
- Identificación de perfiles de startups según variables financieras y categóricas.
- Construcción de modelos predictivos para evaluar probabilidad de éxito.
- Reflexión sobre limitaciones y trabajo futuro.
