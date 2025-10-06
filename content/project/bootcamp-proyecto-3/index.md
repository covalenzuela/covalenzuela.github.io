---
title: "Bootcamp ML — Proyecto 3 (Módulo 8 · Sesión 3): Sentiment con Transformers"
summary: "Actividad de clase: pipeline de Hugging Face para sentimiento en reseñas clínicas con BERT multilingüe."
date: 2025-10-06
type: project
categories: ["educativos"]
tags: ["Bootcamp ML","NLP","Transformers","BERT","Sentiment"]
links:
  - icon: google-drive
    icon_pack: fab
    name: "Ver carpeta en Drive"
    url: "https://drive.google.com/drive/folders/1fIaNHJlBGXaUnhkFL9o6bo2c4X7xOkvJ?usp=sharing"
---

**Qué fue.** **Actividad de la Sesión 3 (Módulo 8)**: usar **Transformers** para **análisis de sentimiento** en reseñas clínicas (modo inferencia).  
**Modelo.** `nlptown/bert-base-multilingual-uncased-sentiment` (Hugging Face).  
**Pasos.** Crear dataset simulado (≥10 reseñas), ejecutar **pipeline** de `sentiment-analysis`, mostrar **texto + predicción + score** y reflexionar sobre resultados.  
**Análisis.** Ventajas frente a TF-IDF, **limitaciones** del modelo y adaptabilidad del enfoque moderno.

**Stack.** Python 3, **transformers**, **torch**, pandas (Colab u otro IDE).
