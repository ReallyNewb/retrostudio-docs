---
description: Moves a model to the given position with the PrimaryPart as the center.
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

# Set Model Primary Part CFrame

## Description

Moves a model to the given position with the PrimaryPart as the center.

<mark style="color:orange;">Errors if the model doesn't have a PrimaryPart!</mark>

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Model (Object)

You give the path to an object that you want to move.

* [x] Can use Variable

```
workspace.Tree
```

#### CFrame (CFrame)

The CFrame of which the model will be pivoted to.

* [x] Can use Variable

```
Position: 180, 45, 120 | Rotation: 180, 0, 0
```

## Outputs

This block does not have any outputs.
