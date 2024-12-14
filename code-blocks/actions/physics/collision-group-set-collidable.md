---
description: Changes collision status between two groups.
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

# Collision Group Set Collidable

## Description

Changes collision status between two groups.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### GroupName1 (String)

The first collision group's name.

* [x] Can use Variable

```
BlacklistParts
```

#### GroupName2 (String)

The second collision group's name.

* [x] Can use Variable

```
WhitelistParts
```

#### Collidable (Bool)

Whether or not every Part object in GroupName1 can be intersected with every part in GroupName2.

```
False
```
