# Predicción de Captura de Merluza Negra en Tierra del Fuego

Este proyecto tiene como objetivo predecir la cantidad mensual de captura de **Merluza Negra** en la provincia de **Tierra del Fuego**, utilizando como variable predictora la **anomalía de temperatura superficial del mar (SST)**.

## 🧭 Estructura del Proyecto (Cookiecutter)

```
├── data/              # Datos (no incluidos en el repo)
│   ├── raw/          # Datos originales reales (Merluza y SST 2019)
│   ├── interim/      # Datos intermedios
│   └── processed/    # Datos listos para modelar
├── notebooks/        # Jupyter Notebooks
├── src/              # Código fuente del proyecto
├── reports/          # Visualizaciones, gráficos y salidas
├── docs/             # Documentación (PDFs, Word, etc.)
└── README.md         # Este archivo
```

## 🔍 Descripción del problema

Se busca modelar y predecir la variable `captura` mensual utilizando valores de `anom` (anomalía de temperatura superficial del mar).
El modelo utilizado es una regresión supervisada (lineal simple) y se entrenó sobre datos reales de 2019.

## 📊 Técnicas aplicadas

- Preprocesamiento de datos (filtrado, fechas, merge, normalización)
- Visualización de dispersión y densidad (KDE e histograma)
- Entrenamiento de modelo de regresión lineal
- Evaluación del modelo (MAE y R²)

## ⚠️ Importante

Este repositorio **no incluye datos sensibles o pesados** por decisión consciente.
Las carpetas `data/` están estructuradas y listas para recibir los archivos `.csv` reales que deben mantenerse localmente.

## 👨‍💻 Autor

- Cristian Couto
- Proyecto académico para la materia Aprendizaje Automático