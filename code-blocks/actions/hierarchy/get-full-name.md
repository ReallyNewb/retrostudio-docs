---
description: Returns a string describing the object's ancestry.
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

# Get Full Name

## Description

Returns a string describing the object's ancestry.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Object (Object)

The object whose ancestry (full path, for example Game.Workspace.Object) will be output.

* [x] Can use Variable

```
game.Workspace.Part
```

## Outputs

#### FullName (String)

The ancestry of the object.

```
Game.Workspace.Part
```
