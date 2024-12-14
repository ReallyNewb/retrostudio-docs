---
description: Disables or enables a RetroStudio CoreGui.
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

# Set Core GUI Enabled

<mark style="color:orange;">This only works on Late 2013 and above!</mark>

## Description

Disables or enables a RetroStudio CoreGui.

#### Available to

* [ ] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### CoreGui (Choice)

The target CoreGui that the game will disable / enable.

* [ ] Can use Variable

```
Backpack
```

#### Enabled (Bool)

Determines whether or not the CoreGui will be enabled or disabled.

* [x] Can use Variable

```
False
```

## Outputs

#### Result (Bool)

Determines whether or not it successfully disabled / enabled the CoreGui.

```
True
```
