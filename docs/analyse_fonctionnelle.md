# Analyse fonctionnelle – Tableau de bord fiscal TFPB

## 1. Contexte

Ce projet a été réalisé dans un cadre fictif de mission d’analyse au sein d’une administration fiscale nationale.  
Il s’appuie sur les données REI 2021 relatives à la taxe foncière sur les propriétés bâties (TFPB) en france, avec pour objectif de produire un tableau de bord synthétique, utilisable par un agent ou analyste dans le cadre d’un travail de contrôle ou de suivi.

## 2. Demande utilisateur

**Profil utilisateur** : collaborateur au sein d’un service en charge de la fiscalité à l'échelle nationale.

**Demande exprimée** :

> "Je voudrais avoir un outil qui me donne une meilleure lecture des données fiscales issues de la TFPB.  
> J’ai besoin d’une vision claire des montants en jeu, et de pouvoir repérer rapidement les situations anormales ou qui méritent d’être vérifiées."

## 3. Interprétation de la demande

Bien que formulée de manière générale, la demande laisse apparaître trois besoins essentiels :
- Comprendre les grandes tendances et volumes liés à la perception de la TFPB
- Identifier les communes présentant des écarts importants entre les montants perçus et attendus
- Prioriser les cas à analyser de manière plus poussée

## 4. Indicateurs clés (KPI)

Les indicateurs retenus dans le tableau de bord sont :
- Écart moyen relatif (en %)
- Nombre de communes avec un écart supérieur à 10 %
- Produit total perçu (agrégé)
- Produit total attendu (agrégé)

Ces KPI offrent une lecture synthétique du système fiscal sur cette taxe à l’échelle nationale.

## 5. Visualisations principales

- **Cartes KPI** : affichent les valeurs globales en haut du rapport
- **Histogramme** : présente les 10 communes ayant les écarts signés les plus élevés
- **Scatter plot** : montre la relation entre la base nette imposable et l’écart relatif (absolu)
- **Tableau de détails** : liste les communes avec leurs montants perçus, attendus et les écarts correspondants

## 6. Résultat attendu

Le tableau de bord permet à l’utilisateur :
- D’obtenir une lecture synthétique des données fiscales sur la TFPB
- De repérer rapidement les cas atypiques ou suspects
- De cibler les communes à examiner en priorité, sans avoir besoin de traitement manuel des données brutes
