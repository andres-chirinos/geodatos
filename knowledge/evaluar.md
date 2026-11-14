---
type: operations
title: Módulo de Evaluación y Priorización
description: Estimación, priorización y preparación de datasets candidatos a archivado a partir del inventario descubierto.
tags:
  - evaluar
  - datasets
  - priorizacion
sources:
  - ../evaluar/README.md
  - ../evaluar/datasets.csv
  - ../evaluar/actualizar.py
timestamp: 2026-11-14T19:16:00Z
---

# Módulo de Evaluación (`evaluar/`)

Evalúa y prioriza las capas descubiertas en `descubrir/` para determinar qué datasets vectoriales son candidatos a ser archivados.

## Artefactos Principales
- [evaluar/datasets.csv](../evaluar/datasets.csv): Tabla de datasets candidatos evaluados.
- [evaluar/actualizar.py](../evaluar/actualizar.py): Pipeline de actualización de evaluaciones.

## Relaciones
- Alimenta a [archivar.md](archivar.md).
