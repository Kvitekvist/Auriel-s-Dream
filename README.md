# Auriel's Dream

- [Auriel's Dream](#auriel-s-dream)
- [System Requirements](#system-requirements)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
  - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
  - [Steam Config](#steam-config)
  - [Disable the Steam Overlay](#disable-the-steam-overlay)
  - [Set the Game language to English](#set-the-game-language-to-english)
  - [Clean Skyrim](#clean-skyrim)
  - [Reinstall Skyrim](#reinstalling-skyrim-vr)
  - [Creation Club Updating Protection](#creation-club-updating-protection)
  - [Start Skyrim VR](#start-skyrim-vr)
  - [Using Wabbajack](#using-wabbajack)
   - [Preparations](#preparations)
   - [Downloading and Installing](#downloading-and-installing)
   - [Problems with Wabbajack](#problems-with-wabbajack)
- [Post-Installation](#post-installation)
    - [Activate the Essential Files](#activate-the-essential-files)
    - [Choose ENB or Shader](#choose-enb-or-shader)
    - [Make the game brighter](#make-the-game-brighter)
    - [How to start up Auriel's Dream](#how-to-start-up-auriels-dream)
    - [Setup VRIK](#setup-vrik)
- [Updating](#updating)
- [Optional mods](#optional-mods)
- [Noteworthy Mods](#noteworthy-mods)
- [Removing the Modlist](#removing-the-modlist)
- [Changelog](#changelog)

## Auriel's Dream

Auriel's Dream is a graphical overhaul of Skyrim VR. The focus is to stay close to vanilla while improving the visual experience to next levels. A few mods change gameplay. Check the [Noteworthy Mods](#noteworthy-mods) section later on for more information on is changed.


[![See trailer](https://i.ibb.co/GP7mJ0K/preview.jpg)](https://youtu.be/ZYQVn2SGNI0)

## System Requirements

Minimum system requirements:

Storage Space: 98 GB (rounded uo)

RAM: 32 GB (Or 16GB with a 20GB windows page file) Game uses about 20GB RAM.

CPU: Intel Core i7-7700HQ, 4 cores at 2.80 GHz

GPU: GTX 1660

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Steam Config

### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right-click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**. Wabbajack does not support SkyrimVR files in other languages either. Wabbajack will fail file validation for other languages.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

### Clean Skyrim

Delete the following directories:
1. Open Stem Steam
2. Right click on “Skyrim VR”
3. Choose: Properties >>  Local Files >>  Browse ![image](https://i.ibb.co/V33zFWt/steam-folder.png)
4. Delete all content in the folder. Do not reinstall yet.
5. Open Windows Search and copy/paste %LOCALAPPDATA%
![image](https://i.ibb.co/VpY98qX/ws.jpg)
6. Delete the Skyrim VR folder
7. Navigate to Users\YOURNAME\Documents\My Games\
8. Delete the SkyrimVR folder

### Reinstalling Skyrim VR

Open Steam and ensure that Skyrim is uninstalled through on it.
Reinstall Skyrim VR from Steam.
Run the Skyrim VR launcher through Steam and let it detect your settings, then close the launcher. This is only necessary once.

### Creation Club Updating Protection

Every time the Creation Club releases new content SKSEVR breaks. A fixed version of SKSEVR usually releases fast, but to ensure your game isn’t broken for a few days follow these steps:
Open your Steam Library
Find The Elder Scrolls V: Skyrim VR and open the properties
Click Properties
Click the Updates tab
Under the Automatic Updates section, select “Only update the game when I launch it”

### Start Skyrim VR

After you have done everything above and got a clean Skyrim VR installation ready, start the Launcher and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu. This will make sure that some of the tools the Mod Organizer that comes with Auriel's Dream will find the Skyrim VR folder.

### Using Wabbajack

### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

### Downloading and Installing

Now, create a new folder on the root of your gaming drive. For me, this is the C drive. Name it "Auriels Dream"
![image](https://i.ibb.co/V9JdtQT/C-drive-folder.png)

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. I Highly recommend getting Nexus premium membership to automate the download process.

1. Open Wabbajack
![image](https://i.ibb.co/JK3rdZc/Browse-modlist.png)

2. Click on Browse Modlists, and download Auriel's Dream from the gallery.

3. Once the download of the Wabbajack file is done, run the file and set the Installation folder the folder you just created. The downloads path should automatically fill in the installation path.

4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected . This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for windows defender can be found 
[here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Activate the Essential Files

First, run the program named Essentials Files from Mod Organizer 2.
This step will add the required files for SKSE, Engine Fixes, DLL loader and other essential files that cannot be handled by MO2.

![image](https://i.ibb.co/KrvCB09/essentials1.jpg)

Then Click "OK" if you get a message saying something about Failed to check for update. This is ok.

![image](https://i.ibb.co/P5mpMfH/enb2.jpg)

Then navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://i.ibb.co/YkFSZJ1/enb3.jpg)

Finally, activate the two options "Essential Files" and "3D Audio". If they were already on, then turn them off, then on again.
If you need more performance, you skip 3D audio.

![image](https://i.ibb.co/dQzVFtL/essentials2.jpg)

Next, place this file in the folder where skyrimvr.exe is located (the steam folder for SkyrimVR):
https://drive.google.com/file/d/1n5ZIV09uDbZnDMvF_imLhrhZCBrhSwdU/view?usp=sharing

### Choose ENB or Shader
From MO2, run the ENB program:

![image](https://i.ibb.co/9YSbjZG/enb1.jpg)

Then Click "OK" if you get a message saying something about Failed to check for update. This is ok.

![image](https://i.ibb.co/P5mpMfH/enb2.jpg)

Then navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://i.ibb.co/YkFSZJ1/enb3.jpg)

Now here, you can choose from a list of different ENB profiles. There are 3 difference performance indicators in their names. Low means low performance cost, Medium means medium performance cost and High means high performance cost. 
If any preset was marked as on, then turn them off, then toggle on the button of your choice. By default, The first option is checked. Uncheck this and then check any of the other options that you would like to test.

![image](https://i.ibb.co/FH866MN/enb4.jpg)

### How to start up Auriel's Dream

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.
![image](https://i.ibb.co/BT63QKP/Run-SKSE.png)

### Make the game brighter
Run the ENB program from MO2. Then choose a preset that has the word "Brighter Nights" in it. If the game is still too dark for you, use the VrVIsion preset.

### Setup VRIK
I made 2 videos for VRIK
1. Setup Weapon Holsters: https://www.youtube.com/watch?v=KTGhQCVcgNE
2. Setup Gestures: https://www.youtube.com/watch?v=CEi7gwN8hgg


### Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

### Optional Mods 
Do check out the Optional mods sections. This contains a lot of popular mods.
If you want to use any of these, you only need to activate them. Do not change their load order.

### Optional Gameplay mods

![image](https://i.ibb.co/Yc0vVy3/optional-mods.jpg)

1. MageVR - Popular mod, mostly for the backpack feature and spell gestures.
Not included because: I don't like the background program this mod needs to run. It can get stuck and cause performance issues. VRIK gestures also has a great gesture system.
2. Dual Wield Block VR. 
Not included because (NIB): Not needed unless you play as a dual wield champ. I like to keep "things" to a minimum.
3. Weapon Throw VR. Throw melee weapons, including bound weapons. Very powerful.
NIB: I find it too powerful.
4. VRIK Rift-Index-WMR Controller Bindings. Specific bindings recommended for Rift / Index users.
NIB: Only relevant for some users.
5. Spellsiphon - Immersive Combat. Very powerful and different way of magic gameplay.
NIB: Too powerful and changes the game too much from the Vanilla experience.
6. Dragonborn Speaks Naturally - Use your voice to control dialogues with NPCs.
NIB: Some users struggle to get this working. It also does not seem that most players use voice commands. Keeping active things to a minimum.
7. Ordinator - Perks of Skyrim - For those that want a more advanced perk tree.
NIB: Changes the vanilla game play too much.
8. Apocalypse - Magic of Skyrim - For those who wants way more spells added to the game
NIB: Changes the vanilla game play too much.
9. Apocalypse - Ordinator Compatibility Patch - Needed if you want both mods.
NIB: You need to use both mods above.
10. Simple Realistic Archery VR - You have to draw each arrow manually after each shot.
NIB: I don't find the mod working smoothly enough. If you use this mod, you must make sure that it's plugin is in the top 100 plugins.
11. Harder Dragons Addon - Dragons have MUCH higher stats.
NIB: Changes difficulty significantly against dragons. By default I want the list to be vanilla difficulty.
12. Faster Respawn - Areas reset after only 3 days. Reduces save file bloat and allows for players to clear out dungeons that are already done more frequently.
NIB: I actually recommend having this active as it is good for the save file. But it can be a little exploited by players that just wait 3 days and repeat a cave for easy experience or loot.

### Optional Survival Mode
![image](https://i.ibb.co/5LTCpVt/surivial.jpg)

1. iNeed - Food, Water and Sleep. Very popular mod that makes food much more relevant. Pairs very well with Campire and Frostfall for the ultimate surival experience.
2. Campfire & Frostfall
3. Food effect for Frostfall

### Optional Hard Mode

1. SkyTEST - Harder Creatures SE. Harder creatures in general.
2. High Level Enemies. Harder creatures and they scale to your level.ø
3. Real Bosses. Makes bosses harder.
4. Increased Enemy Spawns SSE No Scripts. 3x more enemies,
5. True Miraak-Harder Miraak. Powers up Miraak.
6. Harder Dragons Addon. Dragons har much harder to take down.
7. Know Your Enemy - Trait-based resistances and weaknesses. You should use different weapon / spell types against different types of enemies.
8. 4. Scarcity SE - Less Loot Mod. Loot becomes much less scares, slowing down your economical growth, and makes finding good treasure much more exciting.
9. Bring Your Silver Lite Vamps Ghosts and Werewolves version - You will need silver weapons to better deal with vampires, ghosts and werewolves!

### Noteworthy Mods

1. [Completionist - Quest Tracker](https://www.nexusmods.com/skyrimspecialedition/mods/46358)
This mod is visible only in the Mod Configuration window, and it helps you keep track of all quests done and not done, as well as all unique items you have and are missing.

2. [Best Version of Quest Rewards](https://www.nexusmods.com/skyrimspecialedition/mods/52024)
You will always get the best version of a reward, so you do not need to wait to be a certain level to get the “perfect” weapon or armor. I find it that if you wait for that, your smithing and enchanting will already surpass the reward’s usefulness. 

3. [Order my items](https://www.nexusmods.com/skyrimspecialedition/mods/13317)
You can now order ingredients from alchemy shops and ores from blacksmiths. Say you need 10 giant toes. You go to an alchemist shop, order the item (15% fee) and wait a day, then you can pick them up.

4. [Well stocked Alchemists](https://www.nexusmods.com/skyrimspecialedition/mods/1094)
Alchemist shops now have WAY MORE ingredients for sale, both in variety and quantity.

5. [Pick up books simple](https://www.nexusmods.com/skyrimspecialedition/mods/2453)
You will no longer read a book before picking it up. This way you can pick up skill books and read them later.

6. [Perk Points and More Gold for Bounty Quests](https://www.nexusmods.com/skyrimspecialedition/mods/2743)
If you do quests from the tavern keepers (I’m looking for work) you now get both gold and perk points.

7. [Dead NPC Body Cleaner Remover](https://www.nexusmods.com/skyrimspecialedition/mods/10614)
You can now burn dead bodies with fire magic or even torches. Useful to clean up the streets or to counter necromancers.

8. [Upgrade Your Potion](https://www.nexusmods.com/skyrimspecialedition/mods/6063)
In cooking pots you can take basic health, mana or stamina potions, combine two of the same quality to get a new potion of a higher quality.

9. [Destructible Display Cases](https://www.nexusmods.com/skyrimspecialedition/mods/13625)
You can now destroy the glass of display cases with blunt weapons and destruction magic. If you are caught, you will get a bounty on you.

10. [GIST - Genuinely Intelligent Soul Trap SE](https://www.nexusmods.com/skyrimspecialedition/mods/15755)
A new and improved solution to the underfilled soul gem problem.

11. [Reading Is Good (Legacy)](https://www.nexusmods.com/skyrimspecialedition/mods/20018)
Reading a skill book now permanently increases your skill leaning speed by 5% per book.

12. [Spell Wheel VR](https://www.nexusmods.com/skyrimspecialedition/mods/47630)
Really nice system for equiping stuff without opening a menu.

### Removing the Modlist

First, run the 2 programs in MO2 called "ENB" and "Essential Files", and toggle off all the options in the preset. You can now remove the MO2 folder and be done with it.

# Changelog

See [Changelog](CHANGELOG.md).
