#  Analyse du Risque Cardiaque — HeartAttack.ridk

##  Description du projet
Ce projet implémente une **analyse en composantes principales (ACP)** complète sur le dataset **HeartAttack.ridk** afin d’explorer les facteurs associés au risque de crise cardiaque.  
Le pipeline comprend le **prétraitement des données**, l’**ACP**, le **clustering (k-means)** et une **régression logistique** basée sur les composantes principales.
---

## 🧩 Contenu du dépôt
| Fichier | Description |
|----------|-------------|
| `HeartAttack_analysis.Rmd` | Notebook RMarkdown complet pour exécuter le pipeline d’analyse. |
| `HeartAttack.ridk.csv` | Jeu de données source (à ajouter par l’utilisateur). |
| `data_final.csv` | Données finales après ACP (générées automatiquement). |
| `pca_eigenvalues.csv` | Valeurs propres et variance expliquée. |

---

## ⚙️ Installation et dépendances
- **R ≥ 4.1**
- **RStudio** (recommandé)
- Packages R nécessaires :
  ```r
  install.packages(c("pacman", "FactoMineR", "factoextra", "tidyverse", "psych", "caret", "broom"))
