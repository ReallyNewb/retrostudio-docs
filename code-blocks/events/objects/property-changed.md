---
description: Runs connected blocks whenever a specific property of an object is changed.
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

# Property Changed

## Description

Runs connected blocks whenever a specific property of an object is changed.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Object (Object)

The object that the event will be looking for property changes in.

* [x] Can use Variable

```
Workspace.GameStarted
```

#### Property (String)

The object property the event will be looking for property changes in.

* [x] Can use Variable

```
Value
```

## Outputs

#### NewValue (Bool)

The new value of the property.

```
true
```
