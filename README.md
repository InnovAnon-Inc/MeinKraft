# iameinkraft [![luacheck][luacheck badge]][luacheck workflow]  
IA MeinKraft Mods, Redos and Extensions
==========

[![Tip Me via PayPal](https://img.shields.io/badge/paypal-donate-FF1100.svg?logo=paypal&logoColor=FF1133&style=plastic)](https://www.paypal.me/InnovAnon)

----------

## End Game Scenarios
- space wars
  - death star lasers
- roko
- grey goo
- thanos
  - maybe unique items (only craftable once)
- alchemical transmutation
  - fma
- exodia
  - maybe unique items
  - kills all players except creator
- cosmic horror
  - super cool mob that Fs the map (lbm) and eats players
- magickal dark aeon
  - various dark effects that should make the world uninhabitable
- pestilence
  - spawn bugs, strip land bare
- plague
  - sicken all players
- poverty
  - newly loaded blocks stop yielding ore, etc.

-----

## TODO

- add submodules
  - iamapgen

- ialazor
  - beam is still janky
  - explosions need an iterator
  - coilgun should spawn a black hole that eats the map
  - beam should fire continuously => run explosion iterator while beam is firing

- iaspawn 
  - track ancestry of players and entities,
  - death/respawn handling
  - need lineage-tracking, dummy players
  - players can never leave (ie simulate staying logged in even when logged out)
    => helpful messages: you soiled youself n times while you were logged out

- iaroko
  - dummy logic is stubbed out. now the mod needs to be written
  - craft using punch cards
    - tier 1: punch cards crafted similarly to iadiscordia magic items (literally figuring out codes)
    - tier 2: random recipe shapes of t1 punch cards to create t2 punch cards ("reuseable modules / OOP")
    - use punch card on computer node for interesting effects
    - false punch card recipes (so players can input an invalid recipe and reach a dead end)
    - use randomized punch card names ?
    - need to be able to clone punch cards with contrib data for FOSS in-game
    - doc/man punch card (explains the mod)

- iagauntlet
  - finish stones
  - create gauntlet

- iafakery
  - need to make defective items (hurt player or F up env on_use, on_rightclick)

- ianews 
  - more papers,
  - data,
  - newspaper stack is derpy

- iapepe
  - manipulate rest api on various conditions such as last man standing with #player > quota

- iamapgen
  - temple of innovanon
  - backrooms (core) (lbm regen ?)
  - mantle (lava ocean),
  - big ocean (big and deep and creepy),
  - space,
  - frozen north/south

- iadecor
  - can use bug jars on player => player shits bees/spiders
  - picture recipes

- iaskills janky, only has dummy logic

- working_villagers
  - gender info
  - lil ones
  - randomly walking off cliffs
  - route via climbable
  - don't route through impassable entities
  - specific missing jobs
  - refactor job node/tool/etc that's used for abm placement so it can be used for useful talking messages
  - cleanup the api, break things into modules, more subdirs
  - lineage support
  - more intelligent tool use now that we have tool use
  - write a dep mgmt sys, compiler, os, kitchen sink
  - sleep schedules / shifts
  - HB support
  - rework wizard to use the new iadiscordia features
  - combat logic
  - inventory lists
  - village info / central planning

- babel    - override translator to obfuscate all text in game based on player's reading comprehension skill

- mobs

- utils
  - check for recipes with invalid outputs
  - check for items with no recipes



- iadiscordia
  - need to finish randomization logic
  - magic circles
  - magic items with autocast (for security)
  - spells:
    - spawn tree / flora
    - shit yourself
    - shit storm
    - combust
    - avalanche / collapse
    - meteor
    - invert crosses - more crosses
    - grant perms - more mods/perms
    - api calls - more mods
    - stat drain
      - hp
      - mp
      - hunger
      - sleep
      - breath
    - poison
  - weakness ? / gravity
  - explosion
  - magic missile
  - fireball
  - teleport
  - float / fly
  - invisibility / shrink
  - clip ?
  - technic power (generates power)
  - decay (stone->gravel->sand, plants->dry)
  - kill player by name
  - black hole
  - transforming liquid add
  - override day night ratio
  - thanos (kill half the players / entities)

- apartments and other schematics

- hardcore farming
- rip assets from other mods
- rip .mts from other mods
- harder farming:
  - need crop rotation / soil depletion
  - need flowing water (ie not stagnant)
  - aquaponics ?
  - aqua farming ?
  - fishing ?

----------

[luacheck badge]: https://github.com/InnovAnon-Inc/iafakery/workflows/luacheck/badge.svg
[luacheck workflow]: https://github.com/InnovAnon-Inc/iafakery/actions?query=workflow%3Aluacheck

----------

# InnovAnon, Inc. Proprietary (Innovations Anonymous)
> "Free Code for a Free World!"
----------

![Corporate Logo](https://innovanon-inc.github.io/assets/images/logo.gif)

