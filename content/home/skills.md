---
# An instance of the Featurette widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featurette

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Skills
subtitle: "Bioinformática · ML/NLP · Simulación · MLOps · BI/UX"

# Showcase personal skills or business features.
# - Add/remove as many `feature` blocks below as you like.
# - For available icons, see: https://wowchemy.com/docs/page-builder/#icons
feature:
  # ——— Ciencia de datos / ML ———
  - name: Python (pandas, scikit-learn)
    icon: python
    icon_pack: fab
    description: 80%

  - name: R (tidyverse, Bioconductor)
    icon: r-project
    icon_pack: fab
    description: 70%

  - name: Bash / Shell scripting
    icon: terminal
    icon_pack: fas
    description: 85%

  - name: NLP aplicado (TF–IDF, spaCy, SBERT)
    icon: robot
    icon_pack: fas
    description: 70%

  - name: Estadística aplicada
    icon: chart-line
    icon_pack: fas
    description: 70%

  # ——— Bioinformática / Simulación ———
  - name: "Genómica aplicada (NGS: FastQC/MultiQC, BWA, GATK, VEP; RNA-seq/DESeq2)"
    icon: dna
    icon_pack: fas
    description: 75%

  - name: "Simulación molecular (MD: GROMACS; análisis RMSD/RMSF; VMD)"
    icon: microscope
    icon_pack: fas
    description: 70%

  - name: Modelado por homología + visualización (PyMOL/VMD)
    icon: cubes
    icon_pack: fas
    description: 65%

  - name: Docking molecular (AutoDock Vina)
    icon: flask
    icon_pack: fas
    description: 60%

  # ——— Ingeniería / MLOps ———
  - name: APIs con FastAPI (REST, Pydantic)
    icon: server
    icon_pack: fas
    description: 65%

  - name: Docker (contenedorización / compose)
    icon: docker
    icon_pack: fab
    description: 65%

  - name: Pipelines reproducibles (Nextflow)
    icon: project-diagram
    icon_pack: fas
    description: 65%

  - name: Git / GitHub (flujo + Actions)
    icon: github
    icon_pack: fab
    description: 75%

  - name: SQL & bases de datos (PostgreSQL/MySQL)
    icon: database
    icon_pack: fas
    description: 65%

  # ——— BI / UX ———
  - name: Power BI (DAX, Power Query)
    icon: chart-pie
    icon_pack: fas
    description: 70%

  - name: Excel avanzado (tablas dinámicas, fórmulas, macros básicas)
    icon: file-excel
    icon_pack: fas
    description: 80%

  - name: UX de datos (prototipos y flujos — Figma)
    icon: pen-nib
    icon_pack: fas
    description: 60%

# Uncomment to use emoji icons.
#- icon: ":smile:"
#  icon_pack: "emoji"
#  name: "Emojiness"
#  description: "100%"  

# Uncomment to use custom SVG icons.
# Place custom SVG icon in `assets/images/icon-pack/`, creating folders if necessary.
# Reference the SVG icon name (without `.svg` extension) in the `icon` field.
#- icon: "your-custom-icon-name"
#  icon_pack: "custom"
#  name: "Surfing"
#  description: "90%"
---
