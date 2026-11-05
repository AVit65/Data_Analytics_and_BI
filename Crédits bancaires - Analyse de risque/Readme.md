# Analyse des crédits bancaires et prédiction du risque de défaut - Power BI

**Projet personnel | Data Analytics · Machine Learning · Business Intelligence · Power BI**

## Présentation du projet

Ce projet consiste à développer un tableau de bord interactif sous **Microsoft Power BI** pour explorer les caractéristiques des clients d'un établissement bancaire, analyser leurs demandes de crédit et étudier les facteurs associés au risque de défaut de remboursement.

Il combine une approche de **Business Intelligence**, destinée à synthétiser et explorer les données bancaires, avec une approche de **Machine Learning**, reposant sur un modèle prédictif personnellement entraîné pour estimer le risque de défaut des clients.

L'objectif est de transformer des données bancaires et socio-économiques en indicateurs exploitables et en visualisations permettant de répondre à plusieurs questions :

- Quel est le profil démographique et socio-économique des clients ?
- Comment les clients se répartissent-ils selon leur âge, leur sexe, leur situation familiale ou leur région ?
- Quels sont les montants et les types de crédits demandés ?
- Quelle proportion des demandes de crédit est acceptée, refusée ou annulée ?
- Comment les décisions de crédit varient-elles selon les caractéristiques des clients ?
- Quelle proportion de clients présente un défaut de remboursement ?
- Quelles caractéristiques contribuent le plus à la prédiction du risque de défaut ?
- Comment exploiter les scores prédictifs pour identifier les profils nécessitant une attention particulière ?

Le projet s'articule autour de **trois pages d'analyse complémentaires**, allant de la connaissance des clients à l'exploration du risque de crédit à partir des résultats d'un modèle prédictif.

## 1. Clients - Analyse des profils

Cette première page propose une vue d'ensemble de la clientèle et de ses caractéristiques démographiques et socio-économiques.

Elle permet notamment de :

- Suivre le nombre total de clients, leur revenu moyen et leur âge moyen.
- Visualiser la répartition des clients selon leur sexe.
- Explorer la distribution des âges au sein de la clientèle.
- Analyser la répartition géographique des clients à l'échelle régionale.
- Étudier la composition de la clientèle selon la situation familiale.
- Comparer les distributions de revenus en fonction du statut familial.
- Filtrer les analyses par identifiant client et explorer différentes caractéristiques.

Les indicateurs synthétiques permettent également de suivre la **proportion de clients présentant un défaut de remboursement**, afin d'introduire une dimension de risque dans l'analyse de la clientèle.

Cette page constitue une première étape de compréhension de la population étudiée, en mettant en évidence sa diversité et les principales caractéristiques susceptibles d'être approfondies dans les analyses suivantes.

## 2. Crédits internes - Analyse des demandes et des décisions

Cette deuxième page est consacrée à l'étude des demandes de crédit et de leur traitement.

Elle présente plusieurs indicateurs :

- Montant total des crédits.
- Montant moyen des crédits accordés.
- Nombre moyen de crédits par client.
- Pourcentage de demandes de crédit approuvées.

Les visualisations permettent d'approfondir cette analyse :

- **Répartition des statuts des crédits** : comparaison des proportions de demandes approuvées, refusées, annulées ou associées à une offre non utilisée.
- **Distribution des types de crédits accordés** : analyse des montants selon les catégories de crédit, notamment les prêts à la consommation, les prêts de trésorerie et les crédits renouvelables.
- **Distribution des montants** : comparaison des montants de crédit selon le type de revenus des clients.
- **Nombre de crédits accordés et refusés par client** : exploration de la distribution des demandes et de leurs différents statuts.
- **Distribution des types de crédits** : analyse de la composition des demandes selon différentes caractéristiques des clients.

Les filtres interactifs permettent d'explorer ces résultats selon le type de revenus, le statut du contrat, le type de client et l'identifiant client.

Cette page permet de dépasser les volumes globaux pour mieux comprendre **la structure des demandes de crédit, les décisions d'octroi et leur répartition entre les différents profils de clients**.


## 3. Clients à risque - Analyse prédictive du défaut de remboursement

Cette troisième page est consacrée à l'analyse du risque de défaut de remboursement. Elle associe des indicateurs descriptifs aux résultats d'un **modèle de Machine Learning personnellement entraîné**, afin d'explorer les profils de risque et les caractéristiques contribuant aux prédictions.

Elle présente plusieurs indicateurs :

- Nombre total de clients.
- Pourcentage de clients présentant un défaut de remboursement.
- Montant moyen restant dû des clients étudiés.
- Montant moyen des demandes de crédit.

Les visualisations permettent d'approfondir cette analyse :

- **Distribution du taux de défaut** : exploration de la fréquence des défauts selon différentes caractéristiques des clients, notamment leur âge.
- **Comparaison des profils selon le statut de défaut** : analyse des distributions de variables sélectionnées entre les clients ayant présenté un défaut et les autres.
- **Importance des caractéristiques** : classement des variables selon leur contribution aux prédictions du modèle, afin d'identifier les facteurs les plus influents dans l'estimation du risque.
- **Scoring individuel** : consultation des scores de risque produits par le modèle pour chaque client, permettant d'explorer les prédictions à l'échelle individuelle.

Cette page permet ainsi de compléter l'analyse descriptive par une **approche prédictive du risque de crédit**, en reliant les caractéristiques des clients aux estimations produites par le modèle.

L'intégration de ces résultats dans Power BI facilite leur interprétation et leur exploration, dans une perspective d'aide à la décision.

Les scores représentent des estimations issues du modèle et ne constituent pas des certitudes quant à la survenue d'un défaut de remboursement.

## Modélisation prédictive — Scoring du risque de crédit

En complément du travail de visualisation, ce projet intègre un **modèle de Machine Learning développé et entraîné pour prédire le risque de défaut de remboursement** à partir des caractéristiques des clients.

Les scores individuels produits par le modèle sont intégrés au tableau de bord Power BI afin de rendre les résultats accessibles et explorables.

Cette démarche permet d'articuler deux niveaux d'analyse :

- **Analyse descriptive** : comprendre la composition de la clientèle, les demandes de crédit et la fréquence des défauts observés.
- **Analyse prédictive** : estimer le risque individuel de défaut et explorer les caractéristiques influençant les prédictions du modèle.

Le classement des variables importantes complète cette approche en apportant des éléments d'interprétation sur les facteurs utilisés dans l'estimation du risque.

L'objectif n'est donc pas uniquement de produire des prédictions, mais également de **les restituer dans un environnement interactif permettant de les confronter aux caractéristiques des clients et aux indicateurs bancaires**.

## Compétences et outils mobilisés

| Outil / Compétence | Utilisation dans le projet |
|---|---|
| **Power BI Desktop** | Création du rapport et des visualisations interactives |
| **Power Query** | Importation, préparation et transformation des données |
| **DAX** | Calcul des indicateurs clients, des montants de crédit, des taux d'approbation et de défaut |
| **Modélisation relationnelle** | Mise en relation des informations clients, des demandes de crédit et des caractéristiques associées |
| **Machine Learning** | Développement et entraînement d'un modèle prédictif du risque de défaut |
| **Scoring prédictif** | Production de scores individuels pour les clients |
| **Interprétabilité des modèles** | Analyse de l'importance des caractéristiques dans les prédictions |
| **Data Visualisation** | Conception de graphiques, cartes géographiques, tableaux, indicateurs KPI et filtres interactifs |
| **Analyse exploratoire** | Étude des distributions, comparaison des profils et identification de tendances |
| **Valorisation des modèles ML** | Intégration des résultats prédictifs dans un tableau de bord interactif |

## Démarche analytique

Le développement du projet repose sur plusieurs étapes :

1. **Structuration des données** : organisation des informations relatives aux clients, aux demandes de crédit et aux variables de risque.
2. **Préparation et transformation** : harmonisation des champs, traitement des données et création des variables nécessaires aux analyses.
3. **Modélisation relationnelle** : définition des relations entre les tables afin de permettre une exploration cohérente des données.
4. **Création des indicateurs** : calcul des effectifs, des montants moyens, des proportions de crédits approuvés et des taux de défaut.
5. **Modélisation prédictive** : entraînement d'un modèle de Machine Learning destiné à estimer le risque de défaut de remboursement.
6. **Intégration du scoring** : exploitation des scores individuels et des importances de variables dans Power BI.
7. **Visualisation** : conception de trois pages thématiques permettant de passer d'une vue générale de la clientèle à une analyse détaillée du risque.
8. **Vérification** : contrôle de la cohérence des indicateurs, des agrégations et des résultats affichés selon les filtres sélectionnés.

Une attention particulière est portée à la distinction entre **clients, demandes de crédit et contrats**, afin de calculer les indicateurs au niveau d'observation approprié.

Cette distinction est essentielle : un même client peut effectuer plusieurs demandes de crédit, et le nombre de demandes ne correspond donc pas nécessairement au nombre de clients.

## Organisation du dépôt

```text
analyse-credits-bancaires-powerbi/
│
├── README.md
│
└── Screenshots/
    ├── 01_analyse_clients.png
    ├── 02_analyse_credits.png
    └── 03_analyse_risque.png
```

## Limites du projet

- Les résultats dépendent de la qualité, de la représentativité et de l'exhaustivité des données disponibles.
- Les taux d'approbation et de défaut dépendent des définitions retenues et du périmètre des données analysées.
- L'importance des variables renseigne sur leur contribution aux prédictions, sans démontrer un effet causal.
- Les captures d'écran présentent une version statique du rapport : les interactions et les filtres Power BI ne sont pas accessibles directement sur GitHub.

---

*Projet personnel réalisé dans une démarche d'application des compétences en analyse de données, Machine Learning, modélisation prédictive, calcul d'indicateurs et visualisation interactive, avec pour objectif de rendre les résultats d'un modèle de scoring exploitables dans un outil d'aide à la décision.*