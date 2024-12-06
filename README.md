# OXCE Mod Collection

This repository implements different MODs for OXCE and Xcom Files MOD. Some are intended to work only with certain forks of original OXCE (see below)

## XFCGarage
Mod for OXCE "Hangars Reworked" fork. Originally intended as a submod for XComFiles MOD, but can be adapted to other MODs and vanilla game.

This submod adds a 1x1 facility to hold small ground crafts as cars and similar. 

The fork adds a "hangar type" id to both facilities and crafts, so they can only match if have the same id (vanilla-not-id'ed crafts and facilities have
a default -1 id, to work as intended in original OXCE).

The mod adds a new garage 1x1 facility, so only cars are allowed to be allocated inside.

## XFCMultiHangar-Example

Mod for OXCE "Hangars Reworked" fork. Originally intended as a submod for XComFiles MOD, but can be adapted to other MODs and vanilla game.

The fork adds a "hangar type" id to both facilities and crafts, so they can only match if have the same id (vanilla-not-id'ed crafts and facilities have
a default -1 id, to work as intended in original OXCE).
It also adds the capacity for hangar-type facilities to store more than 1 craft, and show all crfts stores in Basescape view.

The mod adds an starting base example which includes a garage facility with 1 car parked, and a 3x3 Hangar facility with 4 slots for crafts. In the example, only helicopters and littel-birds can be placed at the 3x3 hangar.

## XComFilesRetainCorpses
Submod for XCom Files master mod. It simply deactivates a fixed option that prevents retain enemies corpses when interrogation finishes.

## MissileMOD (WIP)
A WIP mod to adapt some crafts and facilities for "missile/kamikaze" behavior, which is being implemented at another WIP fork.
