# 2PLACEMENT — données de navigation hors ligne

Fichiers publiés en **Releases** par le workflow `offline-data` du dépôt de l'application.
Chaque Release contient :

- `catalog.json` : catalogue des pays (frontière, fichiers, tailles, sha256) ;
- `<ISO>-<date>.pmtiles` : carte d'affichage (Planetiler, schéma OpenMapTiles) ;
- `<ISO>-<date>-routing.tar` : tuiles d'itinéraire Valhalla 3.9.1 ;
- `common-<date>.tar` : style, sprites, polices, modèle de configuration Valhalla ;
- `<ISO>-stats.json` : tailles et durées de génération.

## Licences

- Données © **OpenStreetMap contributors**, sous licence **ODbL 1.0**
  (https://www.openstreetmap.org/copyright). Les cartes et tuiles publiées ici sont des bases
  dérivées sous ODbL ; elles sont reproductibles à partir des extraits Geofabrik et du script
  `offline-data/build-country.sh`.
- Schéma © OpenMapTiles (CC-BY 4.0). Frontières : Natural Earth (domaine public).
- Style Liberty (OpenFreeMap, BSD-3). Polices Noto Sans (SIL OFL).
