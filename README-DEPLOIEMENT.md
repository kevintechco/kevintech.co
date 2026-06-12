# 🚀 Déploiement v3 FLAT — la méthode qui marche avec ton upload

## Pourquoi cette version
Fichiers 100 % PLATS : zéro dossier à uploader. Tes 7 URLs villes historiques
(reparation-iphone-creil.html, etc.) sont maintenant DIRECTEMENT les nouvelles pages.

## Étape 1 — Fermer la Pull Request en attente
Onglet **Pull requests** → ouvrir la PR → bouton **Close pull request** (NE PAS merger).

## Étape 2 — Uploader (tout est plat, multi-sélection OK même mobile)
Add file → Upload files → sélectionner TOUS les fichiers du ZIP (51 html + sitemap + robots + .nojekyll)
→ en bas : **« Commit directly to the main branch »** → Commit changes.
Les fichiers existants (index.html, les 36 reparation-iphone-*.html) sont écrasés : c'est voulu.

## Étape 3 — Ménage (supprimer les fichiers morts)
Sur GitHub, ouvrir chaque fichier → icône corbeille → Commit :
- index (2).html, index (3).html, index (4).html, index (5).html, index (6).html,
  index (7).html, index (9).html, index (11).html, index (13).html, index (15).html,
  index (17).html, index (19).html, index (21).html
- index[1].html
- .nojekyll[1].nojekyll

## Étape 4 — Vérifier (2 min après le commit)
- /kevintech.co/                       → nouvelle home bleue
- /kevintech.co/reparation-ecran-iphone.html → page écran
- /kevintech.co/reparation-iphone-creil.html → NOUVELLE page Creil (plus l'ancienne)
- /kevintech.co/reparation-iphone-rhuis.html → redirige vers Pont-Sainte-Maxence

## Étape 5 — GSC
Sitemaps → renvoyer sitemap.xml. C'est tout.
