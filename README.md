# Mohamed Ben Attia — Portfolio

Portfolio statique en français, conçu pour GitHub Pages et adapté aux mobiles.

## Projets

1. Supervision des chambres froides — PFE à l’hôtel Royal Garden Palace, Djerba.
2. Med Assistant — assistant de rappel et de distribution de médicaments.
3. AutoHarness AI — assistant de formation au câblage automobile.
4. Robot UR5 — simulation de pick and place dans CoppeliaSim.
5. Sous-marin — commande à distance depuis LabVIEW via TCP/IP.

Les présentations reposent sur les rapports, les fichiers et les informations fournis par Mohamed Ben Attia. Les visuels sont typographiques ; les captures des rapports ne sont pas publiées. Le site ne publie pas les rapports complets, les configurations privées ni les données d’utilisateurs.

## Structure

- `index.html` : contenu et structure du site.
- `style.css` : mise en page responsive.
- `app.js` : fiches des projets, filtres et fenêtres de détail.

## Aperçu local

Exécuter `python -m http.server 8000` à la racine, puis ouvrir http://localhost:8000.

## GitHub Pages

Dans Settings → Pages, choisir **Deploy from a branch**, puis **main** et **/(root)**. L’adresse prévue est https://Mohamed01880.github.io/.

## Modifier les projets

Le tableau `projects` dans `app.js` contient les descriptions, technologies et réalisations. Le site n’utilise aucune dépendance externe et ne nécessite aucune compilation.
