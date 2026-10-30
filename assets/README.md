# Visuels du profil

Les visuels essentiels sont stockés dans ce dépôt. Aucun service de badges ou de génération d’images à distance n’est nécessaire à leur affichage.

## Bannière

[`header.svg`](header.svg) est une composition vectorielle créée pour ce profil : bleu nuit, ardoise et bleu clair. Elle est statique, sans script, animation, police distante ni ressource externe. Le nom et le positionnement sont aussi disponibles dans le Markdown.

## Captures authentiques

Les deux PNG ont été copiés à l’identique depuis les projets sources. Ils ne sont ni recadrés, ni retouchés, ni reconstitués. Les empreintes SHA-256 permettent de vérifier leur identité avec les originaux.

| Fichier du profil | Source publique | Nature du résultat |
| --- | --- | --- |
| [`projects/cv-extraction.png`](projects/cv-extraction.png) | [Projet CV, capture d’origine au commit e9c8fda](https://github.com/arabat-med/Projet-CV-ATS-main/blob/e9c8fda/docs/images/08-resultat-detail.png) | Résultat réel de l’application avec le CV fictif Camille EXEMPLE. Le pourcentage indique la complétude des rubriques, sans mesure de précision NLP. |
| [`projects/v2v-simulation.png`](projects/v2v-simulation.png) | [Projet V2V, capture d’origine au commit 6528f0e](https://github.com/arabat-med/v2v-traffic-simulation/blob/6528f0e/docs/images/02-vue-aerienne-ign.png) | Fenêtre Qt6/QML à Bourtzwiller, Mulhouse. Véhicules et liens simulés sur un fond photographique IGN ; aucune détection de véhicules dans ce fond. |

```text
66c4396284b57e99292af14c4509a788117479c06b1b1f2733f9c5c90d33fd27  projects/cv-extraction.png
43370430ffaae60c6edaa89c1658ce258604b9057a04aa8322a524b599a30564  projects/v2v-simulation.png
```

La capture CV conserve des données fictives explicitement identifiées. La capture V2V conserve ses attributions cartographiques, dont © IGN. Les licences et conditions des éléments sources restent celles des projets et fournisseurs ; aucune licence de réutilisation supplémentaire n’est attribuée ici.

Voir le [protocole CV](https://github.com/arabat-med/Projet-CV-ATS-main/blob/master/docs/DEMONSTRATIONS.md), le [protocole V2V](https://github.com/arabat-med/v2v-traffic-simulation/blob/main/docs/images/README.md) et les [notices V2V](https://github.com/arabat-med/v2v-traffic-simulation/blob/main/THIRD_PARTY_NOTICES.md).
