---
description: Gets the value of a leaderstat.
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

# Get Leaderstat

## Description

Gets the current value of a specific player's leaderstat.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Player (Object)

The player that you want to get the leaderstat value from.

* [x] Can use Variable

```
game.Players.Roblox
```

#### StatName (String)

Name of the leaderstat that you want to get from the player.

* [x] Can use Variable

```
Coins
```

## Outputs

#### Value (Number)

Returns the current value of the provided player's StatName.

```
CurrentPlayerCoins
```
