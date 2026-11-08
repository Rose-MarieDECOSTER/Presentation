# Portfolio de Rose-Marie De Coster — V1

Site statique personnel, hébergé sur GitHub Pages. Aucun framework, aucune installation nécessaire pour modifier les textes sur Chromebook.

- Site : https://rose-mariedecoster.github.io/Presentation/
- Branche : `main`, publication depuis la racine `/`.
- Point de reprise : [docs/CONTEXTE_ET_REPRISE.md](docs/CONTEXTE_ET_REPRISE.md).
- Texte du CV utilisé : [docs/CV_SOURCE.md](docs/CV_SOURCE.md), téléphone retiré.

## Modifier le site depuis GitHub

1. Ouvrir le fichier concerné, puis le bouton crayon.
2. Modifier le texte entre les balises HTML, sans enlever les balises.
3. Enregistrer avec « Commit changes » sur `main`.
4. Attendre le déploiement GitHub Pages dans l’onglet Actions.

## Organisation

- `index.html` : accueil à défiler, compétences, réalisations, formations, distinction, intérêts.
- `parcours.html` : expériences détaillées.
- `parcours-professionnels.html`, `pse.html`, `nccm.html` : projets.
- `distinction.html` : publications liées au prix André Lebrun.
- `memoire.html` : espace réservé aux futurs extraits.
- `assets/style.css` : palette, mise en page responsive, animations et réduction des mouvements.
- `assets/site.js` : menu mobile accessible, sans dépendance.
- `assets/CV_Rose_Marie_De_Coster.pdf` : téléchargement public, sans téléphone, mise en page de lecture distincte de l’original Word.
- `.nojekyll` : publication directe du HTML.

Aucun cookie, outil de mesure d’audience, police distante, formulaire ou service tiers embarqué. Les liens externes s’ouvrent dans un nouvel onglet.

## Aperçu local facultatif

Depuis le dossier : `python3 -m http.server 8000`, puis ouvrir `http://localhost:8000`.

## GitHub Pages

Dans Settings > Pages : « Deploy from a branch », branche `main`, dossier `/ (root)`. Si GitHub Pages est déjà configuré ainsi, chaque commit publie le site. L’URL est sensible au nom du dépôt : `/Presentation/`.

## Reprendre avec un assistant

> Reprends le portfolio dans Rose-MarieDECOSTER/Presentation. Lis d’abord README.md et docs/CONTEXTE_ET_REPRISE.md, puis inspecte les fichiers actuels. Respecte les décisions validées et demande les contenus manquants sans les inventer.
