# VIET Events for CK3

## Latest Version: 1.4.8 "Animalia" (Released 1/22/22)

_“I have loving-kindness for footless creatures; for those with two feet I have loving-kindness. I have loving-kindness for those with four feet; for those with many feet I have loving-kindness. May all beings, all living beings, all creatures, every one, meet with good fortune; may nothing bad come to anyone.”_

_- Anguttara Nikaya 4:67 (Part of the Pali Canon of Theravada Buddhism)_

Very Immersive Events and Tales (VIET), the sequel to VIET Events Reborn for CK2, is a flavor mod that adds a vast collection of events about everyday life to spice up your game. They add immersion and a diversity of experiences in between wars and vanilla’s event chains, and cover mundane minutiae ranging from small talk with courtiers and eating local cuisine to epic tales about love, philosophy, and the human condition. Some of the events unlock new decisions, character interactions, activities, and much more for you to explore!

I hope the lessons I learned from my eight years (with a hiatus) of modding CK2 will help me deliver a fun experience for any players interested in my mods. Lastly, please note that VIET is not achievement compatible.

Feel free to use my work in your mods - all I ask is that I am credited and (if possible) to give me a heads up.

## Features

- Over 728 new flavor events to experience!
- Explore new decisions, character interactions, activities, and event chains
- Game rule to disable sillier events for those who don't like them, with three levels to choose from: Balanced (Default), Serious (Restricted), and All Events (Full)
- Compatible with almost anything since it doesn't touch any vanilla files - even with overhaul mods, you can via game rule disable events that reference things specific to our medieval world that wouldn’t make sense in other time periods or universes (like fantasy and sci-fi conversion mods)
- Learn history with Historical Context tooltips that provide information about what inspired some of the events - sometimes, reality is stranger than fiction! (These can be disabled via game rule for those who find it immersion breaking.)


## Manual Installation Steps

DO NOT manually download the master branch unless you know what you're doing as it is the WIP version that is constantly being updated!

1. Go to https://github.com/cybrxkhan/VIET-Events-for-CK3/releases and find the latest version you wish to download.
2. Extract the .zip file to Documents\Paradox Interactive\Crusader Kings III\mod
3. Launch CKIII and select VIET Events in the launcher.
4. Enjoy and play!

NOTE: If you are re-installing a mod, delete the old version of the mod first before copy and pasting the new one! While it's not always necessary, it's a good habit to do to prevent any potential issues.

## Version 1.4.8 Changelog

- Added 46 animal themed events
- Added 3 new decisions:
    - Purchase Dependable Donkeys
    - Construct More Dovecotes on Residence
    - Listen to Wild Songbirds
- Added a few new event backgrounds for the Indian region
- Miscellaneous bugfixes

* Adapted from VIET for CK2

## Squash the translation (gather all commits in one)

- Get the SHA1 of the last commit which is not from translation
- Run the command
`git rebase -i <SHA>`
- Let the first pick and replace all other by `s`for `squash`
- Push force the branch
