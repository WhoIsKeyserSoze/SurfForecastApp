# SurfForecastApp

![image](https://user-images.githubusercontent.com/59146778/204785395-2d4db1cf-4d92-46b2-976f-14e492a1809c.png)

<h2>Introduction:</h2>

En 2022 les surfeurs du monde entier utilisent des solutions de surf forecast pour evaluer au mieux les conditions de surf afin de planifier leurs session de manière à avoir la meilleure qualité de vagues possible. 

Avant internet, les surfeurs devaient acquierir des connaissances théoriques sur la houle, le vent, les fond marins et tous les parametres qui ont une influence sur la consistance et l'apparence des vagues au moment ou elles cassent sur la cote. 
On a ensuite eu des sites de prévision météo classiques surs lesquels on peut trouver les indicateurs bruts à partir de relevés locaux. 

De nos jours, il existe un grand nombre de solutions en ligne qui resument les indicateurs utiles à la prise de décision. Cependant de part la portée mondiale de ces solutions, celles-ci se voient obligées de concevoir des modèles de prédictions très généraux pour être efficaces sur un maximum de localisations.

Mais voila, le système qui régit les vagues est un système extremement complexe qui met en oeuvre une multitude de parametre. Certains de ces parametres vont pouvoir être utilisés de la même manière indépendemment de la localisation, mais une grosse partie va aussi influer très différemment en fonction du 'spot', de la topologie du fond marin, la topologie de la cote (par exemple une falaise, une plaine et une foret vont influer différemment sur la manière dont un vent offshore, qui vient des terres, va interagir avec la houle) et d'autres paramètres locaux.

Par conséquent, les solutions mondiales telles "magicseeweed", "surfline", "surfreport", vont pouvoir donner une bonne idée générale l'état des conditions mais vont être incapables d'apporter de la précision dans ces prédictions.

Pour avoir cette précision, l'utilisateur doit se rendre sur une multitude de sites web afin de collecter chacune des information à la ou les sources les plus pertinentes par rapport à sa localisation.


<h2>Objectif de notre application:</h2>

L'objectif premier de notre application est d'automatiser la collecte de ces données, ciblé dans un premier temps sur quelques spots de la région, afin de centraliser la recherche d'information pour la rendre moins chronophage. Il s'agit de choisir les sources pour chacun des indicateurs, récupérer les données (scraping / api), concevoir et mettre en place un visualisation efficace pour la prise de décision.

L'objectif secondaire pour aller plus loin est la mise en place d'un ou plusieurs modèles d'intelligence artificielle pour effectuer une classification des conditions.
Le principal obstacle à cela est le manque de données labellisées. Cependant ce projet étant un projet à but non commercial, nous pourrions utiliser les 'reports' videos de 'lacanau surf info', disponibles 2 à 3 fois par jour tous les jours depuis des années.


<h2>Choix technologiques:</h2>

- Langage de programmation : python

- Scraping : beautiful soup ? Selenium ?

- Visualisation : Streamlit ? Dash ?

- TODO
