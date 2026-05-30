Hub Finition — version PWA installable iPhone

Contenu du dossier :
- index.html : ton app Hub Finition avec les balises PWA/iOS ajoutées.
- manifest.webmanifest : informations d'installation de l'app.
- sw.js : service worker pour le mode hors-ligne.
- icons/ : icônes nécessaires pour iOS/Android.

Important :
Une PWA ne s'installe pas correctement depuis un simple fichier ouvert dans l'app Fichiers de l'iPhone.
Elle doit être hébergée sur une adresse web HTTPS, par exemple GitHub Pages, Netlify, Vercel ou un petit hébergement web.

Installation sur iPhone après hébergement :
1. Ouvre l'adresse de l'app dans Safari.
2. Appuie sur Partager.
3. Choisis « Ajouter à l'écran d'accueil ».
4. L'app apparaîtra comme une vraie icône iOS.

Hors-ligne :
Après une première ouverture réussie depuis Safari, l'app est mise en cache et peut fonctionner hors-ligne.
Les données de l'app demeurent locales sur l'appareil, comme dans la version originale.

Note :
Pour synchroniser réellement avec OneDrive/Excel ou Meta Business Suite, il faudra une étape séparée avec API/serveur ou automatisation.
