Hub Chantier v4.3.3 — Portail client + acceptation automatique EmailJS

Fichiers à publier à la racine GitHub Pages :
- index.html
- portail.html
- manifest.webmanifest
- sw.js
- icons/

Nouveau en v4.3.3 :
- EmailJS configurable dans Mes tarifs
- Le portail client envoie l’acceptation automatiquement si EmailJS est configuré
- Fallback mailto si EmailJS est absent ou échoue

Configuration EmailJS :
1. Créer un compte EmailJS
2. Créer un Email Service
3. Créer un Email Template avec les variables souhaitées, par exemple :
   {{to_email}}, {{quote_no}}, {{quote_title}}, {{client_name}}, {{accepted_by}}, {{accepted_contact}}, {{accepted_at}}, {{total}}, {{deposit}}, {{balance}}, {{acceptance_text}}, {{portal_url}}
4. Dans Hub Chantier > Mes tarifs, remplir :
   - Courriel acceptations
   - EmailJS Public Key
   - EmailJS Service ID
   - EmailJS Template ID

Test :
https://TON_USER.github.io/TON_REPO/?v=42


Nouveau en v4.3.3 : correctif du bouton Modifier/Supprimer des items, même pour les anciens items sauvegardés sans identifiant interne.
