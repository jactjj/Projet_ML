# Projet ML — Advanced Anomaly Detection

**Cours :** Machine Learning III (Unsupervised Learning) @Albert School
**Session 5 :** Practical Assessment — détection d'anomalies sur le dataset AI4I 2020 Predictive Maintenance.

## Objectif

Construire un pipeline non-supervisé pour détecter les pannes machines **avant** qu'elles n'arrivent, en minimisant l'alert fatigue (faux positifs) pour l'équipe maintenance.

- **Coût d'une heure de downtime :** 100 000 €
- **Coût d'un faux positif (FP) :** 500 €
- **Coût d'un faux négatif (FN) :** 15 000 €

## Dataset

[AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/ml/datasets/AI4I+2020+Predictive+Maintenance+Dataset) — 10 000 observations, capteurs (températures, torque, tool wear, etc.).

La colonne `Machine failure` est droppée pendant l'entraînement et n'est utilisée qu'à la fin pour évaluer les modèles.

## Modèles comparés

1. Isolation Forest
2. One-Class SVM
3. Local Outlier Factor (LOF)
4. Robust Covariance (Elliptic Envelope)

## Structure

- `Session5_Anomaly_Detection_Notebook.ipynb` — notebook principal
- `1773592112_Session5_Advanced_Anomaly_Detection_Assessment.pdf` — consigne du projet

## Plan

- **Partie 1 :** EDA & Cleaning
- **Partie 2 :** Modélisation & Tuning
- **Partie 3 :** Comparaison technique & visualisations
- **Partie 4 :** Conclusion managériale & stratégie business
