# Équivalences entre R (`dplyr`) et Python (`pandas`) pour la manipulation de données

Ce dépôt contient tous les exemples de code issus de l’article comparatif entre **R** et **Python** pour la manipulation de données tabulaires. Il a pour but d’aider les utilisateurs à passer facilement de l’un à l’autre, à travers des cas concrets et expliqués pas à pas.

## Contenu

- 📘 `equivalences_r_python_pandas_explique.ipynb`  
  Notebook Jupyter illustrant les principales opérations avec `pandas`, enrichi de commentaires pédagogiques.
  
- 📗 `equivalences_r_dplyr_explique.Rmd`  
  Fichier RMarkdown avec les équivalents R utilisant `dplyr` et `lubridate`.
  

## Opérations couvertes

- Création et affichage de jeux de données
- Sélection et filtrage de colonnes/lignes
- Manipulations de dates et de chaînes de caractères
- Calcul d'âge précis
- Agrégation par groupe
- Jointures entre tables
- Transformation de données

## Prérequis

### Pour le notebook Python

- Python ≥ 3.7
- pandas

```bash
pip install pandas
```

### Pour le fichier RMarkdown

- R ≥ 4.0
- Packages : `dplyr`, `lubridate`

```r
install.packages("dplyr")
install.packages("lubridate")
```

## Objectif

L’objectif de ce dépôt est de servir de **ressource pédagogique** pour les analystes, data scientists et formateurs qui travaillent avec R ou Python, ou qui souhaitent s’initier à l’un des deux langages.

## Auteur

Ce projet a été initié dans le cadre d’un article publié par **[Stat4Decision](https://www.stat4decision.fr/blog/)**, et donc Emmanuel Jakobowicz est l'auteur.

---

N’hésitez pas à proposer des contributions (ajout d’exemples, corrections, portage vers `data.table` ou `polars`, etc.).
