# Analyse du stock et des ventes — BottleNeck

**Projet 6 — Parcours Business Intelligence Analyst | OpenClassrooms**

## Présentation

Ce projet pédagogique porte sur l'analyse des données de BottleNeck, un marchand de vin fictif. Il consiste à rapprocher les données de l'ERP et du site e-commerce à l'aide d'une table de liaison, puis à analyser les ventes, les stocks et les marges.

## Objectifs métier

- Consolider les données ERP et web.
- Identifier les incohérences, les doublons et les valeurs manquantes.
- Calculer le chiffre d'affaires par produit et le chiffre d'affaires total.
- Étudier les meilleures références et la concentration du chiffre d'affaires.
- Repérer les prix atypiques et analyser les stocks et les marges.
- Présenter des recommandations pour fiabiliser les données et améliorer l'ERP.

## Technologies

Python, pandas, NumPy, Matplotlib, Seaborn, Plotly, Jupyter Notebook et Excel.

## Livrables

| Fichier | Contenu |
|---|---|
| [Notebook Python](Humbert_Paco_Bottleneck_1_notebook_042026.ipynb) | Exploration, nettoyage, jointures, calculs et visualisations |
| [Présentation PowerPoint](Humbert_Paco_Bottleneck_2_presentation_042026.pptx) | Restitution des analyses et recommandations pour le CODIR |
| [ERP](erp.xlsx) | Références produits, prix, coûts d'achat et stocks |
| [Table de liaison](liaison.xlsx) | Correspondance entre les identifiants ERP et web |
| [Données web](web.xlsx) | Données du catalogue e-commerce et ventes |
| [Dataset final](dataset_final_bottleneck.xlsx) | Export consolidé fourni avec le projet |

## Démarche

1. Importation et exploration des trois sources.
2. Contrôles de qualité et traitement des incohérences.
3. Rapprochement des données ERP, liaison et web.
4. Analyse des prix, du chiffre d'affaires, des quantités vendues, du stock et des marges.
5. Étude des corrélations et restitution des recommandations.

## Résultats calculés dans le projet

- **825 produits** dans le référentiel ERP.
- **714 produits** rapprochés pour l'analyse des ventes.
- **143 680,10 €** de chiffre d'affaires calculé.
- **17 822 unités** en stock après les traitements du notebook.
- **298 627,66 €** de stock valorisé au coût d'achat après ces traitements.

Ces résultats correspondent aux conventions de traitement du projet pédagogique.

## Consulter et exécuter le notebook

Le notebook peut être consulté directement sur GitHub. Les graphiques interactifs Plotly sont à ouvrir dans Jupyter pour bénéficier de leur interactivité.

Pour l'exécuter, installer les dépendances dans un environnement Python, puis lancer Jupyter depuis ce dossier :

```bash
python -m pip install -r requirements.txt
python -m notebook
```

Ouvrir le notebook et conserver les fichiers Excel à ses côtés. La cellule d'export réécrit `dataset_final_bottleneck.xlsx` dans le dossier d'exécution : utiliser une copie du dossier pour une nouvelle exécution.

## Version publiée

Les six fichiers du projet sont conservés tels qu'ils ont été fournis, sans modification du notebook, de la présentation ni des données. Seuls ce README, la liste des dépendances et le fichier d'exclusion Git ont été ajoutés pour la publication.

## Auteur

Paco Humbert — Projet réalisé dans le cadre de la formation Business Intelligence Analyst d'OpenClassrooms.
