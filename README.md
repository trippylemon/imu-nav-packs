# Offline map packs

Downloadable offline map and routing packs for European regions, used by our navigation app's
"Download regions" screen. This repository contains **data only** — no application code.

Packs are attached to the [`regions` release](../../releases/tag/regions); `catalog.json` there
lists every region with its download URLs, sizes and SHA-256 checksums.

| File | Contents |
| --- | --- |
| `<region>-map.zip` | Vector map tiles (PMTiles), map styles, icons and label fonts |
| `<region>-routing-car.zip` | Car routing graph, address search index and road features (speed cameras, level crossings, traffic calming, signals) |
| `catalog.json` | Region tree (countries → regions → cities) with bounding boxes and pack metadata |

## Licences and attribution

- **Map data © OpenStreetMap contributors**, available under the
  [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
  The tiles, routing graphs, search indexes and road-feature files are derived databases of
  OpenStreetMap and are likewise made available under the ODbL.
- Region extracts and the region list come from [Geofabrik](https://download.geofabrik.de/)
  (OpenStreetMap data, ODbL); some city and oblast boundaries come from OpenStreetMap relations.
- Map styles, sprites and fonts: [OpenFreeMap](https://openfreemap.org/) styles (BSD-3-Clause,
  derived from OpenMapTiles), Noto fonts (SIL Open Font License 1.1).
- Vector tile schema: [OpenMapTiles](https://openmaptiles.org/) (CC-BY 4.0) via Planetiler.
