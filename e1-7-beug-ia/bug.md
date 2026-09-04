# e1-7 Erreur IA
## Bug du compteur 
Le chiffre est sensé s'incrémenter de 1 à chaque fois mais il affiche toujours 0, bien que la console indique bien que la valeur a été changée.
L'affichage ne se met donc pas à jour.

## Correction
Ajouter : document.getElementById("affiche").textContent = n; dans la fonction JS