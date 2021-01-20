# Skyrim-SE-New-Dawn
Wabbajack Modlist Installer

- [Skyrim SE: New Dawn](#NewDawn)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Set the Game language and Windows Region to English](#set-the-game-language-and-windows-region-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [ENB](#enb)
  - [How to start up New Dawn](#how-to-start-up-New-Dawn)
  - [Updating](#updating)
  - [Noteworthy Mods](#noteworthy-mods)
    - [Expanded Cities Towns and Villages](#expanded-cities-towns-and-villages)
    - [NPC Retextures](#npc-retextures)
    - [Music and Weather](#music-and-weather)
  - [Creating your Character](#creating-your-character)
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [Controlmap](#controlmap)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Removing the Modlist](#removing-the-modlist)
    - [Filter by Category in MO2](#filter-by-category-in-mo2)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)

## Preamble

New Dawn is a modlist that isn't inspired by any other modlist or mod, it's just its own kind of thing, my main focuses were on graphics and immersion the two main things you need to be immersed in a game but i don't like to add survival mods, you're already doing that in real life, there's no fun in slaying a dragon when all of a sudden you're thirsty and run out of water or something i don't know lets continue.

This modlist requires at LEAST 90GB free to download and install.

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language and Windows Region to English

This entire Modlist is in English and 99% of all mods you will find are also in English. Some mods can break when using a non English version of Windows. Ensure that your Windows Regional Format is set to English. 

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Download the modlist from [here](https://drive.google.com/drive/folders/1KRJD5P88cmixGhXLGLhC8QsbGRKjI9Rc?usp=sharing) and install from drive option in Wabbajack
3. Once the download is done installing, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `D:/Modlists/New Dawn`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait until I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected . This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Copy Game Folder Files

Copy the all of the files from the MO2/Game Folder Files directory into your game folder.

### ENB

New Dawn comes configured with [Visceral ENB](https://www.nexusmods.com/skyrimspecialedition/mods/21779).

## How to start up New Dawn

1. Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it
2. Once it's launched, there will be a dropdown box on the top right, click on it and start up synthesis
3. it will probably ask you to download some things, do that and start again from step 1
4. After synthesis has been launched you can click on the arrow that appears after a short while on the bottom left
5. after you have run both of the cripts go back to mod organizer
6. Again from the drop down menu select Nemesis Engine and start it, click on uodate engine then after than run engine.
7. Once you are done with both things, ensure the drop down menu is set to 'Play New Dawn' then hit the run button to start playing.

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Noteworthy Mods

### Quest and Encounter Mods

New Dawn comes with one new quest and encounters. (More will be added later)

[Falskaar](https://www.nexusmods.com/skyrimspecialedition/mods/2057)
A DLC sized new lands mod that adds 20+ hours of fully voiced lore friendly (But not canon) quests, dungeons, and more.

### Expanded Cities Towns and Villages

[Dawn of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/9074)
A city overhaul for each of the five major holds, new and improved for SE.

### NPC Retextures

[Cathedral Player and NPC Overhaul - HMB II](https://www.nexusmods.com/skyrimspecialedition/mods/24174)
A lore friendly and compatible NPC overhaul that aims to preserve the rugged aesthetic of people in Skyrim.

[Guards Armor Replacer SSE](https://www.nexusmods.com/skyrimspecialedition/mods/22671)
Replacer for guards and Stormcloak Armor.

### Music and Weather

[Obsidian Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/12125)

[True Storms](https://www.nexusmods.com/skyrimspecialedition/mods/2472)

## Creating your Character

It's recommended to temporarily disable the ENB while creating your character so you can actually see what you're doing. Shift+Enter brings up the ENB gui. Untick "Use Effect" in the bottom left panel.

#### After you configure the MCM and start to choose your selection of escaping the cell, I highly recommend you follow my advice here.

- I don't recommend the Necromancer start unless you want to die repeatedly while screaming and running for the exit.

- Do not select the carriage ride (Vanilla Intro). I do not provide support for your game breaking if you do this.

## In-Game MCM Options

Tweak them to your liking :)

## Other Post Installation FAQ

### Controlmap

These are currently the custom controls added by Mods. Feel free to customize them within the Mod's MCM menus

- Press 'Lalt' to Dodge Roll

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)
  
 #### Darkness Settings
 
 - If you want the game to be brighter or darker, you can use quick adjustors under `ENBEFFECT.FX`, --Nights & Interior Adjustors--

##### If you cannot handle the ENB: Disable `UseEffect` in enbseries.ini

#### More color correction

Fiddle with the Obsidian Weathers MCM for more color customization.

### Zoomed in Display

This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

- Set the display scaling back to 100% in the Screen Resolution Settings for Windows
- Edit the mod SSE Display Tweaks.
  - Under `[Render]`
    - Set Fullscreen to `True`
    - Set Borderless to `False`

## Filter by Category in MO2

Every single mod in New Dawn has been given correct categories for easy searching, if you want a deeper dive by visiting a mod on the Nexus (right click mod - 'Visit on Nexus', if you're unsure about what it is, or what it does.

### Removing the Modlist

You can just remove the MO2 folder and be done with it.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!
- Noggog for Mutagen
- Special thanks to the Synthesis patcher devs
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you
- LostDragonist for helping me make the list
- Luca|CST for providing the base mods


## Contact

You can DM me @Tonii#1020 on Discord, for any help

## Changelog

See [Changelog](CHANGELOG.md).
