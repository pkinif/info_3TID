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

### Théorie sous-jacente aux Exercices

Chaque exercice est conçu pour renforcer une compétence spécifique en analyse de données utilisant Excel.

#### Exercice 1 : Calcul du Total des Matchs Joués
**Concept :** La somme totale d'une colonne numérique.
**Formule Excel :** `SOMME` permet d'additionner toutes les valeurs d'une colonne.

#### Exercice 2 : Identification du Joueur avec le Plus de Victoires
**Concept :** Trouver le maximum dans une série de données.
**Formule Excel :** `MAX` trouve la valeur la plus élevée. `MATCH` localise la position de cette valeur dans la colonne. `INDEX` récupère le nom du joueur correspondant à cette position.

#### Exercice 3 : Détermination de la Région avec le Plus Grand Nombre de Joueurs
**Concept :** La mode d'une série de données catégorielles.
**Formule Excel :** `MODE` ou `MODE.SNGL` détermine l'élément le plus fréquent dans une colonne.

#### Exercice 4 : Calcul de la Moyenne de RatioKDA pour 'League of Legends'
**Concept :** Calculer une moyenne conditionnelle.
**Formule Excel :** `MOYENNE.SI` calcule la moyenne des valeurs dans une colonne qui correspondent à un critère spécifique.

#### Exercice 5 : Création d'un Graphique en Barres pour le Nombre de Joueurs par Équipe
**Concept :** Visualisation des données.
**Action Excel :** L'outil de création de graphique permet de transformer les données numériques en une représentation visuelle facilitant leur compréhension.

## Exercices Pratiques

Pour mettre en pratique les concepts appris, suivez les instructions ci-dessous et utilisez le jeu de données fourni pour compléter les exercices.

1. **Calculer le nombre total de matchs joués.**
   - Utilisez la fonction `SOMME` sur la colonne `MatchsJoués`.
2. **Trouver le joueur avec le plus grand nombre de victoires.**
   - Combinez `MAX`, `MATCH` et `INDEX` pour identifier ce joueur dans la colonne `Victoires`.
3. **Quelle région a le plus grand nombre de joueurs ?**
   - Utilisez `MODE.SNGL` pour trouver la région la plus fréquente dans la colonne `Région`.
4. **Calculer la moyenne des RatioKDA pour le jeu 'League of Legends'.**
   - Appliquez `MOYENNE.SI` pour filtrer le jeu spécifique et calculer la moyenne.
5. **Créez un graphique en barres du nombre de joueurs par équipe.**
   - Sélectionnez les données appropriées et utilisez l'assistant graphique pour créer un graphique en barres.

## Approfondir Vos Connaissances

Pour chaque exercice, prenez le temps de comprendre ce que vous faites et pourquoi. N'hésitez pas à expérimenter avec d'autres données ou formules pour explorer ce qu'Excel a à offrir.
