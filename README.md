# Diablo II - Version Switching Guide

This project serves as a guide to quickly switching between different versions of Diablo II: Lord of Destruction. This is useful if playing with mods which require specific versions of the game. This is not intended to be a fully automatic solution, although such tools are available elsewhere.

 > My [Base Mod](https://github.com/Danjb1/d2-base-mod) can be used to backport a number of fixes from later versions to older versions.

## Instructions

### Setup

First we need a collection of folders like so, one for each version we're interested in:
```
.
+-- Versions
|   +-- v1.07 (Base)
|   |-- v1.12a
|   |-- v1.13d
|   |-- v1.14d
```

The text files in this project list the files required by each of these folders. The files themselves aren't provided here, but they can be easily obtained as described below.

> In a hurry? You can find all of these files online, for example at the bottom of [this page](http://plugy.free.fr/en/index.html).

#### v1.07 (Base)

This is the default version of the game if no patches are installed, so these files can be obtained by simply performing a fresh install of the game.

#### Patches

Once you have the base version, you can simply install one of the official patches, and the relevant files in your game directory will be updated accordingly.

The patches are all hosted by Blizzard, and follow this URL format:

 - **1.12a:** http://ftp.blizzard.com/pub/diablo2exp/patches/PC/LODPatch_112a.exe
 - **1.13d:** http://ftp.blizzard.com/pub/diablo2exp/patches/PC/LODPatch_113d.exe
 - **1.14d:** http://ftp.blizzard.com/pub/diablo2exp/patches/PC/LODPatch_114d.exe

### Switching Versions

Once you have the required files, switching to any version is as simple as grabbing a clean copy of the base version and copying in the required files from a later patch:

1. Copy the v1.07 files into a clean folder (or into an existing Diablo II folder).
2. Copy the files from the desired version into this folder, and overwrite when prompted.

#### Final Warnings

 - Characters saved with a newer version of the game may be incompatible with older versions.
 - Connecting to Battle.net will automatically update your game to the latest version.
