﻿# Gameplay Ability System for Unity
Gameplay Ability System for Unity (or GAS for short) is a Unity framework for creating games which contain any kind of abilities (e.g. DotA, Skyrim).  The framework helps to simplify the interaction between components in a unified manner.  

The approach for this is taken from that used by Unreal's Gameplay Ability System, but implemented in Unity using the Data-Oriented Technology Stack (DOTS) where possible.  

![GAS in action](https://i.imgur.com/0OTe4KG.gif)
(Now outdated)

## Installation
1. Head over to [Releases](https://github.com/sjai013/UnityGameplayAbilitySystem/releases) and download the latest version.
2. Import package into your Unity project

## Demo
The demo uses the Unity [3d Game Kit](https://assetstore.unity.com/packages/templates/tutorials/3d-game-kit-115747), and showcases an implementation of the attribute system for tracking health, mana, etc.  The conversion is not complete, so expect it to be buggy.

## Code Structure
To understand how everything ties together, go through the code in the *MyGamelpayAbilitySystem* folder.  Raise an issue if you need help.

More detailed documentation/code layout will be added in a later release.  

## Roadmap
The following functionality will be implemented in GAS:
* ~~Attribute System [Done]~~
* ~~Attribute modifiers [Done]~~
* Gameplay Tags [WIP]
* Gameplay Effects [WIP]
* Interaction between Gameplay Effects and Gameplay Tags (e.g. for "dispel" spells) [WIP]
* Abilities
* Interaction between Abilities and Gameplay Effects
* Visual display of abilities (e.g. an "ability bar")
* Visual display of cooldowns (e.g. on an "ability bar")
* Visual display of active gameplay effects
* Sample code showing how to restrict which gameplay effects are displayed (e.g. on a "status bar")
* Targetting system (e.g. single-target, multi-target, intelligent target selection, targettability feedback)
* Customised definition of Ability pre-casting checks
* Ability Combos (e.g. providing some method of defining ability sequences and then executing abilities based on some condition)
* Nicer/more designer-friendly way of defining abilities and effects
* Nicer/more designer-friendly way of defining character stats
* Networking capability (prediction, replication, synching)


## Contributing
You can contribute to this project by:
* Posting issues
* Creating PRs with bug fixes or new features
* Testing this in your own games and telling us how this can be improved
* Adding to the Wiki
* Helping with documentation
* Telling your friends!

## License
Gameplay Ability System for Unity is release under the MIT license.  You are free to use, modify, and distribute this software, as long as the copyright header is left intact.