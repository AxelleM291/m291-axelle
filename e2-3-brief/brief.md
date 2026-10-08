# Brief - Arboris
## Pitch
Mon application servira aux gens intéressés à reconnaître les arbres et arbustes de nos régions, en fonction des feuilles de la plante en question. L'application sera principalement utilisées sur mobile et proposera directement à son ouverture des filtres pour identifier l'arbre face à l'utilisateur. Il n'y a pas de compte.

## Public
Dominique Dujardin, un enseignant de 50 ans résidant à Ste-Croix, utilise un smartphone reconditionné au forfait internet limité pour identifier et apprendre à reconnaître les arbres de sa région. Pour répondre à ses besoins de reconnexion à la nature et éliminer ses frustrations liées aux interfaces complexes, aux publicités et au jargon botanique incompréhensible, le produit devra suivre des règles de conception strictes : une approche mobile-first, une accessibilité immédiate sans création de compte ni publicité, une ouverture directe sur les filtres de sélection, et une explication claire des termes techniques pour garantir un apprentissage simple et rapide.

## Écrans
- accueil
- criteres
- options
- arbre

## Contenu de chaque écran
accueil : 
- Bouton : filter la sélection (mène vers l'écran criteres)
- Bouton : supprimer les filtres
- Liste de cartes d'arbres correspondants aux filtres : chaque carte contient une image de l'arbre et son nom, chaque carte mène à la page arbre correspondante

criteres
- Croix en haut à droite pour refermer l'écran critere (et ramener à l'écran accueil)
- Liste des critères avec pour chacun une flèche sur la droite. Chaque critères est un bouton menant à l'écran options correspondant
- Bouton : Rechercher (valide les critères et mène à l'écran d'accueil)

options
- Flèche vers la gauche pour revenir à la page criteres
- Nom du critère (À côté de la flèche)
- Image (schéma) explicative du critère
- Liste à choix multiple des options correspondantes au critère
- Bouton : Valider (enregistre la sélection et retourne à l'écran criteres)

arbre
- Flèche vers la gauche pour revenir à la page accueil
- Nom de l'arbre (À côté de la flèche)
- Photo de l'arbre pour pouvoir l'identifier visuellement
- Informations textuelles sur l'arbre

## Ambiance visuelle
- Nature
- Chaleureux
- Rafraichissant
- Simplicité
- Apprentissage

## 3 directions artistiques
1. Sobre
Typographie
- Titres : DM Serif Display — élégant, légèrement botanique
- Texte/interface : Inter — très lisible et moderne
Couleurs
- Vert forêt #254D32
- Vert sauge #A8BFA3
- Crème #F7F5EE
- Brun très foncé #252521
Formes : cartes simples, coins légèrement arrondis, beaucoup d'espace blanc.
Particularité : les schémas des critères peuvent avoir un aspect illustration scientifique

2. Chaleureuse

Typographie
- Titres : Lora Bold — chaleureuse et organique
- Texte/interface : Nunito Sans — arrondie et accessible
Couleurs
- Vert mousse #526B45
- Terracotta #B86645
- Beige chaud #F2E8D5
- Jaune feuille #D6A84F
- Brun #3B3028
Formes : boutons et cartes avec des arrondis assez généreux.
Particularité : utiliser de petites illustrations de feuilles comme éléments décoratifs, sans surcharger l'interface.

3. Audacieuse

Typographie
- Titres : Space Grotesk Bold — géométrique et affirmée
- Texte/interface : Manrope — moderne et très lisible
Couleurs
- Vert profond #123C32
- Vert électrique #8CC63F
- Crème #F4F1E8
- Orange vif #E87532
- Noir #171A18
Formes : grands aplats de couleur, cartes très graphiques
Particularité : Chaque critère pourrait avoir son propre pictogramme

## Interdits
- Pas de Bootstrap
- Pas de création de compte
- Pas de publicité
- Interface pas pratique, qui ne s'ouvre pas directement sur les filtres de sélection, ce qui fait perdre du temps (et des clics)
- Des termes spécifiques qui n'ont pas d'explication