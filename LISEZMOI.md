# Site du certificat Persona 2.0

Deux fichiers suffisent :
- `index.html` : la page que les participants ouvrent en scannant le QR code.
- `qr.html` : une page utilitaire qui affiche le QR code de l'adresse du site (pour la slide).

## Avant de mettre en ligne (2 min)

Ouvrez `index.html` dans un éditeur de texte, cherchez `dateAtelier` (vers la ligne 120) et remplacez `Octobre 2026` par la date de l'atelier, par exemple `15 octobre 2026`.

## Mettre en ligne sur Vercel, sans ligne de commande (10 min)

1. Sur github.com, créez un nouveau dépôt (bouton « New »), par exemple `certificat-persona20`. Cochez « Add a README file ».
2. Dans le dépôt, cliquez sur « Add file » puis « Upload files », glissez `index.html` et `qr.html`, puis « Commit changes ».
3. Sur vercel.com, cliquez sur « Add New » puis « Project », importez le dépôt `certificat-persona20`.
4. Laissez tous les réglages par défaut (Framework Preset : « Other ») et cliquez sur « Deploy ».
5. Vercel vous donne une adresse, par exemple `https://certificat-persona20.vercel.app`.

Pour modifier le site plus tard, il suffit de remplacer le fichier dans GitHub : Vercel republie automatiquement.

## Récupérer le QR code

Ouvrez `https://<votre-adresse>.vercel.app/qr.html` : le QR code de votre site s'affiche. Faites une capture d'écran, ou envoyez simplement l'adresse pour qu'elle soit intégrée à la slide 22.

## Tester avant l'atelier

- Scannez le QR code avec un iPhone et un Android, générez un certificat avec et sans photo.
- Appuyez sur « Partager sur LinkedIn » : choisissez LinkedIn dans le menu, collez le texte, vérifiez que l'image est bien jointe. Publiez un post de test, puis supprimez-le.
- Sur ordinateur : le bouton télécharge le certificat, copie le texte et ouvre LinkedIn.

## Bon à savoir

- Rien n'est envoyé à un serveur : le certificat est dessiné sur le téléphone du participant.
- LinkedIn ne permet pas de préremplir un post avec une image depuis un site. Le texte est donc copié automatiquement et le participant le colle dans LinkedIn. Les mentions de Jules et Thibaut s'ajoutent en tapant @ devant leur nom (le rappel est affiché sur la page).
