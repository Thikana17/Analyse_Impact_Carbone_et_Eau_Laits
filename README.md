Problématique :
Dans le débat écologique, on se focalise souvent uniquement sur l'empreinte carbone (CO2). Pourtant, pour certains aliments comme le lait d'amande, le véritable enjeu se situe ailleurs : la consommation d'eau.

Ce projet analyse si le lait d'amande est réellement l'alternative la plus durable face au lait de vache et aux autres options végétales (soja, avoine, riz).

📊 Méthodologie & Analyse
L'analyse s'appuie sur le dataset de l'Université d'Oxford (Our World in Data). J'ai traité les données pour comparer trois indicateurs clés par verre de 200ml :
- Émissions de CO2 : Le lait d'amande est performant (environ 0.14 kg).
- Utilisation des terres : Il nécessite peu d'espace.
- Consommation d'eau : C'est le point critique. ### Résultats de l'analyse :

Le constat : Avec 74 litres d'eau par verre, le lait d'amande consomme 20 fois plus d'eau que le lait de soja et 10 fois plus que le lait d'avoine.

L'interprétation : 80% des amandes mondiales viennent de Californie, une région en stress hydrique permanent. Utiliser la Data permet de voir que réduire son CO2 peut parfois aggraver une crise de l'eau localement.

Stack Technique
Python : Nettoyage des données (Outliers, normalisation des unités).

Pandas : Agrégation des données par type de lait.

Plotly : Création de graphiques comparatifs (Bar charts & Scatter plots pour corréler CO2 et Eau).
