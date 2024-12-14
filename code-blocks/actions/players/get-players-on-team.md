---
description: Returns a table of all players on a team.
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

# Get Players On Team

## Description

Returns a table of all players on a team.

#### Available to

* [x] Scripts
* [x] LocalScripts
* [ ] Yields

## Inputs

#### Team (Object)

The team whose players will be output in a table.

* [x] Can use Variable

```
game.Teams.Squishy Cherries
```

## Outputs

#### PlayerTable (Table)

The table containing the players who were a part of the team.

```
{game.Players.Cherry1, game.Players.Cherry2, ...}
```
