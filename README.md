
# Mon Projet - [FocusFlow]

## Contexte
Projet de présentation web réalisé en 2 jours (semaine 2).
Objectif : présenter mon idée de projet avec HTML/CSS.

## Comment ouvrir la page

1. Aller dans le dossier du projet
2. Ouvrir le fichier `index.html` dans un navigateur

### Avant (jeudi)
- CSS ne chargeait pas (page blanche avec texte brut)

### Après (vendredi)
- CSS chargé : page avec mise en forme
- Images affichées correctement
- Contenu personnalisé pour mon projet

## Bugs corrigés

1. **Bug** : Le CSS ne se chargeait pas
   - **Cause** : Mauvais chemin dans index.html
   - **Fix** : Changé `href="css/styles.css"` en `href="styles.css"`
   - **Commit** : `fix: load stylesheet`

2. **Bug** : Images ne s'affichaient pas
   - **Cause** : Chemin incorrect
   - **Fix** : Corrigé les chemins vers `assets/`
   - **Commit** : `fix: correct image paths`