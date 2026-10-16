# Installer l'Éditeur PDF comme un logiciel Windows

## 1. Mettre l'outil en ligne (une seule fois)
1. Sur GitHub, créez un dépôt (ex. `editeur-pdf`), public.
2. Déposez-y **tout le contenu de ce dossier** : `index.html`, `manifest.webmanifest`, `sw.js` et le dossier `icons`.
3. Dans le dépôt : **Settings → Pages → Build and deployment → Source : Deploy from a branch → Branch : main / (root) → Save**.
4. Après une minute, l'adresse apparaît : `https://<votre-compte>.github.io/editeur-pdf/`.

## 2. Installer l'application
1. Ouvrez cette adresse dans Chrome.
2. Cliquez sur le bouton **« Installer »** en haut à droite de l'outil (ou sur l'icône d'installation à droite de la barre d'adresse de Chrome).
3. L'Éditeur PDF apparaît dans le menu Démarrer, a son icône dans la barre des tâches et s'ouvre **toujours dans sa propre fenêtre**, même si Chrome est déjà ouvert.

## 3. En faire le programme par défaut pour les PDF
- Clic droit sur n'importe quel PDF → **Ouvrir avec → Choisir une autre application** → **Éditeur PDF** → **Toujours**.
- Ou : **Paramètres Windows → Applications → Applications par défaut**, tapez `.pdf`, choisissez **Éditeur PDF**.

Au premier PDF ouvert ainsi, Chrome demande l'autorisation d'ouvrir ce type de fichier : acceptez (et cochez « Ne plus demander »).
Un double-clic sur un autre PDF l'ouvre dans un nouvel onglet de la même fenêtre. « Enregistrer » écrit directement dans le fichier d'origine.

## 4. Mises à jour
Pour passer à une nouvelle version, remplacez simplement les fichiers dans le dépôt GitHub. L'application installée prend la nouvelle version au lancement suivant (si besoin, fermez-la puis rouvrez-la deux fois).
