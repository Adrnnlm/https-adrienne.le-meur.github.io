# Site personnel d’Adrienne Le Meur

Site académique construit avec Jekyll et destiné à GitHub Pages.

## Mise en ligne

1. Déposer tous les fichiers à la racine du dépôt GitHub Pages.
2. Dans **Settings → Pages**, sélectionner **Deploy from a branch**.
3. Choisir la branche `main` et le dossier `/ (root)`.
4. Enregistrer puis attendre la fin du déploiement.

Le site est disponible à l’adresse <https://adrnnlm.github.io/https-adrienne.le-meur.github.io/>. Les fichiers PDF publics peuvent être placés dans `assets/pdf/`, puis liés avec une adresse relative telle que `{{ '/assets/pdf/nom-du-fichier.pdf' | relative_url }}`.
