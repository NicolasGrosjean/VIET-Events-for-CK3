# VIET Events for CK3

## Latest Version: 1.3.4 "Arboretum" (Released 5/15/21)

_“If you have a garden in your library, everything will be complete.”_
_- Cicero, letter to Varro_

Very Immersive Events and Tales (VIET), the sequel to VIET Events Reborn for CK2, is a flavor mod that adds a vast collection of events about everyday life to spice up your game. These events add immersion and a diversity of experiences in between wars and vanilla’s event chains, and cover mundane minutiae ranging from small talk with courtiers and eating local cuisine to epic tales about love, philosophy, and the human condition.

Alongside many new events, I intend to adapt many of the events from the old VIET for CK2 as possible. I hope the lessons I learned from my eight years (with a hiatus) of modding CK2 will help me deliver a fun experience for any players interested in my mods.

Feel free to use my work in your mods - all I ask is that I am credited and (if possible) to give me a heads up.

## Features

- Over 454 new flavor events and event chains, and more will be added in updates over time
- Game rule to disable sillier events for those who don't like them, with three levels to choose from: Balanced (Default), Serious (Restricted), and All Events (Full)
- Compatible with almost anything since it doesn't touch any vanilla files - even with overhaul mods, you can via game rule disable events that reference things specific to our medieval world that wouldn’t make sense in other time periods or universes (like fantasy and sci-fi conversion mods)
- Learn history with Historical Context tooltips that provide information about what inspired some of the events - sometimes, reality is stranger than fiction! (These can be disabled via game rule for those who find it immersion breaking.)
- NOT ACHIEVEMENT COMPATIBLE!


## Manual Installation Steps

DO NOT manually download the master branch unless you know what you're doing as it is the WIP version that is constantly being updated!

1. Go to https://github.com/cybrxkhan/VIET-Events-for-CK3/releases and find the latest version you wish to download.
2. Extract the .zip file to Documents\Paradox Interactive\Crusader Kings III\mod
3. Launch CKIII and select VIET Events in the launcher.
4. Enjoy and play!

NOTE: If you are re-installing a mod, delete the old version of the mod first before copy and pasting the new one! While it's not always necessary, it's a good habit to do to prevent any potential issues.

## Squash the translation (gather all commits in one)

- Get the SHA1 of the last commit which is not from translation
- Run the command
`git rebase -i <SHA>`
- Let the first pick and replace all other by `s`for `squash`
- Push force the branch
