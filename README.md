# Cours d'Informatique: Manipulation et Visualisation de Données avec Excel et GitHub

## Bienvenue
Ce document est un guide complet pour notre cours sur la manipulation et la visualisation de données en utilisant Excel et GitHub. Il comprendra la théorie nécessaire, des instructions pratiques, et des exercices pour vous aider à comprendre comment travailler avec des fichiers CSV et à utiliser Excel pour l'analyse de données.

## Théorie et Pratique

### Section 1: Introduction aux Fichiers CSV et GitHub

**Qu'est-ce qu'un fichier CSV ?**
- Un fichier CSV (Comma-Separated Values) est un format qui stocke les données tabulaires sous forme de texte simple. Chaque ligne du texte correspond à une ligne du tableau, et les virgules séparent les colonnes. Ce format est privilégié car il est lisible par l'homme et machine, et est compatible avec de nombreux outils d'importation et d'analyse de données.

**Pourquoi utiliser GitHub ?**
- GitHub est une plateforme en ligne permettant l'hébergement et la gestion de code. Pour la science des données, GitHub est utilisé pour partager et collaborer sur des ensembles de données et des scripts d'analyse. Il assure le suivi des modifications, facilite la collaboration et partage des données ouvertes.

### Section 2: Importation de Données CSV depuis GitHub

**Comment importer des données depuis GitHub ?**
1. Trouvez le fichier CSV dans le dépôt GitHub et téléchargez-le.
2. Ouvrez Excel et allez dans l'onglet "Données".
3. Sélectionnez "Importer des données depuis un fichier texte/CSV".
4. Suivez l'assistant d'importation pour charger le fichier dans Excel.

### Section 3: Organiser et Visualiser les Données dans Excel

**Données au Format Tidy**
- Les données 'tidy' ont une colonne pour chaque variable et une ligne pour chaque observation. Cela simplifie les analyses et est une bonne pratique en science des données. Un tableau tidy permet des manipulations plus intuitives et des analyses statistiques plus directes.

**Filtrage et Gel des Panneaux**
- Le filtrage permet de voir seulement les données qui répondent à un critère défini. Excel permet de filtrer facilement les données en utilisant l'option "Filtre" dans l'onglet "Données".
- "Geler les volets" permet de garder une ligne ou une colonne visible pendant que vous faites défiler le reste de votre tableau. C'est utile pour suivre les en-têtes de colonne lorsque vous parcourez de longs ensembles de données.

**Amélioration de la Lisibilité des Données**
- Une bonne visualisation des données aide à comprendre rapidement les informations clés. Excel propose des outils comme la mise en forme conditionnelle, les styles de cellules, et les styles de tableau pour personnaliser l'apparence de vos données.

### Section 4: Fonctions de Base et Graphiques dans Excel

**Fonctions de Base d'Excel**
- Des fonctions comme SOMME(), MOYENNE(), MAX() et MIN() sont essentielles pour effectuer des calculs de base sur vos données. Nous allons explorer comment ces fonctions peuvent être appliquées pour obtenir des informations pertinentes à partir de notre ensemble de données.

**Création de Graphiques**
- Un graphique est un outil puissant pour la visualisation de données. Nous couvrirons comment sélectionner des données et les transformer en graphiques tels que des histogrammes, des graphiques linéaires, et des graphiques en barres dans Excel.

## Théorie des Données

### Comprendre les Données

Dans ce cours, nous allons travailler avec un jeu de données d'e-sport. Les données représentent des informations collectées sur les joueurs, leurs équipes et leurs performances dans les compétitions.

#### Variables du Jeu de Données
- `IDJoueur`: L'identifiant unique attribué à chaque joueur.
- `Équipe`: Le nom de l'équipe de l'e-sport à laquelle le joueur appartient.
- `Région`: La région géographique d'où provient l'équipe.
- `Jeu`: Le nom du jeu vidéo dans lequel le joueur est en compétition.
- `MatchsJoués`: Le nombre total de matchs que le joueur a disputés.
- `Victoires`: Combien de matchs le joueur a gagnés.
- `Défaites`: Combien de matchs le joueur a perdus.
- `TauxDeVictoire`: Le pourcentage de matchs gagnés sur le total des matchs joués.
- `MoyenneTués`: Le nombre moyen d'adversaires que le joueur a éliminés par match.
- `MoyenneMorts`: Le nombre moyen de fois que le joueur est mort par match.
- `RatioKDA`: Un indicateur de performance calculé à partir du nombre de tués, morts, et assistances.

### Exercices Pratiques sur Excel

#### Exercice 1: Total des Matchs Joués
Calculez la somme totale des matchs joués par tous les joueurs.

#### Exercice 2: Nombre Maximum de Victoires
Identifiez le nombre maximum de victoires qu'un joueur a obtenues.

#### Exercice 3: Nombre Minimum de Défaites
Trouvez le nombre minimum de défaites qu'un joueur a subies.

#### Exercice 4: Total des Victoires pour une Équipe Spécifique
Calculez le total des victoires pour l'équipe nommée "Team Alpha".

#### Exercice 5: Total des Défaites dans une Région
Déterminez le total des défaites pour tous les joueurs dans la région "Europe".

#### Exercice 6: Moyenne des Victoires
Calculez la moyenne du nombre de victoires par joueur.

#### Exercice 7: Total des Matchs Joués pour "League of Legends"
Additionnez le nombre total de matchs joués par les joueurs de "League of Legends".

#### Exercice 8: Total des Victoires en "Counter-Strike"
Trouvez le total des victoires pour les joueurs de "Counter-Strike".

#### Exercice 9: Nombre Maximum de Matchs Joués par un Joueur
Identifiez le nombre maximum de matchs qu'un joueur unique a joués.

#### Exercice 10: Nombre Minimum de Tués par Match
Recherchez le nombre minimum de tués par match qu'un joueur a réalisés.

#### Exercice Bonus: Ajout d'une Variable Binaire pour les Victoires
Créez une nouvelle colonne qui indique '1' si un joueur a gagné plus de 20 matchs, et '0' dans le cas contraire.

## Approfondir Vos Connaissances

Pour chaque exercice, prenez le temps de comprendre ce que vous faites et pourquoi. N'hésitez pas à expérimenter avec d'autres données ou formules pour explorer ce qu'Excel a à offrir.
