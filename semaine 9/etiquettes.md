# Mes étiquettes

Projet : Bookmatch

Une ligne par étiquette. Chaque étiquette, sauf `id`, doit servir à afficher, filtrer ou trier sur au moins un écran de votre brief (méthode en 6 questions, exercice 3).

| Étiquette | Écran du brief qui l'affiche | Sert à (afficher, filtrer, trier) | Sorte de valeur (texte, nombre, vrai/faux) | Unique ? | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | aucun | distinguer les fiches | nombre | oui | 1 |
| `titre` | Résultats, Fiche livre | afficher | texte | non | "Les Heures salées" |
| `auteur` | Résultats, Fiche livre | afficher | texte | non | "Anouk Verlaine" |
| `genre` | Fiche livre | afficher, filtrer | texte | non | "roman", "policier", "romance", "science-fiction", "fantasy" |
| `nbPages` | Fiche livre | afficher, filtrer (longueur), trier | nombre | non | 248 |
| `ambiance` | Fiche livre | afficher, filtrer | texte | non | "mélancolique", "haletant", "feel-good", "mystérieux", "réconfortant" |
| `public` | Fiche livre | afficher, filtrer | texte | non | "ado", "jeune adulte", "adulte" |
| `resume` | Fiche livre | afficher | texte | non | "Une gardienne de phare…" |
| `dejaLu` | Fiche livre (icône livre) | afficher, filtrer (exclure les livres déjà lus) | vrai/faux | non | false |
