# ML_real_estate_project
L'objectif de ce projet est de créer un modèle prédictif pour prédire la valeur des logements en Californie.


## Contexte du projet
Vous êtes développeur AI dans une startup de la Silicon Valley qui fournit des services dans le domaine de l'investissement immobilier. Les chargés de relation client ont mentionné que la demande a augmenté récemment et qu'il devient difficile de faire des estimations personnalisées. De ce fait, l'entreprise vous a confier d'automatiser cette tâche avec un modèle prédictif.

Pour cela, vous avez récupéré une base de données qui contient les prix médians des logements pour les districts de Californie issus du recensement de 1990 :

**longitude**

**latitude**

**housingMedianAge:** Âge médian d'une maison dans un pâté de maisons ; un chiffre plus bas correspond à un bâtiment plus récent.

**totalRooms:** Nombre total de chambres dans un bloc

**totalBedrooms:** Nombre total de chambres dans un bloc

**population:** Nombre total de personnes résidant dans un bloc

**households:** Nombre total de ménages, c'est-à-dire un groupe de personnes résidant dans une unité d'habitation, pour un bloc

**medianIncome:** Revenu médian des ménages dans un bloc de maisons (mesuré en dizaines de milliers de dollars US)

**medianHouseValue:** Valeur médiane des maisons pour les ménages d'un bloc (mesurée en dollars US)

**oceanProximity:** Situation de la maison par rapport à la mer

L'objectif est de créer un modèle avec vos données (train) pour prédire la valeur du prix médian des maisons par district / bloc (medianHouseValue).

A la fin du projet, vous devez évaluer ce modèle avec les données (validation) que seul votre client dispose (le prof).
