# Portfolio académique — Mawounan Jolémon GLODJO

Ce dépôt est basé sur Academic Pages / Jekyll. Il met d’abord en avant les productions : publications, projets, créations numériques, communications, articles et ressources.

## Rubriques du site

- `/publications/` : articles scientifiques et autres publications.
- `/portfolio/` : projets académiques, collaboratifs et personnels.
- `/creations/` : logiciels, scripts, notebooks, outils et prototypes.
- `/talks/` : communications, exposés, posters et présentations.
- `/articles/` : notes techniques, tutoriels et billets.
- `/teaching/` : formations, cours, certifications et ressources pédagogiques.

## Ajouter un contenu

1. Copier le modèle correspondant dans `templates/`.
2. Le placer dans le dossier de collection indiqué dans `templates/README.md`.
3. Remplacer tous les champs provisoires et ne conserver que des informations vérifiables.
4. Ajouter les documents dans `files/` et les illustrations dans `images/`.
5. Faire un commit sur `main` ou `master`. GitHub Actions construit et déploie le site.

Les rubriques vides affichent volontairement un message explicatif au lieu d’exemples fictifs.

## Déploiement GitHub Pages

Dépôt attendu : `Jojosys1/Jojosys1.github.io`

Dans GitHub : **Settings → Pages → Source → GitHub Actions**. Le workflow `.github/workflows/jekyll.yml` construit le site avec Jekyll et publie l’artefact GitHub Pages.
