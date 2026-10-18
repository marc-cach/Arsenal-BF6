# Arsenal BF6

Les armes de Battlefield 6 saison 5 classées par classe, avec les builds d'accessoires conseillés.

## Installer sur Android
Télécharge `Arsenal-BF6.apk` dans la section **Releases** du dépôt, ouvre-le sur le téléphone et autorise l'installation depuis cette source.

## Installer sur iPhone
Ouvre le site GitHub Pages du dépôt dans **Safari**, touche **Partager** puis **Sur l'écran d'accueil**. L'appli s'ouvre en plein écran et marche hors ligne.

## Mettre à jour les armes (patch, nouvelles armes)
Les armes et les builds sont dans `www/data.json`. Pour publier une mise à jour :
1. modifie les armes ou builds dans `www/data.json` ;
2. augmente `version` (ex. `2026-11-10.1`), mets à jour `label`, `date` et `notes` ;
3. pousse sur `main`.

Dans l'appli, le bouton **Mise à jour** (flèche en haut à droite) devient vert dès qu'une nouvelle version existe. Un toucher l'installe, sans réinstaller l'APK.

## Modifier l'appli elle-même
Modifie `www/index.html` et pousse sur `main` : l'APK et le site sont reconstruits automatiquement.
