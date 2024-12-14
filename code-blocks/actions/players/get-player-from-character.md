---
description: Returns a player object from the provided character model.
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

# Get Player From Character

## Description

Returns a player object from the provided character model.

<mark style="color:orange;">Errors if the Character is not a Model object!</mark>

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Character (Object)

The character whose player will be output.

* [x] Can use Variable

```
game.Workspace.RobloxAndTyler
```

## Outputs

#### Player (Object)

The player that has the character provided.
If this is nil, you used an NPC for your character input.

```
game.Players.RobloxAndTyler
```
