# Machine-Learning-appliqu-la-finance
# Analyse des Profils Moyens d'Investisseurs

## Description du projet
Ce projet analyse les profils moyens d'investisseurs à partir de données démographiques et financières.  
L'objectif est de segmenter les investisseurs en **clusters** et de comprendre leurs comportements en matière de risque, épargne et consommation.

---

## Données
Le dataset contient les colonnes suivantes :  

- `AGE` : Année de naissance / âge moyen  
- `EDUC` : Niveau d'éducation  
- `MARRIED` : Marié / Célibataire  
- `KIDS` : Nombre moyen d'enfants  
- `LIFECL` : Style de vie  
- `OCCAT` : Niveau professionnel / occupation  
- `RISK` : Tolérance au risque  
- `HHOUSES` : Nombre de maisons possédées  
- `WSAVED` : Épargne / patrimoine  
- `SPENDMOR` : Comportement de dépense  
- `NWCAT` : Catégorie de richesse nette  
- `INCCL` : Classe de revenu  

---

## Profil moyen de chaque cluster

| Cluster   | Profil général                         | Description analytique |
|-----------|----------------------------------------|-----------------------|
| Cluster 0 | ⚖️ Jeunes familles prudentes           | 🔹 Âge moyen faible (≈ 2) → jeunes adultes  <br> 🔹 Éducation moyenne (≈ 2.3) <br> 🔹 Mariés souvent (1.07 ≈ mariés) <br> 🔹 Enfants présents (≈ 2) <br> 🔹 Faible niveau professionnel (OCCAT ≈ 1.3) <br> 🔹 Forte tolérance au risque (RISK ≈ 3.4) <br> 🔹 Revenus et patrimoine moyens <br> 🟢 => Jeunes ménages actifs, modérément prudents mais prêts à prendre quelques risques pour faire croître leur épargne. |
| Cluster 1 | 💼 Investisseurs expérimentés et aisés | 🔹 Âge élevé (≈ 4.9) → adultes mûrs <br> 🔹 Niveau d’étude modéré (≈ 2.5) <br> 🔹 Mariés (≈ 1.5) <br> 🔹 Peu ou pas d’enfants <br> 🔹 Très haut niveau de vie (LIFECL ≈ 5.6) <br> 🔹 Bon poste (OCCAT ≈ 2.6) <br> 🔹 RISK ≈ 3.4 → bons preneurs de risque <br> 🟢 => Investisseurs mûrs, avec bons revenus, prêts à investir de manière stratégique et plus risquée. |
| Cluster 2 | 🏦 Classe moyenne stable et prudente    | 🔹 Âge moyen (≈ 3.1) <br> 🔹 Niveau d’étude élevé (≈ 3.6) <br> 🔹 Peu d’enfants <br> 🔹 Revenus élevés (INCCL ≈ 4.7) <br> 🔹 NWCAT ≈ 4.2 (bonne richesse) <br> 🔹 RISK ≈ 2.4 (peu enclins au risque) <br> 🟢 => Classe moyenne supérieure : bons revenus, mais préfèrent la sécurité et l’épargne aux placements risqués. |
| Cluster 3 | 🧒 Jeunes célibataires débutants        | 🔹 Très jeunes (AGE ≈ 2) <br> 🔹 Peu expérimentés (LIFECL ≈ 2.3) <br> 🔹 Célibataires (MARRIED ≈ 1.8) → plutôt non mariés <br> 🔹 Peu d’enfants (≈ 0.5) <br> 🔹 Revenus faibles (INCCL ≈ 2-3) <br> 🔹 Prise de risque modérée (RISK ≈ 3.2) <br> 🟢 => Jeunes actifs en début de carrière, avec un comportement financier variable, parfois influencé par la consommation (SPENDMOR). |

---

## Visualisations
- Radar charts pour chaque cluster (Python / Matplotlib)  
- Graphiques de répartition des variables (histogrammes, barplots)  

---

## Technologies utilisées
- Python  
- Pandas  
- Matplotlib / Seaborn  
- Jupyter Notebook / Google Colab  

---

## Auteur
**Sofien Meftahi** – Étudiant / Data Analyst en herbe  


