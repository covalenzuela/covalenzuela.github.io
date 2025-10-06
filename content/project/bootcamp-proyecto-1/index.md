---
title: "Bootcamp ML — Proyecto 1 (Módulo 9): Interpretabilidad con LIME/SHAP"
summary: "Evaluación Modular del Módulo 9: explicabilidad local y global de un clasificador (LIME/SHAP) + sesgo y ética."
date: 2025-10-06
type: project
categories: ["educativos"]
tags: ["Bootcamp ML","ML clásico","Interpretabilidad","SHAP","LIME","Clasificación"]
links:
  - icon: google-drive
    icon_pack: fab
    name: "Ver carpeta en Drive"
    url: "https://drive.google.com/drive/folders/1Hs3jl_w-43aEhxaFoJUiTqq3BVb2esAz?usp=sharing"
---

**Qué fue.** **Evaluación Modular (Módulo 9)** enfocada en **interpretabilidad de modelos**.  
**Tarea.** Entrenar un clasificador (p. ej., Regresión Logística / Random Forest / XGBoost) y explicarlo con **SHAP** (global + local) y **LIME** (local), comparando hallazgos.  
**Dataset.** *Heart Failure Prediction* (Kaggle) u otro tabular similar.  
**Métricas.** Accuracy/F1, *confusion matrix*, y análisis de **variables sensibles** con mirada ética.  
**Entregables.** Notebook + PDF con explicaciones y propuestas de mejora del modelo/datos.

**Stack.** Python, pandas, scikit-learn, **shap**, **lime**, matplotlib.

**Resultados clave (ejemplos a documentar).**
- Gráficos SHAP (summary/bar/waterfall) → patrones globales.
- Explicaciones LIME en ≥3 casos → contrastes locales vs. SHAP.
- Riesgo de sesgo y mitigaciones sugeridas (features sensibles, umbrales, etc.).
