# XDK 3D Control Center — atelier d'impression 3D

Logiciel Windows (10 et 11) de **XDK TEAM DEV** qui réunit **tout ton atelier d'impression 3D au même endroit** :
l'état de chaque imprimante en direct, les caméras, l'historique des impressions, les bobines, les modèles 3D et les
prises connectées.

## Télécharger

Le plus simple : installe-le depuis **XDK Hub** (il se met à jour tout seul).

Sinon :

1. Ouvre la [dernière version](https://github.com/XDK-Vito/XDK-3D-Control-Center-releases/releases/latest).
2. Télécharge **`XDK-3D-Control-Center.exe`** (le fichier `.sha256` à côté sert seulement à vérifier le téléchargement).
3. Lance-le. Windows peut afficher « Windows a protégé votre ordinateur » : *Informations complémentaires* ›
   *Exécuter quand même*.

Il faut **Microsoft Edge WebView2** (déjà présent sur Windows 10 et 11 à jour).

## Clé (essai gratuit de 24 h)

Il faut une **clé** pour utiliser le logiciel : essai gratuit de 24 h, puis **1 mois (9,99 €)** ou **à vie (29,99 €)**.

1. Ouvre le logiciel : il affiche le **code de ton PC** (par exemple `ABCD-EFGH-JKLM`). Copie-le.
2. Rejoins le **Discord XDK TEAM DEV** : https://discord.gg/zEC35KSuxt, choisis ta langue, puis va dans la catégorie
   🧊 XDK 3D CONTROL CENTER, salon 🔑・demande-de-clé.
3. Clique sur « Essai gratuit » et colle ton code PC : le bot t'envoie ta clé tout de suite en **message privé**.
4. Colle la clé dans le logiciel et clique sur « Activer ».

Une clé ne marche que sur le PC de son code.

## Imprimantes prises en charge

« Chercher sur mon réseau » (Paramètres › Mes imprimantes) trouve tes imprimantes toutes seules ; sinon, ajoute-les
à la main : type, nom et adresse IP. Tout passe par ton réseau local.

- **Klipper / Moonraker** (filament) : FLSUN V400 / S1 / T1, Elegoo Neptune 4, Voron, Sovol SV08… — état,
  températures, caméra, historique et commandes à distance.
- **Bambu Lab** (X1, P1, A1, H2D) : numéro de série trouvé tout seul, code d'accès à lire sur l'écran de l'imprimante.
- **Prusa** (MK4, MK3.9, XL, MINI, Core One) avec PrusaLink : mot de passe affiché sur l'écran.
- **OctoPrint** (Ender-3 et toutes les imprimantes Marlin) : clé API obtenue toute seule (« Demander la clé »).
- **Creality** K1 / K1 Max / K1C / K2 Plus / Ender-3 V3 / Hi, **Flashforge** Adventurer 5M / 3 / 4 / Finder,
  **Elegoo Centauri Carbon** : aucun code.
- **Elegoo Saturn / Mars** (résine, protocole SDCP) : Saturn 3 Ultra, Saturn 4 Ultra, Mars 4 Ultra, Mars 5 Ultra…
- **Anycubic Kobra 3 Max** et **Photon P1 Max** : connectées toutes seules par ton compte Anycubic (Slicer Next).

Les codes d'accès restent sur ton PC : jamais affichés ni exportés.

## Ce qu'il fait

- **Tableau de bord** de toutes les imprimantes : en impression, en attente, hors ligne, temps restant, caméras.
- **Historique des impressions** : filtre par période, tri, fiche détail, statistiques par imprimante, graphiques,
  **export Excel**.
- **Bobines au gramme** : le filament utilisé est décompté tout seul (Moonraker) ou par journal.
- **Modèles 3D** : recherche sur Printables, MakerWorld, Thingiverse, Cults3D…, favoris, bibliothèque avec aperçu 3D,
  rangement des téléchargements, lancement du slicer.
- **Prises connectées** (Tuya / LSC Smart Connect, facultatif) : allumer et couper une imprimante, avec avertissement
  si une impression est en cours ou si elle est encore chaude.
- **Sauvegarde automatique** chaque jour, export / import de tes réglages pour changer de PC.
- Cartes déplaçables à la main, thème clair / sombre / automatique, taille du texte.

Tes imprimantes, réglages et clés restent sur ton PC : pas de compte XDK. Le logiciel parle à tes imprimantes sur ton
réseau local (et au compte Anycubic Cloud seulement si tu le relies).
