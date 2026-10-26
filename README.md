# FANTASIAN Neo Dimension — Story Mode

A free, open-source drag-and-drop difficulty change for **FANTASIAN Neo Dimension**.

This is a fan project. It is not made by or affiliated with Square Enix or Mistwalker.

The project is [MIT licensed](LICENSE). Use it, share it, and change it.

**[Download the latest release](https://github.com/dunjeon/FantasianNeoDimension-StoryMode/releases/latest)**

## Install

Close the game. Open the zip and drag the `FantasianND_Data` folder onto the game folder, into the same place as the `FantasianND_Data` folder that is already there. Replace the files when asked.

The game folder is the one that contains `FantasianND.exe`. On Steam it is:

`steamapps/common/FANTASIAN Neo Dimension/`

Start the game. Nothing else needs to be installed. The same drop works on Windows and on Linux through Proton.

## What the menu does

The menu names stay **Normal**, **Hard**, and **Super Hard**. The enemy numbers behind those names change:

| Menu | Enemies |
| --- | --- |
| Normal | Story. HP 60%, attack 50%, defense 60%, speed −4, experience +50%. |
| Hard | Easy. HP 80%, attack 75%, defense 80%, speed −2, experience unchanged. |
| Super Hard | The original Normal enemy stats. |

Both Story and Easy are scaled from the game's original Normal enemy table. A positive HP pool stays at least 1. An agility above 0 never drops below 1, and an agility of 0 stays 0. Enemies that give no experience still give none. Levels, growth, gear, and saved party stats are not edited.

A New Game+ custom enemy slider still scales attack, defense, and speed on top of these tables.

## Remove it

In Steam, verify the integrity of the game files. That restores the original Normal, Hard, and Super Hard tables.

## Files in the release

The zip already has the game's folder layout:

```
INSTALL.txt
FantasianND_Data/StreamingAssets/StandaloneWindows64/packA/asset/3543967287_enemyparameterinfotable
FantasianND_Data/StreamingAssets/StandaloneWindows64/packA/asset/3543967287_enemyparameterinfotablehard
FantasianND_Data/StreamingAssets/StandaloneWindows64/packA/asset/3543967287_enemyparameterinfotablesuperhard
```

Drag `FantasianND_Data` onto the game folder. Leave `INSTALL.txt` where it is.
