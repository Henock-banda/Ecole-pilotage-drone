# École de pilotage drone

Application web d’apprentissage du pilotage de drones : drone gris vu de dos au-dessus de l’herbe, télécommande à écran avec vue caméra (mode 1 et mode 2), 8 leçons, mode Pratique au doigt, boutons Décoller / Atterrir / Maison / Photo. Aucun serveur ni dépendance : c’est une page web simple, installable sur téléphone et utilisable hors ligne.

## Mettre l’application en ligne avec GitHub

1. Créez un compte sur github.com, puis un nouveau dépôt public (par exemple `ecole-pilotage-drone`).
2. Cliquez sur **Add file > Upload files**, déposez tous les fichiers de ce dossier (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`), puis **Commit changes**.
3. Ouvrez **Settings > Pages**. Dans **Source**, choisissez **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après une à deux minutes, l’application est disponible à l’adresse `https://VOTRE-NOM.github.io/ecole-pilotage-drone/`.

## Niveaux et missions

L’application propose des leçons guidées, puis 9 missions avec obstacles (maisons, arbres, plantes) réparties en 3 niveaux : Débutant, Intermédiaire et Professionnel. Réussir les missions d’un niveau débloque le suivant. La progression est enregistrée sur l’appareil.

## Images

Les images du drone, de la télécommande et de l’herbe sont intégrées dans `index.html`. Pour remplacer les maisons, arbres et plantes dessinés par vos propres photos, ajoutez un dossier `images/` avec trois PNG à fond transparent : `maison.png`, `arbre.png` et `plante.png`. Ils sont utilisés automatiquement.

## Installer sur téléphone

Ouvrez l’adresse dans Chrome (Android) ou Safari (iPhone), puis menu **Ajouter à l’écran d’accueil** (ou **Installer l’application**). Après une première ouverture avec internet, elle fonctionne hors ligne.

## Utiliser en local

Ouvrez simplement `index.html` dans un navigateur. L’installation hors ligne (`sw.js`) ne fonctionne qu’à partir d’une adresse https, comme GitHub Pages.

## Sécurité

Entraînez-vous toujours en extérieur dégagé, loin des personnes, en gardant le drone en vue, et respectez la réglementation de votre pays.
