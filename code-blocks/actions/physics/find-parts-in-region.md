---
description: Returns a table of all parts within the given area.
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

# Find Parts In Region

## Description

Returns a table of all parts within the given area.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### CFrame (CFrame)

The position and rotation of the region.

* [x] Can use Variable

```
Position: 0, 0, 0 | Rotation: 0, 0, 0
```

#### Size (Vector3)

The size of the region.

* [x] Can use Variable

```
50, 100, 50
```

#### FilterType (Choice)

Determines how the region will look for its parts.

* [ ] Can use Variable

```
Blacklist
```

#### FilterDescendantsTable (Table)

A list of parts the region will look for.

* [ ] Can use Variable

```
blacklistedParts
```

#### MaxParts (Number)

Determines how many maximum part objects can be scanned in the region.

* [x] Can use Variable

```
50
```

## Outputs

#### PartsTable (Table)

The scanned parts that the region found.

```
{game.Workspace.Object, game.Workspace.Object2, ...}
```
