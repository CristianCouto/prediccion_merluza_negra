# 📊 Figures

Este directorio contiene las visualizaciones generadas a partir del análisis del proyecto de predicción de captura de merluza negra en Tierra del Fuego.

---

## 🖼️ Imágenes incluidas

| Archivo                          | Descripción                                                        |
|----------------------------------|---------------------------------------------------------------------|
| `captura_vs_anomalia.png`        | Dispersión entre la captura mensual y la anomalía de temperatura. |
| `mae_por_modelo.png`             | Comparación del MAE entre modelos (SVM, Random Forest, etc.).     |

---

## 📂 Instrucciones

- Todas las imágenes deben tener un nombre claro y estar en formato `.png` o `.jpg`.
- Usar nombres con guiones bajos (`_`) y en minúsculas.
- Las imágenes pueden ser referenciadas directamente en el informe (`report/final_report.md` o `.pdf`).

---

## 🧠 Recomendación

Usá este script para guardar tus visualizaciones directamente aquí desde el notebook:

```python
import matplotlib.pyplot as plt

plt.savefig("report/figures/captura_vs_anomalia.png", dpi=300)
```

---

## ✍️ Autor

Cristian Couto – Proyecto: Predicción de Captura de Merluza Negra (2025)
