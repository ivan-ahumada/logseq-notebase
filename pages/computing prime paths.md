---
title: Computing prime paths
---

## Find all [[Simple path]]s:
### Meaning find all [[Simple path]]s of length $0$ and extend them to length $1$, then length $2$, and so on.
### Select those that are maximal
## `*` indicates a cycle and it cannot be extended for the next step.
## `!` in a path table means to not consider that node because it doesn't have outgoing edges.
## **CAREFUL**: `!` is also used if a path would repeat nodes on a further extend.
## **CAREFUL:** any path with `*` is a [[Prime path]]
## Any path with `!` needs to be checked if its a subpath of another [[Simple path]]
### If it is, then cross it out
### All remaining paths not crossed out that still have `*` or `!` are [[Prime path]]s
