# BrickPixel 🧱

**Transformer une photographie en mosaïque LEGO, pixel après pixel !**

BrickPixel est un projet collaboratif réalisé dans le cadre de l'enseignement de **Numérique et Sciences Informatiques (NSI)** en classe de première.

L'objectif est de développer une application web permettant de transformer une photographie en une mosaïque de briques LEGO. L'image est pixelisée à partir d'une palette de couleurs, puis découpée en tuiles indépendantes. Chaque tuile peut ensuite être construite séparément à l'aide d'un plan de montage et d'un inventaire des pièces nécessaires.

## 🎯 Objectifs du projet

BrickPixel est à la fois un projet informatique et un projet de construction collective.

Il permet notamment de travailler sur :
- La programmation en JavaScript ;
- La manipulation et le traitement d'images numériques ;
- Les structures de données ;
- Les algorithmes de comparaison et de traitement des couleurs ;
- La conception d'une interface web avec HTML et CSS ;
- Le travail collaboratif et la gestion d'un projet informatique avec Git et GitHub.

À terme, chaque élève pourra prendre en charge la construction d'une ou plusieurs tuiles. L'assemblage de toutes les réalisations permettra de reconstituer l'image initiale sous la forme d'une grande mosaïque.

## ⚙️ Fonctionnement

L'application doit permettre de suivre plusieurs étapes.

### 1. Importation d'une image

L'utilisateur importe une photographie depuis son ordinateur.

### 2. Pixelisation

L'image est redimensionnée selon les dimensions choisies par l'utilisateur, puis transformée en pixel art.

Chaque pixel est associé à la couleur LEGO la plus proche parmi celles disponibles dans la palette retenue.

### 3. Découpage en tuiles

L'image pixelisée est découpée en plusieurs tuiles de dimensions définies par l'utilisateur.

Chaque tuile constitue une partie autonome de la mosaïque et possède ses propres coordonnées dans l'image globale.

### 4. Génération des plans et des inventaires

Pour chaque tuile, l'application doit générer :
- Un plan de construction indiquant la position et la couleur de chaque pièce ;
- Un inventaire détaillé des briques nécessaires, regroupées par couleur ;
- Une fiche de construction pouvant être imprimée.

L'objectif final est de permettre à chaque participant de construire sa tuile indépendamment des autres.

## 🛠️ Technologies utilisées

Le projet repose sur des technologies web standards :

- **HTML5** : structure de l'application ;
- **CSS3** : mise en forme et présentation ;
- **JavaScript** : traitement des images, algorithmes et interactions ;
- **Canvas** : manipulation et affichage des images ;
- **Git et GitHub** : gestion du code source et travail collaboratif.

Aucune installation particulière n'est nécessaire pour utiliser le prototype.

## 🚀 Utilisation

### Lancer l'application

1. Télécharger le dépôt ou le cloner avec Git.
2. Ouvrir le fichier `index.html` dans un navigateur web récent.
3. Importer une photographie et commencer à utiliser les fonctionnalités disponibles.

Le traitement des images est effectué directement dans le navigateur : aucune photographie n'est envoyée vers un serveur.

### Accéder à l'application en ligne

Une version hébergée pourra être proposée grâce à **GitHub Pages**.

## 📁 Organisation du projet

Le prototype initial regroupe volontairement le HTML, le CSS et le JavaScript dans un unique fichier `index.html`, afin de faciliter sa prise en main.

À mesure que le projet se développera, le code pourra être organisé en plusieurs fichiers et dossiers :

```text
BrickPixel/
│
├── index.html
├── README.md
├── LICENSE
│
├── css/
│   └── style.css
│
├── js/
│   ├── main.js
│   ├── interface.js
│   ├── image.js
│   ├── couleurs.js
│   ├── pixelisation.js
│   ├── decoupage.js
│   ├── inventaire.js
│   └── exportation.js
│
└── data/
    └── palette-lego.js
```

Cette organisation permettra de répartir le développement entre plusieurs groupes, chacun pouvant travailler sur une fonctionnalité bien identifiée.

## 🤝 Un projet collaboratif

BrickPixel est développé collectivement par les élèves de NSI.

Chaque participant contribue à une partie du projet : conception de l'interface, traitement des images, gestion des couleurs, découpage en tuiles, génération des inventaires ou encore tests.

Le dépôt GitHub permet de centraliser le travail, de suivre les évolutions du code et de faciliter l'intégration des différentes contributions.

## 📌 État du projet

Le projet est actuellement au stade du prototype fonctionnel.

Les principales fonctionnalités déjà présentes sont :
- L'importation d'une photographie ;
- Le redimensionnement de l'image ;
- La conversion en pixel art ;
- L'association des pixels à une palette de couleurs ;
- Le découpage de l'image en tuiles ;
- La sélection et la visualisation d'une tuile ;
- L'affichage d'un inventaire des pièces ;
- L'impression des fiches de construction.

La palette de couleurs actuellement utilisée est illustrative. Les références et la disponibilité des pièces devront être vérifiées avant toute réalisation physique.

De nombreuses améliorations restent possibles, tant sur le plan informatique que sur celui de l'expérience utilisateur.

## 📄 Licence

Ce projet est distribué sous licence MIT. Voir le fichier `LICENSE` pour plus d'informations.

Les photographies, ressources graphiques et données externes éventuellement utilisées dans le projet restent soumises à leurs propres conditions d'utilisation.

BrickPixel est un projet pédagogique indépendant, sans affiliation avec le groupe LEGO.

---

**BrickPixel — Un projet de NSI où le code prend forme, tuile après tuile !**
