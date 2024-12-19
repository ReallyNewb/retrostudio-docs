---
description: Runs connected blocks whenever a child is added to an object.
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

# Child Added

## Description

Runs connected blocks whenever a child is added to an object. *A child is a top-level object inside of an object. For example, Workspace.Part is a child of Workspace, but Workspace.Part.Part2 is not.*

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Object (Object)

The object that the event will be looking for additions in.

* [x] Can use Variable

```
Workspace.Model
```

## Outputs

#### Child (Object)

The returned child variable.

```
Workspace.Model.Settings
```
