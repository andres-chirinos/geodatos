---
type: operations
title: Módulo de Publicación Estática
description: Construcción del sitio estático y vistas públicas del índice vivo y del archivo en GitHub Pages.
tags:
  - publicar
  - github-pages
  - sitio-estatico
sources:
  - ../publicar/README.md
  - ../publicar/construir.py
  - ../.github/workflows/publicar.yml
timestamp: 2026-11-14T19:16:00Z
---

# Módulo de Publicación (`publicar/`)

Genera el sitio web estático desplegado en GitHub Pages (`https://mauforonda.github.io/geodatos/`).

## Artefactos Principales
- [publicar/construir.py](../publicar/construir.py): Orquesta la copia de `publicar/src/` a `publicar/dist/` y ejecuta `generar_descubrir.py` y `generar_archivar.py`.
- [.github/workflows/publicar.yml](../.github/workflows/publicar.yml): Workflow automático de compilación y despliegue.

## Flujo
- Etapa final del pipeline de publicación estática.
