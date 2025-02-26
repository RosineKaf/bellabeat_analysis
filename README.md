# 📊 Bellabeat Analysis - Data Science Project  

## 📝 Description  
Ce projet analyse l'utilisation des appareils connectés Bellabeat pour comprendre les tendances d'activité physique, de sommeil et de fréquence cardiaque.  

## 📂 Contenu du Projet  
- 📁 **data/** → Données brutes et nettoyées  
- 📁 **notebooks/** → Scripts R pour l'analyse  
- 📁 **visualizations/** → Graphiques et insights  
- 📜 **README.md** → Présentation du projet  

## 📊 Méthodologie  
✅ Nettoyage et préparation des données avec **R** (`tidyverse`, `dplyr`)  
✅ Analyse exploratoire des tendances d'activité et de sommeil  
✅ Visualisation avec **ggplot2**  
✅ Recommandations stratégiques pour Bellabeat  

## 📈 Visualisations  
![Distribution des pas quotidiens]((https://github.com/RosineKaf/bellabeat_analysis/blob/main/VISUALISATION/Distribution_pas_quotidien.png?raw=true))  
![Graphique Sommeil](visualizations/sleep_analysis.png)  

## 🚀 Comment exécuter le projet ?  
```r
# Charger les librairies
library(tidyverse)

# Importer les données
activity_data <- read_csv("data/dailyActivity.csv")

# Aperçu des données
glimpse(activity_data)
