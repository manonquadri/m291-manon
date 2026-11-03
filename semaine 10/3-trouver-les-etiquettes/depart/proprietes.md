# Les étiquettes de la location d'instruments

Une ligne par étiquette. La colonne « Sert à » répond aux questions 2, 3 et 4 de la méthode : afficher, filtrer, trier. Une étiquette qui ne sert à rien de tout cela n'entre pas dans le fichier, sauf `id`.

| Étiquette | Écran | Sert à (afficher, filtrer, trier) | Sorte de valeur | Unique ? | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | — | aucun (sert à distinguer les fiches) | nombre | oui | 1 |
| `nom` | Liste | afficher | texte | non | "Violon 3/4" |
| `famille` | Liste | afficher, filtrer | texte | non | "cordes", "vents", "percussions" |
| `prixMois` | Liste | afficher, trier | nombre | non | 25 |
| `taille` | Détail | afficher | texte | non | "enfant", "adulte" |
| `description` | Détail | afficher | texte | non | "Avec étui et archet." |
| `disponible` | — | filtrer | vrai/faux | non | true |

Pourquoi le nom de l'instrument ne suffit pas à distinguer les fiches (une phrase) :
Il y a deux fiches « Violon 3/4 » (l'une disponible, l'autre déjà louée) : avec le nom seul, la page ne peut pas savoir laquelle ouvrir dans l'écran Détail, alors que leurs `id` (1 et 2) sont différents.

Suggestion de l'IA que j'ai refusée, et pourquoi :
L'IA proposait une étiquette `etui` (vrai/faux). Je l'ai refusée parce que le brief ne l'affiche dans aucun écran et ne prévoit ni filtre ni tri dessus, donc elle ne répond à aucune des questions 2, 3 ou 4 (l'info est déjà dans la `description`).