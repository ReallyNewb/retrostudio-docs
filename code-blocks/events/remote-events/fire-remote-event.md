---
description: Fires a RemoteEvent.
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

# Fire Remote Event

## Description

Fires a RemoteEvent to its handling client/server. 
<mark style="color:orange;">Strings sent from server-handled event objects will always be filtered!</mark>

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Player (Object)

The player who will receive the message sent by the server. *This output is reserved for server scripts only.*

* [x] Can use Variable

```
game.Players.RobloxAndTyler
```

#### RemoteEvent (Object)

The remote event that will be fired.

* [x] Can use Variable

```
game.Players.RedeemCode
```

#### Parameters (Tuple)

A list of parameters that will be sent to the handling script.

```
[
"MyCode"
]
```
