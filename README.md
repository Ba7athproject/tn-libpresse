# RSF Explorer — Tunisie 2013–2026

Une interface pensée pour comparer l'état de la liberté de la presse entre la Tunisie et l’Afrique du Nord, le reste de l’Afrique et l’Europe, en alternant vue analytique, vue de synthèse et scénarios éditoriaux.

Données basées sur les rapports de RSF (2013-2026), collectées par DW dans le cadre d'un article data-analytique publié sur GitHub. L'interface est élaborée par l'équipe du Projet Ba7ath.

## Objectif

Ce projet propose un microsite statique pour explorer l'évolution de la liberté de la presse sur la période 2013–2026, avec la Tunisie comme point de référence permanent.

L'application permet de :
- comparer la Tunisie avec des pays d’Afrique du Nord, du reste de l’Afrique et d’Europe ;
- basculer entre plusieurs lectures visuelles ;
- utiliser des scénarios éditoriaux rapides pour contextualiser une trajectoire nationale ;
- consulter une table de synthèse sur les évolutions de score et de rang.

## Source des données

Les données utilisées dans cette interface sont basées sur les rapports annuels de Reporters sans frontières (RSF) couvrant la période 2013–2026.

Le jeu de données consolidé a été collecté et structuré par DW dans le cadre d'un travail data-analytique publié sur GitHub.

## Crédit interface

L'interface, la logique de comparaison et l'expérience de navigation ont été élaborées par l'équipe du Projet Ba7ath.

## Structure 

```text
.
├── index.html
├── README.md
└── data/
    └── 2013-2026-with-secondary-data.csv
```

## Technologies utilisées

- HTML/CSS/JavaScript
- Plotly.js pour les graphiques
- Papa Parse pour le chargement et le parsing du CSV
- GitHub Pages pour l’hébergement statique

## Licence et réutilisation

Le code de l’interface peut être adapté et réutilisé dans un cadre éditorial, pédagogique ou de recherche, sous réserve de conserver les mentions de source des données et du travail d’interface.
