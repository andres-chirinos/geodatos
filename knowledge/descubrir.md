---
type: operations
title: Módulo de Descubrimiento (GeoServer)
description: Mantiene el directorio manual de instancias GeoServer, el inventario histórico de capas disponibles y el log de disponibilidad de servicios.
tags:
  - descubrir
  - geoserver
  - wms
  - wfs
sources:
  - ../descubrir/README.md
  - ../descubrir/directorio.json
  - ../descubrir/probar_candidato.py
timestamp: 2026-11-14T19:16:00Z
---

# Módulo de Descubrimiento (`descubrir/`)

Monitorea instancias GeoServer públicas de Bolivia y mantiene el inventario vivo de capas WMS/WFS.

## Artefactos Principales
- [descubrir/directorio.json](../descubrir/directorio.json): Directorio de fuentes GeoServer (actualmente 52 entradas con `ows`, `nombre`, `descripcion`, `wms`, `wfs`).
- [descubrir/capas.csv](../descubrir/capas.csv): Inventario histórico de capas descubiertas.
- [descubrir/log.csv](../descubrir/log.csv): Registro histórico de disponibilidad de servicios.
- [descubrir/probar_candidato.py](../descubrir/probar_candidato.py): Utilidad CLI para probar nuevos GeoServer y registrarlos en `directorio.json`.

## Relaciones
- Alimenta a [evaluar.md](evaluar.md) y [publicar.md](publicar.md).
