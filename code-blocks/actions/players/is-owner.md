---
description: Checks if a player has edit access to the game.
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

# Is Owner

## Description

Checks if a player has edit access or is the owner of the game.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Player (Object)

The player whose ownership will be checked.

* [x] Can use Variable

```
game.Players.RobloxAndTyler
```

#### AllowAuthorizedUsers (Bool)

Includes players that have edit access to the game.

* [x] Can use Variable

```
True
```

## Outputs

#### Result (Bool)

Determines whether or not the target player has edit permissions, or is the owner.

```
True
```
