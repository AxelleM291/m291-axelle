# Mes étiquettes

Projet : Arboris

Une ligne par étiquette. Chaque étiquette, sauf `id`, doit servir à afficher, filtrer ou trier sur au moins un écran de votre brief (méthode en 6 questions, exercice 3).

| Étiquette | Écran du brief qui l'affiche | Sert à (afficher, filtrer, trier) | Sorte de valeur (texte, nombre, vrai/faux) | Unique ? | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | aucun | distinguer les fiches d'arbres | nombre | oui | 1 |
| `nom` | accueil, arbre | afficher le nom de l'arbre et le retrouver dans la liste des résultats | texte | non | `Érable` |
| `image` | accueil, arbre | afficher la photo ou l'illustration de l'arbre pour l'identifier visuellement | texte | non | `erable.svg` |
| `typeFeuille` | accueil, critères, options | filtrer les arbres selon qu'ils ont des aiguilles ou des feuilles | texte | non | `Aiguilles` |
| `formeFeuille` | accueil, critères, options | filtrer et afficher la forme de la feuille (simple ou composée) | texte | non | `simple` |
| `dispositionRameau` | accueil, critères, options | filtrer et afficher la disposition des feuilles sur le rameau | texte | non | `opposées` |
| `bordFeuille` | accueil, critères, options | filtrer et afficher le bord de la feuille pour comparer les espèces | texte | non | `lisse` |
| `description` | arbre | afficher les informations détaillées sur l'arbre et ses caractéristiques | texte | non | `Grandes feuilles vertes claires, dessus des feuilles tous doux, arbre de grande taille (environ 20 m), ...` |
| `filtresActifs` | accueil, critères | afficher les critères sélectionnés et filtrer les résultats de manière dynamique | texte | non | `feuille, simple, opposées, denté` |
| `resultatCorrespondant` | accueil | trier et afficher les arbres correspondant aux filtres choisis | vrai/faux | non | `true` |
