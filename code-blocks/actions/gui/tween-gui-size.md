---
description: Resizes a GUI to a specific size, easing, and time.
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

# Tween GUI Size

<mark style="color:orange;">Despite its description in the real script editor, this block does not yield!</mark>

## Description

Resizes a GUI to a specific size, with a set easing and time.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Object (Object)

The target GUI whose size will be modified.

* [x] Can use Variable

```
game.StarterGui.AwesomeGui.MainScreen
```

#### Size (UDim2)

The size of which the GUI will smoothly resize to.

* [x] Can use Variable

```
1, 0, 1, 0
```

#### Time (Number)

The time of which the GUI will smoothly resize to.

* [x] Can use Variable

```
1
```

#### EasingStyle (Choice)

Determines the way how the tween will smoothly resize the GUI.

* [ ] Can use Variable

```
Back
```

#### EasingDirection (Choice)

Determines the way how the EasingStyle resizes the GUI.
* In = Forward
* Out = Backward
* InOut = Forward halfway through, and backward for the rest of the duration of time

* [ ] Can use Variable

```
In
```
