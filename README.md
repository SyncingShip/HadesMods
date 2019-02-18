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

## Planned mods
### Janus
An expansion to Seed Recorder, with more information and logging in a spreadsheet
### Quick Death
A suicide button, for quickly resetting a run
### Misc
Adding new boons / gods  
Adding new UI elements, mod configuration menu  
Mod Loader  

## How to create and share your own mods (Through patch files)
1. Navigate your command line to the Scripts folder
2. Make sure your files are fresh by verifying your game files
3. Create an empty git repository with `git init`
4. Add the file you're going to make changes to `git add ScriptFile.lua`
5. Commit the file to the repository `git commit -m "A descriptive message"`
6. Make your changes
7. Add the file you made changes to `git add ScriptFile.lua`
8. Commit the file again `git commit -m "Another descriptive message"`
9. Create the patch file `git format-patch HEAD^1..HEAD`
10. Result: 0001-Another-Descriptive-Message.patch
11. (Optional) Rename the patch file, share it with other people

## Disclaimer
These mods aren't endorsed by Supergiant Games.  
Any game crashes, save corruption, crashes or other problems due to installing these mods are not their responsibility to deal with.  
If you have any questions about modding, or are having issues with any of my mods, feel free to contact me on Discord (Ship#0001)
