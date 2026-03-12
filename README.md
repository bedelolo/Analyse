# 📊 Étude de Marché : Emballages Alimentaires Jetables (Bénin)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blueviolet)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/license-MIT-green)

## 📋 Contexte du projet
Ce projet s'inscrit dans le cadre d'une étude de marché de terrain menée auprès de **123 professionnels de la restauration et vendeurs de rue** au Bénin (répartis sur les zones de Cotonou et Abomey-Calavi).

L’objectif principal de cette analyse est d'accompagner une entreprise ("Cinnuex") qui souhaite lancer sa nouvelle marque d'emballages jetables, en s'appuyant sur des **données probantes** (Business Intelligence) recueillies sur le terrain.

## 🎯 Objectifs de l'Analyse (EDA)
Ce repo contient le traitement scientifique complet des données brutes, répondant aux questions stratégiques suivantes :
1. **Profilage des consommateurs :** Qui sont ces vendeurs ? Quels sont leurs objectifs (économie contre écologie) ?
2. **Exigences techniques :** Quels matériaux (carton, bioplastiques, aluminium), formats (compartimentés) et contenances (ML) sont attendus ?
3. **Analyse Financière & Pricing :** Quel est le budget métier moyen alloué aux emballages ? Quelle est l'acceptation d'une hausse tarifaire contre une augmentation de la qualité (hermétisme) ?
4. **Analyse Croisée :** Comprendre la différence de pouvoir d'achat et d'exigences entre la zone de Cotonou (COT) et celle d'Abomey-Calavi (CAL).

---

## 🏗️ Structure du Projet (Repository)

```bash
📦 Analyse-Emballages-Jetables
 ┣ 📂 graphiques/                                 # Dossier des exports (20+ graphiques Matplotlib/Seaborn)
 ┃ ┣ 📜 00_dashboard.png                          # Vue d'ensemble (Dashboard)
 ┃ ┣ 📜 08_budget_mensuel.png                     # Histogramme du budget
 ┃ ┗ 📜 ... 
 ┣ 📜 enquête.xlsx                                # Dataset Brut de l'enquête (Excel source)
 ┣ 📜 Analyse_Spatiale_Et_Comportementale_Emballages.ipynb # Le Notebook final !
 ┣ 📜 Rapport_Final_Cinnuex.md                    # Le Rapport d'analyse et recommandations business (Markdown)
 ┗ 📜 README.md                                   # Documentation du dépôt
```

---

## 🛠️ Stack Technologique
Ce script utilise majoritairement la stack Data Science & Visualisation de base en Python :
* **Pandas & NumPy** : Import, parsing, nettoyage de chaînes de caractères complexes, nettoyage d'expressions monétaires et Feature Engineering.
* **Matplotlib & Seaborn** : Visualisation de l'élasticité prix, des graphiques en barres superposés croisés et intégration des palettes hexadécimales personnalisées.
* **Collections (Counter)** : Traitement sémantique de réponses à choix multiples et extraction de mots clés sur des champs `Text Open`.
* **Jupyter Notebook** : Format asynchrone pour la présentation didactique pas à pas.

---

## 🚀 Comment lancer le projet en local ?

### 1. Prérequis
Assurez-vous d'avoir Python 3.8+ installé, ainsi que `pip`.
Installez les bibliothèques d'analyse de données requises via le terminal :
```bash
pip install pandas numpy matplotlib seaborn jupyterlab openpyxl
```

### 2. Démarrage
1. Clonez ce dépôt.
```bash
git clone https://github.com/votre_profil/Analyse-Emballages-Jetables.git
cd Analyse-Emballages-Jetables
```
2. Lancez le notebook Jupyter :
```bash
jupyter notebook Analyse_Spatiale_Et_Comportementale_Emballages.ipynb
```
3. Exécutez l'ensemble des cellules ("Run All") pour voir la création du rapport analytique.

---

## 📈 Extraits des Recommandations Stratégiques (Insights)
* **Design "Star MVP" :** Le marché requiert un produit de Format Grand (1100 ML), doté impérativement de 2 compartiments.
* **Matériel ciblé :** Très forte appétence pour le Canton Durci et le Bioplastique, devant détrôner le plastique jetable polluant.
* **Focus "Friction métier" :** L'argument marketing décisif (Key Selling Point) devra être une barrière hermétique **100% anti-fuite de sauce et résistante aux extrêmes chaleurs.**

---

*Mission Data Analyse réalisée par Antigravity.*
