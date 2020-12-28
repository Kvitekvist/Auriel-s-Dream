# Auriel's Dream

- [Auriel's Dream](#auriel-s-dream)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Set the Game language to English](#set-the-game-language-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Reinstall Skyrim](#reinstalling-skyrim)
      - [Creation Club Updating Protection](#creation-club-updating-protection)
      - [Start Skyrim](#start-skyrim)
      - [Using Wabbajack](#using-wabbajack)
        - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
         - [Copy Game Folder Files](#copy-game-folder-files)
  - [How to start up Auriel's Dream](#how-to-start-up-auriel-s-dream)
  - [Updating](#updating)
  - [Noteworthy Mods](#noteworthy-mods)
  - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Changelog](#changelog)

## Auriel's Dream

Auriel's Dream is a graphical overhaul of Skyrim VR. The focus is to stay close to vanilla while improving the visual experience to next levels. A few mods change gameplay. Check the [Noteworthy Mods](#noteworthy-mods) section later on for more information on is changed.


[![See trailer](https://i.ibb.co/k45nLXV/video-cover2.jpg)](https://www.youtube.com/watch?v=I42TrKFAvyg)

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of glall mods you will find are also in Enish. I highly recommend playing the game in English and **I will not give support to people with a non-English game**. Wabbajack does not support SkyrimVR files in other languages either. Wabbajack will fail file validation for other languages.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

Delete the following directories:
1. Open Stem Steam
2. Right click on “Skyrim VR”
3. Choose: Properties >>  Local Files >>  Browse

![image](https://i.ibb.co/V33zFWt/steam-folder.png)

4. Delete all content in the folder. Do not reinstall yet.
5. Open Windows Search and copy/paste %LOCALAPPDATA%
6. Delete the Skyrim VR folder
7. Navigate to Users\YOURNAME\Documents\My Games\
8. Delete the SkyrimVR folder

#### Reinstalling Skyrim VR

Open Steam and ensure that Skyrimis uninstalled through on it.
Reinstall Skyrim VR from Steam.
Run the Skyrim VR launcher through Steam and let it detect your settings, then close the launcher. This is only necessary once.

#### Creation Club Updating Protection

Every time the Creation Club releases new content SKSEVR breaks. A fixed version of SKSEVR usually releases fast, but to ensure your game isn’t broken for a few days follow these steps:
Open your Steam Library
Find The Elder Scrolls V: Skyrim VR and open the properties
Click Properties
Click the Updates tab
Under the Automatic Updates section, select “Only update the game when I launch it”

#### Start Skyrim VR

After you have done everything above and got a clean Skyrim VR installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu. This will make sure that some of the tools the Mod Organizer that comes with Auriel's Dream will find the Skyrim VR folder.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

Now, create a new folder on the root of your gaming drive. For me, this is the C drive. Name it "Auriels Dream"
![image](https://i.ibb.co/V9JdtQT/C-drive-folder.png)

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. I Highly recommend getting Nexus premium membership to automate the download process.

1. Open Wabbajack
![image](https://i.ibb.co/JK3rdZc/Browse-modlist.png)

2. Click on Browse Modlists, and download Auriel's Dream from the gallery.

3. Once the download of the wabbajack file is done, run the file and set the Installation folder the folder you just created. The downloads path should automatically fill in the installation path.

4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected . This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Copy Game Folder Files

Copy the relevant files from the `Installation Folder/Game Folder Files` directory into your game folder (this is where skyrimvr.exe is located).
![image](https://i.ibb.co/z2dd004/Game-folder-files.png)

1. Copy ALL the files marked in green, and paste them into your game folder.
2. There are 2 more folders here. If you have an LCD headset then folder marked in purple is relevant for you. If you have an OLED headset then the one makred in yellow is relevant for you. DO NOT copy the relevant folder. You must OPEN the relevant folder, then copy all the files inside that folder and paste those into the game folder like in step 1.

## How to start up Auriel's Dream

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.
![image](https://i.ibb.co/BT63QKP/Run-SKSE.png)

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Noteworthy Mods

Auriel's Dream uses the full suite of Simon Magus's mods which are:

1. [SkyComplete](https://www.nexusmods.com/skyrim/mods/90941)
This mod is visible only in the Mod Configuration window, and it helps the you keep track of all quests done and not done, as well as all unique items you have and are missing.

2. [Unleveled Items](https://www.nexusmods.com/skyrimspecialedition/mods/254)
You will always get the best version of a reward, so you do not need to wait to be a certain level to get the “perfect” weapon or armor. I find it that if you wait for that, your smithing and enchanting will already surpass the reward’s usefulness. 

3. [Order my items](https://www.nexusmods.com/skyrimspecialedition/mods/13317)
You can now order ingredients from alchemy shops and ores from blacksmiths. Say you need 10 giant toes. You go to an alchemyst shop, order the item (15% fee) and wait a day, then you can pick them up.

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

### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder. The easiest way to remove these, unless you know what files that is, is to do a clean install of Skyrim VR again. See [Clean Skyrim](#clean-skyrim)

## Changelog

See [Changelog](CHANGELOG.md).
