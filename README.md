# AZK Stremio AniSkip

Patch Morphe pour Stremio Android qui ajoute des boutons `Skip OP`, `Skip ED` et `Skip recap` pendant les segments détectés par AniSkip.

Version du mod : **1.1.0**

Dépôt : <https://github.com/AzukiSensei/aniskip-stremio>

## Fonctionnalités

- récupération du titre, de la saison et de l’épisode depuis les métadonnées et l’URL du média ;
- recherche de l’identifiant AniList puis des segments AniSkip ;
- affichage du bouton uniquement pendant le segment OP, ED ou recap concerné ;
- bouton compact placé à droite et centré verticalement ;
- mode debug désactivé par défaut.

## Configuration

Après avoir ajouté la source dans Morphe et sélectionné le patch **Stremio AniSkip**, l’option **Activer le mode debug** est disponible dans les paramètres du patch. Elle ouvre une fenêtre de diagnostic contenant les données média, les requêtes et les réponses AniList/AniSkip.

Ajouter la source Morphe :

<https://morphe.software/add-source?github=AzukiSensei/aniskip-stremio>

## Compilation locale

```bash
./gradlew buildAndroid
```

Le fichier `.mpp` est généré dans `patches/build/libs/`.

Une copie de la version 1.1.0 est également disponible dans [`releases/stremio-aniskip-morphe-1.1.0.mpp`](releases/stremio-aniskip-morphe-1.1.0.mpp).

## Licence

GPLv3 — voir [LICENSE](LICENSE).
