# Création d'un fichier de Documentation via Terminal VSCode (repo créé au prealable sur github web)

| Étape                     | Commande                                             | Description |
|---------------------------|------------------------------------------------------|-------------|
| **Ouvrir le dépôt local** | `cd chemin_vers_votre_dossier/fichier`                         | Naviguez vers votre dépôt local. |
| **Créer un dossier**      | `mkdir docs`  `cd docs`                            | Crée un dossier `docs` et y navigue. |
| **Ajouter des fichiers**  | `touch README.md`                                    | Crée un fichier `README.md` dans le dossier `docs`. |
| **Éditer le fichier**     | Ouvrez `README.md` dans VSCode et écrivez votre documentation. | Ajoutez du contenu à votre documentation. |
| **Ajouter au dépôt Git**  | `git add .`                                          | Ajoute tous les nouveaux fichiers au dépôt. |
| **Commit**                | `git commit -m "Ajout de la documentation"`          | Enregistre les modifications dans l'historique Git. |
| **Push**                  | `git push origin main`                               | Publie vos changements sur le dépôt GitHub. |
