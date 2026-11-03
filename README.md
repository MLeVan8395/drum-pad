# Drum pad pédagogique

Un drum pad et une petite boîte à rythmes en ligne, libres et gratuits, pour **comprendre la batterie électronique** : comment on fabrique chaque son, et comment on construit un rythme.

Il a été conçu pour les cours de musiques actuelles et jazz (FM, MAO, cours de batterie ou d'instrument), mais il sert à tout élève ou enseignant curieux.

👉 **Utiliser le drum pad :** https://mlevan8395.github.io/drum-pad/

## Installer l'appli sur un téléphone ou un ordinateur

Le drum pad s'installe comme une application, gratuitement et sans passer par une boutique :

- **Android** (Chrome) : ouvre le site, puis touche le bouton **Installer l'appli** en haut de la page, ou menu ⋮ → **Installer l'application**.
- **iPhone / iPad** (Safari) : bouton Partager → **Sur l'écran d'accueil**. Attention : sur iPhone, désactive le mode silencieux, sinon on n'entend rien.
- **Ordinateur** (Chrome, Edge) : icône d'installation dans la barre d'adresse.

Il fonctionne ensuite **hors ligne** et se met à jour tout seul à chaque ouverture avec une connexion.

## Ce qu'on y trouve

| Partie | Ce qu'on fait | Ce qu'on apprend |
|---|---|---|
| **10 grands pads** | Grosse caisse, caisse claire, cercle, clap, charley fermé et ouvert, tom aigu, tom basse, crash, cloche. Au doigt ou au clavier (A Z E R T / Q S D F G) | Le rôle de chaque élément de la batterie |
| **Séquenceur** (volet à ouvrir) | Une mesure en doubles croches, comptée « 1 ti ke ta, 2 ti ke ta… ». Notes et accents, tempo, swing, métronome, enregistrement en direct depuis les pads | Temps, contretemps, subdivisions, accents, binaire et ternaire |
| **Rythmes de départ** | Rock, disco / house, funk, hip-hop, trap, shuffle blues, reggae, bossa nova, grille vide | Les grooves de base des styles, avec une explication pour chacun |
| **3 kits** | Acoustique, électronique (boîtes à rythmes des années 80), 8 bits (consoles de jeux vidéo) | Le même instrument fabriqué de trois façons : on compare les sons |
| **Réglage du son** (volet à ouvrir) | La « recette » du son (oscillateurs, bruit, filtre, enveloppe), sa forme d'onde, et ses réglages : hauteur, déclin, volume, plus un réglage propre à chaque son | Une batterie électronique fabrique ses sons avec les briques d'un synthétiseur |

Le bouton **Copier le lien de ce rythme** crée une adresse qui contient tout le rythme et les réglages des sons : pratique pour envoyer un exercice aux élèves. Le dernier rythme est aussi gardé sur l'appareil d'une visite à l'autre.

Pour aller plus loin sur les oscillateurs, filtres et enveloppes : le [mini-synthé pédagogique](https://mlevan8395.github.io/mini-synthe/).

## Technique

Une seule page (`index.html`), sans dépendance : tous les sons sont synthétisés en direct avec la Web Audio API, rien n'est enregistré. `manifest.webmanifest` et `sw.js` en font une appli installable qui marche hors ligne. Aucune donnée n'est collectée.

## Licences

- Code : licence MIT (voir `LICENSE`).
- Textes pédagogiques : CC BY-SA 4.0 (voir `LICENCE-CONTENU.md`).

© 2026 Mickael Le Van
