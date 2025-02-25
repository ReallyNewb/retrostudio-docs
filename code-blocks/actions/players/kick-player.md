---
description: Kicks a player from the game. Does nothing for RetroStudio admins, this is to prevent rule-breaking games from not being checked by admins.
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

# Kick Player

## Description

Kicks a player from the game. Does nothing for RetroStudio admins, this is to prevent rule-breaking games from not being checked by admins.

#### Available to

* [x] Scripts
* [ ] LocalScripts
* [ ] Yields

## Inputs

#### Player (Object)

The player who will be kicked from the game.

* [x] Can use Variable

```
game.Players.ExploiterAccount
```

#### Reason (String)

The reason for the player's kick.

* [x] Can use Variable

```
Kicked for Rule #1: No fling exploits allowed.
```
