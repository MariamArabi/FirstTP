# Rendu N 1 : Calendar Chart
## Définition
Un calendar chart est une visualisation utilisée pour montrer l'activité au cours d'une longue période de temps, comme des mois ou des années. Ils sont mieux utilisés lorsque vous voulez illustrer comment une certaine quantité varie en fonction du jour de la semaine, ou comment elle évolue au fil du temps.
## Calendar Charts et navigateur
Les calendar charts sont rendus dans le navigateur en utilisant SVG ou VML, selon ce qui est approprié pour le navigateur de l'utilisateur. Comme tous les graphiques Google, les graphiques de calendrier affichent des infobulles lorsque l'utilisateur survole les données. Et crédit où le crédit est dû: notre tableau de calendrier a été inspiré par la visualisation du calendrier D3.
## Exemples
### Exemple 1 : classique
Disons que nous voulons montrer comment la présence d'une équipe sportive a varié tout au long de la saison. 
Avec un calendar chart, nous pouvons utiliser la luminosité pour indiquer les valeurs et laisser les gens voir les tendances en un coup d'œil:
![calendarchart1](https://user-images.githubusercontent.com/35372804/35143466-f122af22-fd01-11e7-8cab-184d9c940b23.PNG) - Exemple classique d'un calendar chart
Encore mieux, on peut passer la souris sur les jours individuels pour voir les valeurs de données sous-jacentes.
### Exemple 2 : un calendar chart classique et utilisé par tous
Le calendier est le graphique utilisé par tous. Il permet de visualiser les jours, les plannings, les évènement... :

![claendarchart2](https://user-images.githubusercontent.com/35372804/35143655-86741dcc-fd02-11e7-91f2-34a0e0fbaec7.PNG)  Calendrier

### Exemple 3 : carte de chaleur
Le graphique ci-dessous permet de montrer l'historique (ou les prévisions) de la température dans une région donnée. Dans cet exemple, il est accompagné d'un calcul de la moyenne de la température sur les mois, d'une courbe qui montre l'évolution en temps réel de la température et de la variation de la température moyenne sur les semaines :

![calendarchart 3](https://user-images.githubusercontent.com/35372804/35144212-2b0f3244-fd04-11e7-946f-13ba6edbc8b2.PNG) - Heat map

Il est facilement compréhensible, toutes les informations importantes sautent aux yeux sans besoin de déchiffrer ou d'avoir une certaine expertise dans la description des cartes de température. Pourtant, une telle visalisation pourrait dissimuler plusieurs données statistiques utiles qui ne peuvent pas être exposé dans un graphique.

### Exemple 4 : Diagramme de Gantt
Le diagramme de Gantt est un outil de gestion de projet développé à l'origine par Henry Gantt au début des années 1900. C'est un type de graphique à barres qui affiche les heures de début et de fin de chaque tâche dans un calendrier de projet. Les tâches sont généralement catégorisées à l'aide d'une structure de répartition du travail avec des tâches récapitulatives pour les principaux livrables du projet et des sous-tâches qui décomposent le projet en une hiérarchie de tâches détaillée et gérable. 
Voir la figure ci-desssous :

![gantt](https://user-images.githubusercontent.com/35372804/35144248-4cafad84-fd04-11e7-931a-e44d58e94d3a.PNG) - Diagramme de Gantt

Il est simplement mise en place avec Excel ou Google Sheets. Personnalisé, et donc permet de mettre au clair les informations voulu par l'utilisateur. Il ne nécessite pratiquement aucun apprentissage pour l'édition.

## Sources
* [Google Charts](https://developers.google.com/chart/interactive/docs/gallery/calendar) 
* [Vertex 42]( https://www.vertex42.com)

### Auteur

**Mariam ARABI**
