# jukebox-mt
Tera Toolbox module that allows you to listen to some groovy tunes anywhere with a portable jukebox.

(Patch version 92.4 - Menma TERA)

## Usage
Spawn a jukebox with `/8 jukebox` and interact with it to be on your way.

## Installation

* Download this repository and place it in the `/mods/` subfolder of your TERA Toolbox installation.

## Commands
| Main command | Argument(s) | Example | Description |
| -------- | ----------- | ------- | ----------- |
| jukebox | none | !jukebox | Spawns a jukebox, or despawns ones if one is already spawned.|
| jukebox | play (sound) | !jukebox play "CharacterTheme.Popori_ThemeCue" | Manually plays a sounds by filename. Case sensitive. Look at soundData.json, or dump the DC or look into gpks to find all of them. |
| jukebox | mute | !jukebox mute | Ends currently playing sound. |
| jukebox | r | !jukebox r | Reloads the module. You should not ever have to do this (hopefully).

