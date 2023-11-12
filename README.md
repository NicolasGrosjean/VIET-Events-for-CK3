# VIET Events for CK3

<img src="https://i.imgur.com/qyhwEls.jpg">

## Latest Version: 1.11.0 "Qanat" (Released 11/11/23)

_“Water is everywhere around you, but you see only barriers that keep you from water.”_
_– Rumi (1207 - 1273 CE), Persian poet, scholar, Sufi mystic_

Very Immersive Events and Tales (VIET), the sequel to VIET Events Reborn for CK2, is a flavor mod that adds a vast collection of events about everyday life to spice up your game. They add immersion and a diversity of experiences in between wars and vanilla’s event chains, and cover mundane minutiae ranging from small talk with courtiers and eating local cuisine to epic tales about love, philosophy, and the human condition. Some of the events unlock new decisions, character interactions, activities, and much more for you to explore!

I hope the lessons I learned from my eight years (with a hiatus) of modding CK2 will help me deliver a fun experience for any players interested in my mods. Lastly, please note that VIET is not achievement compatible.

Feel free to use my work in your mods - all I ask is that I am credited and (if possible) to give me a heads up.

## Features

- Over **1074** new flavor events to experience!
- Explore new decisions, artifacts, character interactions, activities, and more!
- Game rule to disable sillier events for those who don't like them, with three levels to choose from: Balanced (Default), Serious (Restricted), and All Events (Full)
- Compatible with almost anything since it doesn't touch any vanilla files - even with overhaul mods, you can via game rule disable events that reference things specific to our medieval world that wouldn’t make sense in other time periods or universes (like fantasy and sci-fi conversion mods)
- Learn history with Historical Context tooltips that provide information about what inspired some of the events - sometimes, reality is stranger than fiction! (These can be disabled via game rule for those who find it immersion breaking.)


## Manual Installation Steps

DO NOT manually download the master branch unless you know what you're doing as it is a WIP version and not necessarily stable!

1. Go to https://github.com/cybrxkhan/VIET-Events-for-CK3/releases and find the latest version you wish to download.
2. Extract the "VIET" folder and "VIET.mod" file from the .zip file to Documents\Paradox Interactive\Crusader Kings III\mod
3. Launch CKIII and select VIET in the launcher.
4. Enjoy and play!

The mod folder should look something like this:

<img src="https://i.imgur.com/JEGUadr.jpg">

**NOTE**: If you are re-installing a mod, delete the old version of the mod first before copy and pasting the new one! While it's not always necessary, it's a good habit to do to prevent any potential issues.

## Changelog

### Version 1.11.0

New events added in this version: **8**

- Added 8 water-themed events
- Slightly reduced the chances of travel events
- Miscellaneous bugfixes

* Adapted from VIET for CK2

## Credits

Thanks to all I worked with, took stuff from, and provided me encouragement and feedback over the years. Special thanks in particular to the teams behind WTWSMS (especially IlikeTrains and Loup99) and Lux Invicta (including tsf4), as well as M@ni@c, creator of Hide Your Jewelry, for maintaining and improving on VIET for CK2 over the years, which provided me a solid foundation for improved reboot of VIET Events. Huge thanks also to the kind souls who take the time to translate the mod and put up with my erratic update schedule.

A few other shoutouts in particular:

- Bonseny for the amazing VIET and RICE logos
- OrdepNM, my partner in crime in the early days of VIET for CK2 and who stepped up to help maintain it while I had serious medical issues years ago.
- Sleight of Hand for pushing me to get into the CK2 modding scene and for other assistance over the years, which is why I am still here for some reason.
- tora75 for contributing the Norse unique localizations for several events.
- Stik, Vertimnus, and Tobbzn on the CK3 Mod Co-op for helping me figure out how to adapt my CK2 province events and do a system for county events for CK3.

## Squash the translation (gather all commits in one)

- Get the SHA1 of the last commit which is not from translation
- Run the command
`git rebase -i <SHA>`
- Let the first pick and replace all other by `s`for `squash`
- Push force the branch
