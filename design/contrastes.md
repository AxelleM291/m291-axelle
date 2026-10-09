# Contrastes

Ratios calculés avec la formule WCAG 2.x (identique au [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)), à partir des couleurs des fichiers [maquettes/style/](maquettes/style/).

Seuils AA : texte **4,5:1** · grand texte (≥ 24 px ou ≥ 18,66 px gras) **3:1** · bordures, focus, icônes **3:1**.

## Audacieuse (retenue)

| Élément | Couleurs | Ratio | Résultat |
|---|---|---|---|
| Texte courant | `#0F1115` / `#FFFFFF` | 18,90:1 | ✅ |
| Texte secondaire | `#3A3F47` / `#FFFFFF` | 10,60:1 | ✅ |
| Texte sur fond gris clair | `#3A3F47` / `#F2F3F5` | 9,54:1 | ✅ |
| **Bouton principal** | `#0F1115` / `#C6F432` | **14,75:1** | ✅ |
| Footer | `#D5D8DD` / `#0F1115` | 13,22:1 | ✅ |
| Focus (contour 3 px) | `#0F1115` / `#FFFFFF` | 18,90:1 | ✅ |
| **Bordure des options** | `#D5D8DD` / `#FFFFFF` | **1,43:1** | ❌ |

## Sobre

| Élément | Couleurs | Ratio | Résultat |
|---|---|---|---|
| Texte courant | `#252521` / `#F7F5EE` | 14,10:1 | ✅ |
| Titres, liens | `#254D32` / `#F7F5EE` | 8,81:1 | ✅ |
| Bouton principal | `#FFFFFF` / `#254D32` | 9,61:1 | ✅ |
| **Focus** | `#A8BFA3` / `#F7F5EE` | **1,81:1** | ❌ |
| Bordures des options | `#A8BFA3` / `#FFFFFF` | 1,97:1 | ❌ |

## Chaleureuse

| Élément | Couleurs | Ratio | Résultat |
|---|---|---|---|
| Texte courant | `#3B3028` / `#F2E8D5` | 10,54:1 | ✅ |
| Titres, liens | `#526B45` / `#F2E8D5` | 4,87:1 | ✅ |
| **Bouton principal** (16 px gras) | `#FFFCF5` / `#B86645` | **4,08:1** | ❌ |
| **Focus** | `#D6A84F` / `#F2E8D5` | **1,80:1** | ❌ |
| Bordures des options | `#E4D5BA` / `#FBF5E9` | 1,33:1 | ❌ |

## Bilan et itération

L'audacieuse est la seule maquette dont le bouton principal **et** le focus sont conformes. Il lui reste un seul défaut à corriger :

| | Avant | Après |
|---|---|---|
| Bordure des options | `#D5D8DD` — 1,43:1 ❌ | `#8A8F96` — 3,26:1 ✅ |

Après l'observation, l'accent `#C6F432` a été remplacé par `#A9D18E` ([iteration.md](iteration.md)) : le bouton principal passe de 14,75:1 à **10,98:1**, toujours conforme.

Correctifs si on reprenait les autres pistes : focus de la sobre → `#6E8A67` (3,50:1) · bouton de la chaleureuse → `#9C5236` (5,58:1) · focus de la chaleureuse → `#8B6A2B` (4,12:1).
