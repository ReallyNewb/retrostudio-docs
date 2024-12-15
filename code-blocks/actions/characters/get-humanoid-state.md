---
description: Gets a humanoid's state.
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

# Get Humanoid State

## Description

Gets a humanoid's state.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Humanoid (Object)

The humanoid whose state will be retrieved.

* [x] Can use Variable

```
game.Workspace.ExampleChill.Humanoid
```

## Outputs

#### State (String)

The current state of the humanoid. For knowing state names and their behavior, check the [Enum.HumanoidStateType documentation.](https://create.roblox.com/docs/reference/engine/enums/HumanoidStateType)

```
FallingDown
```
