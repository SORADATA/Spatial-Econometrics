# Spatial Econometrics

Collection de projets d'**économétrie spatiale** appliquée à différents contextes géographiques et problématiques économiques. Ce repository explore les interdépendances spatiales, les effets de débordement (spillovers) et les clusters géographiques en utilisant des techniques avancées de modélisation spatiale.

## 🎯 Objectifs

- Analyser les **autocorrélations spatiales** dans les phénomènes économiques et sociaux
- Quantifier les **effets directs et indirects** des politiques publiques
- Identifier les **clusters spatiaux** et valeurs aberrantes géographiques
- Développer des modèles économétriques spatiaux robustes (SAR, SEM, SDM, SARAR)

## 📁 Projets

### 1. [Maroc - Analyse Spatiale de la Pauvreté](./Maroc)

Analyse économétrique spatiale de la pauvreté au niveau provincial au Maroc.

**Données** : 61 provinces | **Variables** : Pauvreté, Analphabétisme, Activité économique

**Résultats clés** :
- I de Moran = 0.522*** (forte autocorrélation spatiale)
- Effets indirects représentent 30-32% de l'impact total des politiques
- Identification de clusters High-High (centre-est) et Low-Low (sud saharien)

**Modèles** : SAR, SEM | **Décomposition** : Effets directs/indirects (LeSage & Pace, 2009)

---

### 2. [Projet à venir]

*D'autres analyses spatiales seront ajoutées ici...*

## 🛠️ Méthodologie

### Analyse Exploratoire Spatiale (ESDA)
- **I de Moran global** : Test d'autocorrélation spatiale
- **LISA (Local Indicators of Spatial Association)** : Identification de clusters locaux
- **Moran Scatterplot** : Visualisation des patterns spatiaux

### Modélisation Économétrique Spatiale
- **SAR (Spatial AutoRegressive)** : Dépendance spatiale de la variable dépendante
- **SEM (Spatial Error Model)** : Autocorrélation spatiale des erreurs
- **SDM (Spatial Durbin Model)** : Effets spatiaux des variables explicatives
- **SARAR** : Combinaison SAR + SEM

### Décomposition des Effets
- **Effets directs** : Impact local
- **Effets indirects (spillovers)** : Débordements sur les voisins
- **Effets totaux** : Impact système global

## 🔧 Technologies

**Langages** : Python, R

**Bibliothèques Python** :
- `geopandas` : Manipulation de données géospatiales
- `pysal` / `esda` : Analyse exploratoire spatiale
- `spreg` : Estimation de modèles économétriques spatiaux
- `libpysal` : Matrices de poids spatial
- `matplotlib` / `seaborn` : Visualisation

**Bibliothèques R** :
- `spdep` : Économétrie spatiale
- `spatialreg` : Modèles de régression spatiale
- `sf` : Données spatiales simples
- `tmap` : Cartographie thématique

## 📚 Références Théoriques

- **Anselin, L. (1988)**. *Spatial Econometrics: Methods and Models*. Springer.
- **LeSage, J., & Pace, R. K. (2009)**. *Introduction to Spatial Econometrics*. CRC Press.
- **Elhorst, J. P. (2014)**. *Spatial Econometrics: From Cross-Sectional Data to Spatial Panels*. Springer.
- **Getis, A., & Ord, J. K. (1992)**. The Analysis of Spatial Association by Use of Distance Statistics. *Geographical Analysis*, 24(3), 189-206.

## 🎓 Contexte

Projets réalisés dans le cadre du **Master Expertise Statistique pour l'Économie et la Finance (ESEF)** - Université de Lorraine, en alternance avec le **Ministère de l'Économie et des Finances (Bercy)**.

## 📧 Contact

**Auteur** : Moussa (SORADATA)  
**Institution** : Université de Lorraine | Ministère de l'Économie et des Finances  
**GitHub** : [@SORADATA](https://github.com/SORADATA)

---

⭐ N'hésitez pas à explorer les différents projets et à donner votre feedback !
