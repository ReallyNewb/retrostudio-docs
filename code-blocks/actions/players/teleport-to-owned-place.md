---
description: Teleports a player to another RetroStudio place.
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

# Teleport To Owned Place

## Description

Teleports a player to another RetroStudio place *as long as its place ID parameter is owned by the creator of the game.* There are options for either creating a new server and teleporting the player to a solo server.

#### Available to

* [x] Scripts
* [ ] LocalScripts
* [x] Yields

## Inputs

#### Player (Object)

The player who will be teleported to the new server/solo server.

* [x] Can use Variable

```
game.Players.CuriousPlayer
```

#### PlaceId (String)

The place ID to teleport the player to. *This place ID must be owned by the creator of the game!*

* [x] Can use Variable

```
38392095_1
```

#### NewServer (Bool)

Determines if the server should be a *new* server.

* [x] Can use Variable

```
true
```

#### SoloServer (Bool)

Determines if the server should be a *solo* server.

* [x] Can use Variable

```
false
```
