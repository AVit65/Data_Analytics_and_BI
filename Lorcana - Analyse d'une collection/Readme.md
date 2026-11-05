# Disney Lorcana - Analyse et valorisation d'une collection avec Power BI

**Projet personnel | Data Analytics · Business Intelligence · Power BI**

## Présentation du projet

Ce projet consiste à développer un tableau de bord interactif sous **Microsoft Power BI** pour suivre, explorer et valoriser une collection de cartes du jeu Disney Lorcana.

L'objectif est de transformer des données de collection, d'ouvertures de boosters et de prix de marché en indicateurs synthétiques et en visualisations permettant de répondre à plusieurs questions :

- Quelle proportion de la collection est complétée ?
- Quelles cartes manquent encore, et dans quels chapitres ?
- Comment les cartes possédées se répartissent-elles selon leur rareté, leur couleur ou leur histoire ?
- Quelle est la composition des boosters ouverts et quelle est la fréquence des nouvelles découvertes ?
- Quelle est la valeur estimée de la collection et quelle part provient des doublons ?
- Quelles cartes et catégories contribuent le plus à sa valeur ?

Le projet s'articule autour de **trois pages d'analyse complémentaires**, allant du suivi de la collection à l'estimation de sa valeur.

## 1. Collection - Complétude et composition

Cette première page propose une vue d'ensemble de la collection et de sa progression.

Elle permet notamment de :

- Suivre le taux de complétion de la collection et le nombre de cartes manquantes.
- Visualiser la progression par chapitre.
- Explorer la répartition des cartes par rareté, couleur et type.
- Analyser les cartes possédées selon leur histoire ou leur univers Disney.
- Filtrer les résultats par chapitre, rareté, couleur, type de carte et histoire.

Les indicateurs synthétiques permettent de distinguer le nombre de **cartes physiques**, les **doublons** et la progression de la collection en termes de cartes différentes.

Cette distinction est essentielle : posséder plusieurs exemplaires d'une même carte augmente la taille physique de la collection, mais pas nécessairement son taux de complétion.

## 2. Boosters - Ouvertures et découvertes

Cette page est consacrée à l'analyse des boosters ouverts et à leur contribution à la progression de la collection.

Elle comprend plusieurs analyses :

- **Nouveautés et répétitions par booster** : évolution du nombre de nouvelles références découvertes et de la proportion de cartes déjà possédées.
- **Régularité des découvertes** : distribution du nombre de nouvelles cartes obtenues par booster.
- **Répartition des raretés** : comparaison de la composition des boosters selon l'acheteur ou selon la source des booster (Display ou hors Display)
- **Contrôle des ouvertures** : identification des boosters conformes et de ceux nécessitant une vérification.
- **Exploration des cartes** : consultation des cartes associées aux boosters, avec leurs illustrations.

Cette page permet d'étudier comment l'ouverture successive de boosters contribue à enrichir une collection, tout en faisant apparaître la fréquence croissante des répétitions.

Elle associe ainsi une dimension descriptive à une logique de **contrôle de la qualité des données**.

## 3. Valorisation - Analyse des prix

Cette troisième page s'intéresse à la valeur économique estimée de la collection.

Elle présente plusieurs indicateurs :

- Valeur totale estimée des cartes possédées.
- Valeur attribuable aux exemplaires supplémentaires.
- Valeur des cartes différentes possédées.
- Nombre de cartes dont le prix dépasse 10 €.
- Nombre de cartes pour lesquelles aucune estimation de prix n'est disponible.

Les visualisations permettent d'approfondir cette analyse :

- **Valeur totale par chapitre** : comparaison de la contribution de chaque chapitre à la valeur de la collection.
- **Valeur totale par rareté** : identification des catégories de rareté qui concentrent le plus de valeur.
- **Classement des cartes selon leur prix** : exploration des cartes les plus valorisées, avec leur illustration, leur rareté et les informations disponibles sur l'estimation.
- **Prix moyen des cartes** : comparaison des prix selon les chapitres et les raretés.
- **Répartition de la valeur par tranche de prix** : distinction entre la valeur des exemplaires uniques et celle des doublons selon différentes catégories de prix unitaires.

Cette approche permet de dépasser la simple estimation globale pour mieux comprendre **la structure et la concentration de la valeur** de la collection.

Les prix présentés constituent des estimations dépendant des données de marché disponibles et ne garantissent pas un prix de revente.

## Compétences et outils mobilisés

| Outil / Compétence | Utilisation dans le projet |
|---|---|
| **Power BI Desktop** | Création du rapport et des visualisations interactives |
| **Power Query** | Importation, nettoyage et transformation des données |
| **DAX** | Calcul des indicateurs de collection, des doublons et des estimations de valeur |
| **Modélisation relationnelle** | Mise en relation des cartes, des acquisitions, des boosters et des prix |
| **Data Visualisation** | Conception de graphiques, tableaux, indicateurs KPI et filtres interactifs |
| **Contrôle qualité** | Détection d'anomalies et identification des informations manquantes |

## Démarche analytique

Le développement du tableau de bord repose sur plusieurs étapes :

1. **Structuration des données** : organisation des informations relatives aux cartes, aux acquisitions, aux boosters et aux prix.
2. **Préparation et transformation** : harmonisation des champs et création des variables nécessaires aux analyses.
3. **Modélisation** : définition des relations entre les différentes tables.
4. **Création des indicateurs** : calcul des quantités possédées, des cartes manquantes, des doublons et des valeurs estimées.
5. **Visualisation** : conception de trois pages thématiques permettant d'explorer les données à différents niveaux.
6. **Vérification** : contrôle de la cohérence des données et des résultats affichés.

Une attention particulière est portée à la distinction entre **références de cartes**, **exemplaires physiques** et **versions standard ou premium**, afin de produire des indicateurs adaptés aux différentes analyses.

## Organisation du dépot 

```text
lorcana-powerbi-dashboard/
│
├── README.md
│
├── Screenshots/
│   ├── 01_vue_ensemble.png
│   ├── 02_analyse_boosters.png
│   └── 03_valorisation_cartes.png

```

## Limites du projet

- Les estimations de valeur dépendent des prix disponibles.
- Certaines cartes ne disposent pas d'une estimation exploitable.
- Les résultats reflètent l'état de la collection et des données au moment de leur actualisation.
- Les captures d'écran présentent une version statique du rapport : les interactions et filtres Power BI ne sont pas accessibles directement sur GitHub.

---

*Projet personnel réalisé dans une démarche d'application des compétences en analyse de données, modélisation, calcul d'indicateurs et visualisation interactive.*