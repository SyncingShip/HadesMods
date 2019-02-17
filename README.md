# Hades Mods

Mods for the game Hades by Supergiant Games

## Always Show Run Depth
Causes the "Chamber X" text to always display, instead of just in the boon menu. Intended to be useful for speedrunners.

## 100x Darkness
Multiplies all darkness gained by 100. The tooltip will not show the different amount, so keep an eye on your darkness total at the bottom right when picking up darkness to see if the mod is working  
Note: This will also multiply the amount of darkness you lose when buying with darkness from the shopkeeper in the house of hades

## Seed Recorder
Display the seed of whatever room you're in. Also records seeds to Hades/Seeds.txt

## Installation (Windows)
1. BACK UP YOUR SAVE FILES. So far these mods should make no difference to save files, but it is possible to corrupt your save files with code edits similar to this. Saves can be found in `Username/Documents/Saved Games/Hades` 
2. Download and install [git](https://git-scm.com). This will be used for patching the game files.
3. Download this repository using "Clone or download" from the github page
4. If you chose Use Git Bash Only, open Git Bash from the start menu. If you chose either of the other options, open Powershell or CMD
5. Navigate your command line to the scripts folder with   
`cd [Hades folder]/Content/Scripts`
6. Move the patch file you wish to install from the repository you downloaded into somewhere you know, such as the root folder Hades
7. While your command line is in the scripts folder, use  
`git apply [path to .patch file]`

## Uninstalling (Windows)
1. Right click on Hades -> Verify through the Epic Games Store

## Compatibility
The current mods in this repository work with eachother, as they affect different files in different locations. Just apply each patch in whatever order
