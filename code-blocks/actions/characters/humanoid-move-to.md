---
description: Makes a humanoid move to the specified position.
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

# Humanoid Move To

## Description

Makes a humanoid move to the specified position.

<mark style="color:orange;">If the provided humanoid does not reach its target in 8 seconds, the MoveTo will be cancelled.</mark>

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Humanoid (Object)

The humanoid that will move to the provided Target.

* [x] Can use Variable

```
game.Workspace.Zombie.Humanoid
```

#### Target (Vector3)

The position that the Humanoid will move to.

* [x] Can use Variable

```
123, 0, 92
```
