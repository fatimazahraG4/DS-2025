
# 🫀 Jeu de données : Heart Disease (UCI Machine Learning Repository)

**DOI :** [10.24432/C52P4X](https://doi.org/10.24432/C52P4X)  
**Date de dépôt :** 30 juin 1988  
**Sources :** Cleveland, Hungary, Switzerland, VA Long Beach  
**Nombre d’instances :** 303  
**Nombre d’attributs :** 14 (sur 76 au total)  
**Type de données :** Multivarié (catégorique, entier, réel)  
**Domaine :** Santé et médecine  
**Tâche associée :** Classification  
**Valeurs manquantes :** Oui  

---

## 🧩 Description du jeu de données

Ce jeu contient 76 attributs au total, mais les études publiées se concentrent sur un sous-ensemble de **14 attributs**.  
Le but est de prédire la **présence de maladie cardiaque**.  
La valeur cible (`num`) varie de 0 (absence) à 4 (présence).  
Les travaux de recherche se concentrent principalement sur la **base de Cleveland**.

---

## 🔢 Variables principales

| Nom du champ | Type | Description | Valeurs possibles / Unités |
|---------------|------|-------------|-----------------------------|
| **age** | Entier | Âge du patient | années |
| **sex** | Catégorique | Sexe du patient | 1 = homme ; 0 = femme |
| **cp** | Catégorique | Type de douleur thoracique | 1 = angine typique ; 2 = angine atypique ; 3 = douleur non angineuse ; 4 = asymptomatique |
| **trestbps** | Entier | Pression artérielle au repos (à l’admission) | mm Hg |
| **chol** | Entier | Taux de cholestérol sérique | mg/dl |
| **fbs** | Catégorique | Glycémie à jeun > 120 mg/dl | 1 = vrai ; 0 = faux |
| **restecg** | Catégorique | Résultats de l’électrocardiogramme au repos | 0 = normal ; 1 = anomalie ST-T ; 2 = hypertrophie ventriculaire gauche |
| **thalach** | Entier | Fréquence cardiaque maximale atteinte | — |
| **exang** | Catégorique | Angine induite par l’effort | 1 = oui ; 0 = non |
| **oldpeak** | Réel | Dépression du segment ST induite par l’effort | — |
| **slope** | Catégorique | Pente du segment ST au pic de l’effort | 1 = ascendante ; 2 = plate ; 3 = descendante |
| **ca** | Entier | Nombre de vaisseaux majeurs colorés par fluoroscopie | 0 à 3 |
| **thal** | Catégorique | Résultat du test Thallium | 3 = normal ; 6 = défaut fixe ; 7 = défaut réversible |
| **num** | Cible | Diagnostic de maladie cardiaque | 0 = absence ; 1–4 = présence |

---

## 🧠 Contexte scientifique

- Étude initiale : *International application of a new probability algorithm for the diagnosis of coronary artery disease*  
  **Auteurs :** R. Detrano, A. Jánosi, W. Steinbrunn, M. Pfisterer, J. Schmid, S. Sandhu, K. Guppy, S. Lee, V. Froelicher  
  **Publié dans :** *American Journal of Cardiology* (1989)

---

## 🧾 Fichiers disponibles

| Fichier | Taille |
|----------|--------|
| `cleveland.data` | 59.2 KB |
| `hungarian.data` | 60.7 KB |
| `switzerland.data` | 24.1 KB |
| `long-beach-va.data` | 39 KB |
| `new.data` | 380.6 KB |

---

## 📚 Référence de citation

Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989).  
*Heart Disease [Dataset]*. UCI Machine Learning Repository.  
[https://doi.org/10.24432/C52P4X](https://doi.org/10.24432/C52P4X)

**Licence :** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

