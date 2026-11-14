---
type: infrastructure
title: Módulo de Archivado Vectorial (STAC, GeoParquet, PMTiles)
description: Preservación de datasets vectoriales en Archive.org como GeoParquet y PMTiles, expuestos mediante STAC 1.1.0 y Frictionless DataPackage.
tags:
  - archivar
  - stac
  - geoparquet
  - pmtiles
  - datapackage
sources:
  - ../archivar/README.md
  - ../archivar/catalog.json
  - ../archivar/actualizar.py
timestamp: 2026-11-14T19:16:00Z
---

# Módulo de Archivado (`archivar/`)

Preserva capas vectoriales de geoservidores de Bolivia en formato GeoParquet y PMTiles, manteniendo metadatos interoperables STAC 1.1.0 y Frictionless DataPackage (`datapackage.json`).

## Artefactos Principales
- [archivar/catalog.json](../archivar/catalog.json): Catálogo raíz STAC 1.1.0 con 26 catálogos institucionales hijos.
- `archivar/publicados/<fuente>/<capa>/`: Contiene `datapackage.json` (6103 paquetes), `collection.json`, `metadata.json`, `sample.json`, `map.png` y `legend.png`.
- [archivar/geoparquet.py](../archivar/geoparquet.py), [archivar/pmtiles.py](../archivar/pmtiles.py), [archivar/stac.py](../archivar/stac.py), [archivar/paquete_datos.py](../archivar/paquete_datos.py): Generadores de artefactos estándar.

## Relaciones
- Alimenta a [publicar.md](publicar.md).
