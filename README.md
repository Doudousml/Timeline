Timeline Aubervilliers - EXIF Reader

Une application web interactive et élégante permettant de visualiser une série de photographies sous forme de frise chronologique dynamique. Le projet extrait automatiquement les métadonnées EXIF (Date, Heure, Auteur, Appareil) pour organiser et documenter les images.

✨ Fonctionnalités
- **Extraction EXIF Automatique :** Utilise la bibliothèque exif-js pour lire les données cachées des fichiers JPEG (Heure de prise de vue, Artiste, Lieu, Modèle d'appareil).

- **Tri Chronologique :** Les photos sont automatiquement triées par heure, de la plus ancienne à la plus récente, peu importe l'ordre d'importation.
- **Interface Immersive :** Design sombre (Dark Mode) avec des animations fluides en CSS (Bézier cubique).
- **Focus Dynamique :** Au clic ou au survol, l'image sélectionnée s'agrandit pour révéler les détails techniques.
- **Navigation Intuitive** : Supporte le Glisser-Déposer (Drag & Drop) et la sélection classique de fichiers.
- **Responsive & Accessible** : Conteneur à défilement horizontal optimisé et gestion de la navigation au clavier.
- **Bouton Supprimer** : Une fois une image sélectionnée (agrandie), un bouton rouge "SUPPRIMER" apparaît en haut à droite de celle-ci pour la retirer de la timeline.
- **Corbeille interactive** : Vous pouvez glisser une image (Drag & Drop) directement vers l'icône de la corbeille située en bas de la page pour l'effacer.

🛠️ Technologies utilisées
- HTML5 / CSS3 : Structure et mise en page (Flexbox, CSS Variables).
- JavaScript (ES6+) : Logique de traitement des fichiers, tri et rendu dynamique.
- EXIF.js : Bibliothèque externe pour la lecture des métadonnées d'images.
- Inter Font Family : Pour une typographie moderne et lisible.


 Installation et Utilisation
 Comme il s'agit d'une application côté client (client-side), aucune installation de serveur n'est requise.
 1. Téléchargez le fichier index.html.
 2. Ouvrez le fichier dans un navigateur web moderne (Firefox est recommandé pour une meilleure gestion des fichiers locaux).
 3. Ajoutez vos photos :
 - Glissez vos images directement sur la zone en pointillés.
 - OU Cliquez sur le bouton "+ GLISSER OU SÉLECTIONNER DES PHOTOS" pour choisir vos fichiers.
