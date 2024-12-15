---
description: Finds a path between the two positions. Returns a table of Vector3s, or a table with no elements if the path couldn't be computed.
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Compute Path

## Description

Finds a path between the two positions. Returns a table of Vector3s, or a table with no elements if the path couldn't be computed.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [x] Yields

## Inputs

#### StartPosition (Vector3)

The start position of the path.

* [x] Can use Variable

```
0, 100, 0
```

#### EndPosition (Vector3)

The end position of the path.

* [x] Can use Variable

```
0, 0, 100
```

## Outputs

#### ComputedPath (Table)

The table of Vector3s that the path computed. *These are directly Vector3s, meaning you can loop through them and put their values in a position-based object property.*

```
{Vector3, Vector3, ...}
```
