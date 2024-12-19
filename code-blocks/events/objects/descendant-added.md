---
description: Runs connected blocks whenever a descendant is added to an object.
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

# Descendant Added

## Description

Runs connected blocks whenever a descendant is added to an object. *A descendant is an object in an object, regardless of its level. Both Workspace.Part and Workspace.Part.Part2 are both descendants of Game and Workspace.*

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Object (Object)

The object that the event will be looking for any addition in.

* [x] Can use Variable

```
Workspace.Model
```

## Outputs

#### Descendant (Object)

The returned descendant variable.

```
operationScript (Workspace.Model.Scripts.Operations.OperationScript1)
```
