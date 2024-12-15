---
description: Deals damage to a character if they are not protected by a ForceField.
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

# Take Damage

## Description

Deals damage to a character if they are not protected by a ForceField.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Player (Object)

The player whose Humanoid will take damage.

**There are 3 alternatives to a player object. You can input the following:**
* A part (the torso, left leg, head, etc.) of a character's humanoid.
* The character model itself.
* The character's humanoid.

* [x] Can use Variable

```
game.Workspace.Zombie
```

#### Damage (Number)

The amount of damage to deal to the Player.

```
25
```
