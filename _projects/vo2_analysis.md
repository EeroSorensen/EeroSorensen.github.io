---
layout: page
title: VO₂ Analysis
description: "Interactive Metabolic Cart Data Analysis using Python"
img: assets/img/vo2_preview.png
category: work
--- 

## Overview ##

This project analyzes exercise physiology data collected during a graded test. The dataset was sourced from [demo-knes381 Kaggle dataset](https://www.kaggle.com/datasets/drjohnholash/demo-knes381) by Dr. John Holash at the University of Calgary.

The analysis was developed in Python (matplotlib) and is embedded directly from Kaggle. The figure is generated programmatically from the CSV data. Changing the input dataset will automatically update all four panels

---

## How it Works ##

The code follows a step-by-step workflow: 

1. **Loaded data** from the raw CSV file into pandas DataFrame using 'pd.read_csv()', skipping the metadata rows at the top
2. **Renamed columns** from duplicate column headers are cleaned up using 'df.rename()'
3. **Assigned variables** (VO₂, VE, VCO₂, FECO₂) are extracted from the DataFrame
4. **Finding VO₂max** by identifying the maximum value of VO₂ and its time point by using 'max()' and 'argmax()'
5. **Generated the figure** by creating a 4-panel subplot using 'matplotlib.pyplot', with all panels sharing an x-axis (time)
6. **Annotating** the VO₂max value directly on the plot with a red arrow
7. **save** the figure at 300 dpi using 'fig.savefig()'

Each panel uses the same dataset to plot a physiological variable against time. Changing the input CSV will update all four panels automatically.

---

## Variables Analyzed ##

Variable | Description | Unit
------------- | ------------- | -------------
**V̇O₂** | Oxygen uptake | L/min
**VE** | Minute ventilation | breaths/min
**V̇CO₂** | Carbon dioxide output | L/min
**FECO₂** | Fractional expired CO₂ | %

---

## Notebook 

<iframe src="https://www.kaggle.com/embed/eerosorensen/knes381-pythonproject-eeros"
height="900" width="100%" frameborder="0" scrolling="auto" 
title="KNES381 Python Project"></iframe>

---

## Links

- [Original Kaggle Notebook](https://www.kaggle.com/code/eerosorensen/knes381-pythonproject-eeros)
- [GitHub Repository](https://github.com/EeroSorensen/KNES_381_PythonProject)
