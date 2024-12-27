# PROYECTO_FINAL

# PREDICCIÓN DEL TIEMPO DE RESOLUCIÓN DE INCIDENCIAS EN UN PROYECTO DE DESARROLLO DE SOFTWARE ÁGIL USANDO APRENDIZAJE AUTOMÁTICO

Este proyecto utiliza modelos de aprendizaje automático como Gradient Boosting, Random Forest y XGBoost para predecir los tiempos de resolución de tickets en JIRA. A continuación se detalla la estructura de archivos, las dependencias y las instrucciones para ejecutar los notebooks.

## Estructura del CD

```
/CD
│
├── /DATA/
│   └── issues_history.csv                # Archivo de datos con los tickets de JIRA
│
├── /NOTEBOOK FILES/
│   ├── 1_cleaning_process.ipynb          # Notebook para la limpieza  de datos
│   ├── 2_eda_feature_engineering.ipynb   # Notebook para el analisis exploratorio y el feature engineering
│   ├── 3_pre_model_process.ipynb         # Notebook para normalizar los datos
│   ├── 4_training_evaluation.ipynb       # Notebook para entrenar los modelos y evaluar su desempenio
│   └── 5_implementation_plan.ipynb       # Notebook que presenta el disenio de la implementacion
│
├── /NOTEBOOKS/
│   └── PROYECTO FINAL.pdf                # Monografia
|
└── README                                # Este archivo
```

### Requisitos

Antes de ejecutar los notebooks, asegúrate de tener instaladas todas las dependencias necesarias.

- Anaconda: Para su instalacion ir a: https://www.anaconda.com/download
- Python: Para su instalacion ir a: https://www.python.org/downloads/

Una vez instalada las herramientas, en anaconda navigador abrir JupiterLab, buscar el directorio de este CD y ejecutar los correspondientes archivos .ipynb

### Alternativa

Si bien el proyecto no se trabajo en Google Colab, existe un repositorio para poder acceder o descargar todos los archivos previamente mencionados: https://drive.google.com/drive/folders/1U42YI3jpfrxdRGFsoD1t-XIFO-ykuUCG?usp=sharing
Puede descargarlo en su entorno drive, modificar las rutas de los archivos DATA a su conveniencia y ejecutarlos.

### Contacto

Si tienes alguna pregunta o necesitas asistencia, no dudes en contactar a:

_Nombre del autor_: Anahi Callejas
_Correo electrónico_: anahicosi@gmail.com
