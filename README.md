# Portfolio académique — Mawounan Jolémon GLODJO

Ce dépôt contient un site personnel construit avec le template **Academic Pages** (Jekyll / GitHub Pages).

## Contenu du site

- Accueil et présentation
- Axes d’intérêt
- Projets : KyFax et GREENCOIN
- Curriculum vitæ
- Coordonnées de contact

Le thème Academic Pages, ses layouts, composants, styles, scripts et outils de génération sont conservés.

## Déploiement sur GitHub Pages

1. Créer un **nouveau dépôt public** nommé exactement `Jojosys1.github.io` sous le compte GitHub `Jojosys1`.
2. Extraire le contenu de cette archive sur l’ordinateur.
3. Envoyer **tout le contenu situé à la racine de l’archive** dans la racine du nouveau dépôt (ne pas envoyer le fichier ZIP et ne pas créer un sous-dossier `Jojosys1.github.io-master`).
4. Vérifier que `_config.yml`, `_pages/`, `_portfolio/` et `.github/` se trouvent directement à la racine du dépôt.
5. Faire un commit sur la branche `main` ou `master`.
6. Dans GitHub : **Settings → Pages → Build and deployment → Source → GitHub Actions**.
7. Ouvrir l’onglet **Actions** et vérifier que le workflow « Build and deploy Jolémon's Academic Pages site » se termine avec succès.
8. Le site sera publié à l’adresse `https://jojosys1.github.io`.

Le workflow est configuré pour se déclencher sur `main` et `master`. Il construit le site avec Jekyll puis le publie via GitHub Pages.

## Mise à jour du contenu

- Page d’accueil : `_pages/about.md` (elle génère `/`).
- Présentation : `_pages/about-me.md`.
- Axes d’intérêt : `_pages/research.md`.
- CV en ligne : `_pages/cv.md`.
- Ajouter un projet : créer un fichier Markdown dans `_portfolio/`.
- Menu : `_data/navigation.yml`.
- Profil latéral : `_config.yml`.
- Photo : remplacer `images/profile.png` par une photo carrée, en conservant ce nom.
- Documents : placer les PDF dans `files/`.

## Important

Les anciennes entrées de démonstration du template (publications, conférences, cours et articles fictifs) ont été retirées pour éviter d’afficher des éléments qui ne correspondent pas au parcours réel. Les rubriques natives et les mécanismes du thème restent disponibles pour ajouter ces contenus ultérieurement.

Les fiches KyFax et GREENCOIN ne décrivent que les informations présentes dans le CV. Les détails techniques, résultats et liens de code sont à compléter à partir des réalisations réelles.

Le PDF original du CV ne figurait pas dans le ZIP du dépôt reçu : il devra être ajouté dans `files/` si tu souhaites proposer son téléchargement depuis le site.
