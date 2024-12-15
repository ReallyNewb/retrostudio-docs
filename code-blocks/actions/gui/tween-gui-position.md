---
description: Pivots a GUI to a specific position, easing, and time.
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

# Tween GUI Position

<mark style="color:orange;">Despite its description in the real script editor, this block does not yield!</mark>

## Description

Pivots a GUI to a specific position, with a set easing and time.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Object (Object)

The target GUI whose position will be modified.

* [x] Can use Variable

```
game.StarterGui.AwesomeGui.MainScreen.SomePart
```

#### Position (UDim2)

The position of which the GUI will smoothly pivot to.

* [x] Can use Variable

```
0.2, 0, 0.5, 0
```

#### Time (Number)

The time of which the GUI will smoothly pivot to.

* [x] Can use Variable

```
1
```

#### EasingStyle (Choice)

Determines the way how the tween will smoothly pivot the GUI.

* [ ] Can use Variable

```
Back
```

#### EasingDirection (Choice)

Determines the way how the EasingStyle pivots the GUI.
* In = Forward
* Out = Backward
* InOut = Forward halfway through, and backward for the rest of the duration of time

* [ ] Can use Variable

```
In
```
