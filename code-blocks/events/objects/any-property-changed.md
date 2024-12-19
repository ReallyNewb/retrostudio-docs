---
description: Runs connected blocks whenever any property of an object is changed.
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

# Any Property Changed

## Description

Runs connected blocks whenever any property of an object is changed.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Object (Object)

The object that the event will be looking for property changes in.

* [x] Can use Variable

```
Workspace.Brick
```

## Outputs

#### Property (String)

The property that was changed.

```
Anchored
```

#### NewValue (Bool)

The new value of the property.

```
True
```
