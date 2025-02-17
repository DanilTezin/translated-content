---
title: leading
slug: Web/EXSLT/set/leading
tags:
  - EXSLT
  - XSLT
translation_of: Web/EXSLT/set/leading
---
{{ XsltRef() }}

`set:leading()` retourne les nœuds d'un 1er ensemble de nœuds qui se trouvent avant le 1er nœud du 2nd ensemble de nœuds.

### Syntaxe

    set:leading(ensembleNœuds1,ensembleNœuds2)

### Arguments

- `ensembleNœuds1`
  - : L'ensemble de nœuds dans lequel chercher les nœuds qui précèdent le 1er nœuds du 2nd ensemble de nœuds.
- `ensembleNœuds2`
  - : L'ensemble de nœuds avec lequel on compare le 1er ensemble de nœuds.

### Retourne

Un ensemble de nœuds contenant les nœuds appartenant à `ensembleNœuds1` dont les valeurs précèdent le 1er nœud de `ensembleNœuds2`.

{{ Note("Si le 1er nœud de <code>ensembleNœuds2</code> n\'est pas contenu dans <code>ensembleNœuds1</code>, cette fonction retourne un ensemble vide. Si <code>ensembleNœuds2</code> est vide, alors le résultat est <code>ensembleNœuds1</code>.") }}

### Définition

- [EXSLT - SET:LEADING (en)](http://www.exslt.org/set/functions/leading/index.html)

### Support par Gecko

Supporté par Gecko 1.9 et ultérieur.
