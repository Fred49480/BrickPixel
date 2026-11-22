# 🧱 BrickPixel

**De la photographie à la mosaïque LEGO !**

BrickPixel est un projet collaboratif de développement informatique réalisé dans le cadre de l'enseignement de **Numérique et Sciences Informatiques (NSI)**.

L'objectif est de développer une application web permettant de transformer une photographie en une mosaïque de type *pixel art*, composée de couleurs issues d'une palette de briques LEGO.

Chaque mosaïque est ensuite découpée en plusieurs carrés indépendants. Pour chacun d'eux, l'application génère un plan de construction et un inventaire des pièces nécessaires.

Le projet associe ainsi algorithmique, programmation web, traitement d'images et travail collaboratif.

---

## 🎯 Objectifs du projet

Développer une application permettant de :

- importer une photographie depuis son ordinateur ;
- choisir les dimensions de l'image finale ;
- convertir la photographie en une image pixel art ;
- remplacer chaque pixel par la couleur LEGO la plus proche dans une palette prédéfinie ;
- visualiser le résultat et son découpage ;
- diviser la mosaïque en carrés de dimensions paramétrables ;
- générer pour chaque carré un plan de construction ;
- calculer automatiquement le nombre de pièces nécessaires pour chaque couleur ;
- exporter et imprimer les fiches individuelles de construction.

À terme, les différentes fiches permettront à plusieurs participants de construire simultanément les différentes parties d'une même mosaïque.

## 🖥️ Fonctionnement envisagé

Le fonctionnement de BrickPixel s'articule autour de quatre grandes étapes.

### 1. Importation et préparation de l'image

L'utilisateur importe une photographie et définit les dimensions de la mosaïque souhaitée.

L'application prépare alors une version redimensionnée de l'image.

### 2. Conversion en pixel art

Chaque pixel est associé à la couleur LEGO disponible la plus proche.

La palette de couleurs constitue une donnée centrale de l'application.

### 3. Découpage de la mosaïque

L'image obtenue est découpée en carrés de dimensions paramétrables.

Chaque carré possède une position dans la mosaïque complète et peut être traité indépendamment.

### 4. Génération des plans de construction

Pour chaque carré, l'application génère :
- une représentation quadrillée du pixel art ;
- une légende des couleurs utilisées ;
- un inventaire des pièces nécessaires ;
- une fiche destinée à être imprimée et distribuée à un participant.

## 🛠️ Technologies utilisées

Le projet repose sur des technologies web standards :

| Technologie | Utilisation |
|---|---|
| HTML5 | Structure de l'application |
| CSS3 | Mise en forme et présentation |
| JavaScript | Algorithmes et interactions |
| Canvas API | Manipulation et affichage des images |
| Git / GitHub | Gestion du code et travail collaboratif |

Aucune installation particulière n'est nécessaire pour utiliser l'application : un navigateur web récent suffit.

## 🚀 Utilisation

### Lancer l'application

1. Cloner le dépôt ou télécharger les fichiers du projet.
2. Ouvrir le fichier `index.html` dans un navigateur web récent.
3. Importer une photographie.
4. Choisir les dimensions de la mosaïque.
5. Sélectionner la taille des carrés.
6. Générer la mosaïque.
7. Sélectionner un carré pour consulter son plan et son inventaire.

L'application fonctionne directement dans le navigateur. Les photographies sont traitées localement et ne sont pas envoyées vers un serveur.

### Hébergement

L'application pourra également être hébergée gratuitement avec GitHub Pages afin d'être accessible depuis n'importe quel appareil connecté à Internet.

## 📂 Organisation du projet

L'organisation initiale du dépôt est volontairement simple :

```text
BrickPixel/
│
├── index.html
│
├── README.md
│
└── LICENSE
```

Au fur et à mesure du développement, le code sera progressivement organisé en plusieurs fichiers afin de séparer les différentes responsabilités :

```text
BrickPixel/
│
├── index.html
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
├── data/
│   └── palette-lego.js
│
├── README.md
└── LICENSE
```

## 👩‍💻 Un projet collaboratif

BrickPixel est développé collectivement par les élèves de NSI.

Le développement est organisé en petites tâches indépendantes, réparties entre différents groupes de travail.

Les objectifs sont notamment de mettre en pratique :
- la conception d'une application informatique ;
- la décomposition d'un problème complexe en sous-problèmes ;
- la programmation modulaire ;
- la manipulation de structures de données ;
- la conception et l'utilisation d'algorithmes ;
- les tests et la validation d'un programme ;
- le travail collaboratif avec Git et GitHub.

Le dépôt évoluera progressivement au fil des contributions des participants.

## 📌 État du projet

**Version actuelle : prototype fonctionnel (0.1)**

Le prototype permet déjà d'importer une photographie, de la convertir en pixel art à l'aide d'une palette de démonstration, de découper l'image en carrés et de générer des inventaires.

Les prochaines étapes porteront notamment sur :
- la constitution d'une palette LEGO documentée ;
- l'amélioration des algorithmes de traitement des images ;
- la séparation du code en modules ;
- la conception définitive des fiches de construction ;
- l'intégration des différentes fonctionnalités ;
- la validation de l'application complète.

Certaines fonctionnalités et données sont encore provisoires.

## 📜 Licence

Ce projet est distribué sous licence MIT.

La licence autorise notamment l'utilisation, la modification et la redistribution du code, sous réserve de conserver les mentions de copyright et de licence.

Voir le fichier [LICENSE](LICENSE).

---

**BrickPixel — Un projet de NSI où le code prend forme, pixel après pixel !**
