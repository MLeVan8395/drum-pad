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
| **12 grands pads** | Grosse caisse, caisse claire, cercle, clap, charley fermé, ouvert et au pied, tom aigu, tom basse, ride, crash, cloche. Au doigt ou au clavier (A Z E R T Y / Q S D F G H) | Le rôle de chaque élément de la batterie |
| **Séquenceur** (volet à ouvrir) | Une mesure en doubles croches, comptée « 1 ti ke ta, 2 ti ke ta… ». Notes et accents, tempo, swing, métronome, enregistrement en direct depuis les pads | Temps, contretemps, subdivisions, accents, binaire et ternaire |
| **Rythmes de départ** | Rock, disco / house, funk, hip-hop, trap, shuffle blues, reggae one drop, reggae stepper, jazz swing, bossa nova, grille vide | Les grooves de base des styles, avec une explication pour chacun |
| **3 kits** | Acoustique (vrais enregistrements), électronique (boîtes à rythmes des années 80), 8 bits (consoles de jeux vidéo) | Le même instrument fabriqué de trois façons : on compare les sons |
| **Partition** (volet à ouvrir) | Le rythme du séquenceur écrit en notation de batterie, mise à jour en direct, avec le comptage « 1 ti ke ta » et une barre qui suit la lecture | Le lien avec la FM : lire et écrire un rythme de batterie (durées, silences, accents, portée de percussion) |
| **Réglage du son** (volet à ouvrir) | La « recette » du son (oscillateurs, bruit, filtre, enveloppe), sa forme d'onde, et ses réglages : hauteur, déclin, volume, plus un réglage propre à chaque son | Une batterie électronique fabrique ses sons avec les briques d'un synthétiseur |

Le bouton **Copier le lien de ce rythme** crée une adresse qui contient tout le rythme et les réglages des sons : pratique pour envoyer un exercice aux élèves. Le dernier rythme est aussi gardé sur l'appareil d'une visite à l'autre.

Pour aller plus loin sur les oscillateurs, filtres et enveloppes : le [mini-synthé pédagogique](https://mlevan8395.github.io/mini-synthe/).

## Technique

Une seule page (`index.html`), sans dépendance : les kits électronique et 8 bits sont synthétisés en direct avec la Web Audio API ; le kit acoustique utilise de courts enregistrements (dossier `sons/acoustique`, environ 170 Ko). `manifest.webmanifest` et `sw.js` en font une appli installable qui marche hors ligne. Aucune donnée n'est collectée.

## Clavier MIDI

Avec Chrome ou Edge (ordinateur) ou Chrome (Android), branche un clavier ou un contrôleur à pads en USB et touche **🎹 Clavier MIDI** : les notes suivent la norme General MIDI (Do = grosse caisse, Ré = caisse claire, Fa♯ = charleston…), avec la vélocité. **Apprendre un bouton** relie un potard ou un fader du contrôleur à n'importe quel curseur. Pas disponible sur iPad / iPhone (Apple ne le permet pas).

## Licences

- **Tout le projet** (code, textes, exercices, schémas, partitions) : © 2026 Mickael Le Van, **tous droits réservés** (voir [`LICENSE`](LICENSE)). Reproduction, diffusion et usage commercial interdits sans autorisation écrite de l’auteur. Les éléments de tiers cités restent sous leur propre licence.
- Sons du kit acoustique : extraits de [Virtuosity Drums](https://github.com/sfzinstruments/virtuosity_drums) de Versilian Studios, sous licence CC0 (domaine public). Voir `sons/acoustique/LISEZ-MOI.txt`.

© 2026 Mickael Le Van
