Hub Chantier v4.6.6

Dépose les fichiers à la racine GitHub Pages : index.html, portail.html, manifest.webmanifest, sw.js, icons/.
Test : ?v=466

Notes : pour recevoir les acceptations automatiquement, configure le courriel acceptations et/ou EmailJS dans Mes tarifs. Le courriel reçu contient un lien Hub permettant de marquer la soumission acceptée dans ton app locale.


V4.7 — Acceptation automatique réelle
-------------------------------------
Pour que le client clique Accepter/Refuser et que le Hub le voie, il faut configurer Supabase dans Mes tarifs > Portail client / sync.
EmailJS sert seulement à envoyer une notification courriel automatique; Supabase sert à enregistrer la décision pour que le Hub puisse la synchroniser.
Table recommandée: quote_acceptances avec colonnes quote_id, quote_no, status, client_name, client_contact, client_phone, client_email, company_name, quote_title, total, created_at, user_agent.
