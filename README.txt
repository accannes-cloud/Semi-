SITE — SEMI DE CANNES
=====================

PAGES
-----
- index.html ............ Accueil (hero, courses, carte + profil, infos, partenaires)
- la-course.html ........ Les épreuves, règlement, palmarès, primes, résultats
- inscriptions.html ..... Tarifs, comment s'inscrire, conditions
- carte.html ............ Carte interactive : village, parcours, ravitos, hôtels
- infos-pratiques.html .. Accès, parking, hôtels, dossards, programme, FAQ
- partenaires.html ...... Partenaires + devenir partenaire
- benevoles.html ........ Devenir bénévole (missions, avantages)
- contact.html .......... Coordonnées + formulaire
- styles.css ............ Feuille de style COMMUNE à toutes les pages
- gpx/ .................. Les 3 traces officielles (5 / 10 / 21 km)

IMPORTANT
---------
Toutes les pages partagent styles.css : gardez TOUS les fichiers dans le
MÊME dossier. Le design se modifie à un seul endroit (styles.css).
Remarque : ouvert tout seul hors du dossier, une page peut apparaître sans
style — c'est normal, il suffit que styles.css soit à côté (ou en ligne).

MISE EN LIGNE
-------------
Déposez tout le dossier chez votre hébergeur (ou Netlify / Vercel / GitHub
Pages). La carte interactive s'affiche une fois en ligne.

À PERSONNALISER (cherchez ces repères dans le code)
---------------------------------------------------
- Date de l'édition ....... EDITION_DATE (index.html)
- Ravitaillements ......... const RAVITOS (index.html) : indiquez les km
- Tracés du parcours ...... const ROUTES (index.html, extraits des GPX)
- Tarifs / primes / palmarès ... pages la-course.html et inscriptions.html
- Newsletter & formulaires ..... à brancher (Brevo, Formspree, etc.)
- Encadrés "à compléter / à confirmer" : remplacez le texte par vos infos.

COULEURS DE MARQUE :  Corail #F37252  |  Bleu ciel #8BC9E1
