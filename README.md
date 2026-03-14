# 📊 Dashboard Analyse des Ventes Pharmaceutiques (2014-2019)

## Description

Dashboard interactif réalisé avec **Power BI** analysant les ventes de médicaments d'une pharmacie sur une période de 6 ans (2014-2019).  
Ce projet couvre l'ensemble de la chaîne analytique : import des données, transformation, modélisation et visualisation.

## 🗂️ Source des données

- **Dataset** : [Pharma Sales Data — Kaggle](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data)
- **Auteur** : Milan Zdravković
- **Licence** : CC BY-NC 4.0
- **Contenu** : 600 000 transactions retraitées, rééchantillonnées en données mensuelles

## 💊 Médicaments analysés (classification ATC)

| Code | Catégorie |
|---|---|
| M01AB | Anti-inflammatoires — Dérivés acétiques |
| M01AE | Anti-inflammatoires — Dérivés propioniques |
| N02BA | Analgésiques — Dérivés salicyliques |
| N02BE | Analgésiques / Antipyrétiques (Paracétamol) |
| N05B | Psycholeptiques — Anxiolytiques |
| N05C | Psycholeptiques — Somnifères et sédatifs |
| R03 | Médicaments respiratoires (Asthme) |
| R06 | Antihistaminiques systemiques (Allergies) |

## 📈 Visuels du dashboard

- **KPI Total Unités vendues** sur l'ensemble de la période
- **Histogramme** des ventes par médicament
- **Courbe temporelle** de l'évolution mensuelle par médicament
- **Camembert** de répartition des ventes par médicament
- **Slicer** interactif pour filtrer par médicament

## 🔍 Insights clés

- **N02BE (Paracétamol)** représente près de 50% des ventes totales
- Fort pic de ventes en **novembre-décembre** — saisonnalité hivernale marquée
- **N05C (Somnifères)** est le médicament le moins vendu de la pharmacie
- Creux estival visible sur la majorité des catégories (juillet-août)

## 🛠️ Technologies utilisées

- **Power BI Desktop** — Visualisation et modélisation
- **Power Query** — Transformation des données (Unpivot, typage, nettoyage)
- **DAX** — Mesures calculées (SUM, CALCULATE, FILTER)

## 📁 Contenu du repository

```
📦 powerbi-pharma-dashboard
 ┣ 📊 dashboard-pharma-sales.pbix   # Fichier Power BI complet
 ┣ 📄 salesmonthly.csv              # Dataset source
 ┗ 📖 README.md                     # Documentation
```

## 👤 Auteur

**Elyes** — Étudiant en Master Intelligence Artificielle en Santé  
Centrale Lille / Université de Lille (ILIS)
