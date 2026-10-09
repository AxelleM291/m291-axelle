# Brief - Arboris
## Pitch
### Concept
Mon application servira aux gens intéressés à reconnaître les arbres et arbustes de nos régions, en fonction des feuilles de la plante en question. L'application sera principalement utilisées sur mobile et proposera directement à son ouverture des filtres pour identifier l'arbre face à l'utilisateur. Il n'y a pas de compte.

### Pour qui
Les adultes intéressés par les arbres de nos régions, mais qui n'ont pas le temps de tout apprendre par coeur dans un livre.

### Quel besoin réel non satisfait
Apprendre à reconnaître des arbres par coeur prend du temps, et nécessite souvent un livre qu'il faut payer ou alors empreinter à la bibliothèque, mais que l'on n'a jamais sur soit au moment où l'on veut l'utiliser.

### La solution
Les arbres sont dehors, et la seule chose qu'on prend systhématiquement avec nous lorsqu'on sort, c'est notre téléphone. L'application web propose donc d'afficher en quelques clics à peine l'arbre qui se trouve en face de vous, sans création de compte et sans publicité, ce qui vous permet d'apprendre au fur et à mesure à reconnaître les différents arbres.

## Public
### Persona
**Nom et prénom**
Dominique Dujardin

**Âge**
50 ans

**Lieu de résidence**
Ste-Croix

**Métier**
Enseignant en secondaire 1

**Appareil principal**
Smartphone reconditionné avec un forfait data limité. 

**Besoins fonctionnels**
Savoir rapidement l'espèce de l'arbre ou de l'arbustre tout en apprenant au fur et à mesure de son utilisation de l'application à reconnaître par soi-même les plantes de nos régions, de manière à se sentir plus connecté à la terre et à ce qui l'entoure.

**Irritations majeurs**
Les sites compliqués d'accès, où il faut se créer un compte ou alors fermer des publicités en cliquant sur des boutons minuscules. Le manque d'explication des termes spécifiques permettant de différencier les feuilles, qui rende la recherche trop compliquée.

**Citation**
« Je veux un outil pratique pour identifier et apprendre les arbres de la régions, avec lequel j'ai pas besoin de me casser la tête sur des termes compliqués ou une interface que je ne comprends pas. »

## Écrans
- accueil
- criteres
- options
- arbre

## User-flow
1. Dominique clic sur le bouton filtre
2. Dominique choisi le critère à modifier
3. Dominique choisi les options correpsondantes à la feuille
4. Dominique valide les options
5. Dominique valide les critères
6. Dominique regarde la liste des arbres proposés et clic sur celui qui semble correspondre

## Contenu de chaque écran
accueil : 
- Bouton : filter la sélection (ouvre la boîte de dialogue criteres)
- Bouton : supprimer les filtres
- Liste de cartes d'arbres correspondants aux filtres : chaque carte contient une image de l'arbre et son nom, chaque carte mène à la page arbre correspondante

criteres (boîte de dialogue qui s'affiche par dessus l'écran accueil)
- Croix en haut à droite pour refermer la boîte de dialogue criteres
- Liste des critères avec pour chacun une flèche sur la droite. Chaque critères est un bouton ouvrant la boîte de dialogue options correspondante
- Bouton : Rechercher (valide les critères et ferme la boîte de dialogue criteres)

options (boîte de dialogue)
- Flèche vers la gauche pour revenir à la page criteres
- Nom du critère (À côté de la flèche)
- Croix en haut à droite pour refermer la boîte de dialogue
- Image (schéma) explicative du critère
- Liste à choix multiple des options correspondantes au critère
    - Feuille ou aiguille
        - options :
            - Aiguilles
            - Feuille [plane]
    - Type de feuilles
        - options :
            - feuille simple
                - pennée
                - palmée
            - feuille composée
                - pennée
                - palmée
    - Disposition sur le rameau
        - options :
            - opposées
            - Alternes
    - Bord de la feuille
        - options :
            - bord découpé
                - crénelé
                - lobé
            - bord non-découpé
                - lisse
                - ondulé
                - denté
                - doublement denté
    Les sous-critères sont affichés uniquement si le critère parent est sélectionné. Ce sont également des choix multiples.
- Bouton : Valider (enregistre la sélection et retourne à la boîte de dialogue criteres)

arbre (page à part entière)
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

## Règles de conception
- Mobile first
- Pas de création de compte
- Pas de publicité
- Interface pratique, qui s'ouvre directement sur les filtres de sélection de manière à ne pas perdre du temps
- Une explication accompagnant les termes spécifiques pour permettre d'apprendre tout en étant facile d'accès

## Interdits
- Bootstrap
- Création de compte
- Publicité