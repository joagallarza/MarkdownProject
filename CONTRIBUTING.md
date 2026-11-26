# Contributing to MarkdownProject

Gràcies per voler contribuir a **MarkdownProject**! Aquest document explica com fer-ho de manera ordenada.

## Table of Contents

- [Code Style](#code-style)
- [Pull Requests](#pull-requests)
- [Reporting Issues](#reporting-issues)

## Code Style

- Escriu el contingut en **Markdown** i revisa'l amb la previsualització de VSCode abans de fer commit.
- Fes servir encapçalaments jeràrquics (`#`, `##`, `###`) sense saltar nivells.
- Per als blocs de codi, indica sempre el llenguatge (per exemple ` ```python `).
- Missatges de commit:
  - en anglès i en imperatiu (*Add*, *Fix*, *Update*...);
  - curts i descriptius, per exemple `Add feature list table to README`.

## Pull Requests

1. Crea una branca a partir de `main` amb el format `feature/<número-issue>-<descripció>`.
2. Fes commits petits, un per cada canvi lògic.
3. Puja la branca a GitHub amb `git push -u origin <branca>`.
4. Obre un *pull request* cap a `main` i referencia la issue a la descripció (per exemple, `Resolves #1`).
5. Espera la revisió i aplica els canvis que et demanin abans de fer el *merge*.

> Un pull request ha de resoldre **una sola** issue.

## Reporting Issues

Abans d'obrir una issue, comprova que no n'hi hagi una d'igual. Quan la creïs, inclou:

| Camp | Descripció |
|------|------------|
| Títol | Resum curt del problema o de la millora |
| Descripció | Què passa i què esperaves que passés |
| Passos | Com reproduir el problema, si n'hi ha |
| Captures | Imatges o sortides de terminal que ajudin a entendre-ho |
