## **Empresa Destinataria y Sector**

El análisis se enfoca en el sector de marketing de un banco portugués.

### **Objetivos:**

1. **Evaluar los Datos:** Realizar un análisis exploratorio y descriptivo para comprender ciertas características y patrones en el conjunto de datos y algunas caracteristicas del perfil del cliente.
2. **Modelado Predictivo:** Evaluar una serie de modelos de clasificación para predecir la columna 21, que indica si un cliente se suscribe al servicio correspondiente. Seleccionar el modelo que proporcione los mejores resultados en términos de precisión y eficacia.

## Estructura de directorios y archivos

    Analisis_sistema_educativo_Argentina/
    │
    ├── data/                          # Datasets
    │   ├── bronze/                    # Datos brutos
    │   ├── silver/                    # Datos limpios y transformados para ML y EDA
    │   └── gold/                      # Datos listos para visualización de datos
    │
    ├── models/                        # Mejor modelo para predecir la variable target
    │
    └── notebook                       # Este cuaderno con todas las etapas

## Tecnologías Utilizadas
- Python
  - Bibliotecas para análisis de datos:
    - NumPy
    - pandas
    - missingno
  -	Bibliotecas para visualización de datos:
    -	Seaborn
    - Plotly
  -	Bibliotecas para aprendizaje automático:
    -	scikit-learn
    - joblib
  - Bibliotecas para gestion de directorios y archivos
    - os
    - zipfile
  - Bibliotecas para web-scraping
    - lxml
    - requests

## Estado del proyecto:
- Finalizado 