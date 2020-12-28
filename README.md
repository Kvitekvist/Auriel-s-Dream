# Auriel's Dream

- [Auriel's Dream](#auriel-s-dream)
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
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
         - [ENB](#enb)
  - [How to start up Equanimity](#how-to-start-up-equanimity)
  - [Updating](#updating)
  - [Noteworthy Mods](#noteworthy-mods)
    - [Gameplay](#gameplay)
    - [Quest and Encounter Mods](#quest-and-encounter-mods)
    - [Expanded Cities Towns and Villages](#expanded-cities-towns-and-villages)
    - [NPC Retextures](#npc-retextures)
    - [Followers](#followers)
    - [Audio and Weather](#audio-and-weather)
    - [New Equippables](#new-equippables)
  - [Creating your Character](#creating-your-character)
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [Controlmap](#controlmap)
    - [Ultrawide Options](#ultrawide-options)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Zoomed in Display](#zoomed-in-display)
    - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)

## Auriel's Dream

Auriel's Dream is a graphical overhaul of Skyrim VR. The focus is to stay close to vanilla while improving the visual experience to next levels. A few mods change gameplay. Check the [Noteworthy Mods](#noteworthy-mods) section later on for more information on is changed.

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

#### Reinstalling Skyrim

Open Steam and ensure that Skyrimis uninstalled through on it.
Reinstall Skyrim from Steam.
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

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Click on Browse Modlists, and download Auriel's Dream from the gallery.
3. Once the download is done set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Auriels Dream`). The downloads path should automatically fill in the installation path.
![image](https://i.ibb.co/V9JdtQT/C-drive-folder.png)

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

Copy the all of the files from the `Installation Folder/Game Folder Files` directory into your game folder.

### ENB

Equanimity comes configured with [Rudy ENB For Cathedral Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/39113)
The ENB AO, Letterbox and Depth of Field have been disabled due to preference and performance reasons. Feel free to re-enable them should you desire.

If you want a different ENB. You can choose from a wide variety of ENBs on the Nexus that support Cathedral Weathers. To replace the ENB installed. Delete the enbcache folder, enbseries folder, enbseries.ini and replace those with the new ENB. You don't have to delete the enblocal.ini as that contains tweaks that don't affect how it looks but rather things like screenshot formats, vsync settings.

A few other ENB suggestions are:

- [Ljoss](https://www.nexusmods.com/skyrimspecialedition/mods/30971)
- [Silent Horizons](https://www.nexusmods.com/skyrimspecialedition/mods/21543)
- [Serio's ENB](https://www.nexusmods.com/skyrimspecialedition/mods/30506)
- [Soul Spectrum ENB](https://www.nexusmods.com/skyrimspecialedition/mods/29675)

**Note:**
Please check that vsync is set to disable in enblocal.ini otherwise you will either be stuck compiling shaders or a black screen, or the menu with no options.

## How to start up Equanimity

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Noteworthy Mods

### Gameplay

Equanimity uses the full suite of Simon Magus's mods which are:

1. [Adamant - A Perk Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/30191)
2. [Mysticism - A Magic Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/27839)
3. [Arena - An Encounter Zone Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/33487)
4. [Blade and Blunt - A Combat Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/34549)
5. [Aetherius - A Race Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/26686)
6. [Mundus - A Standing Stone Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/33411)
7. [Scion - A Vampire Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/41639?)

Various other mods are used to flesh out all aspects of the game as well such as:

1. [Growl - Werebeasts of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/31245) for overhauling Lycantrophy
2. [Triumvirate - Mage Archetypes](https://www.nexusmods.com/skyrimspecialedition/mods/39170) which adds new mage archetypes to the game
3. [Complete Crafting Overhaul Remastered](https://www.nexusmods.com/skyrimspecialedition/mods/28608) which overhauls the crafting component of the game
4. [Skyrim Revamped - Complete Enemy Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/14598) which overhauls NPC and makes bosses harder
5. [Wintersun - Faiths of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/22506) adds a religion aspect to the game in the form of worshipping aedras or daedras and getting rewarded for it
6. [OMEGA Updated](https://www.nexusmods.com/skyrimspecialedition/mods/33718) is an overhaul around Morrowloot Ultimate which blends well with mods like Skyrim Revamped, Guards Armor Replacer and a lot of other stuff
7. [Spell Perk Item Distributor](https://www.nexusmods.com/skyrimspecialedition/mods/36869) and [Enemy (R)evolution of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/37228) allows for enemies to use spells and perks from mod added stuff
8. [Equipment Durability System](https://www.nexusmods.com/skyrimspecialedition/mods/19023) adds a durability system to the temperness of your equipment which can be viewed on the bottom left of the screen
9. [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) drastically changes how pacing in the game is done. Rather than only getting experience on skill level ups, you now gain experience level for completing quests and killing monsters
10. [Reqliquary of Myth](https://www.nexusmods.com/skyrimspecialedition/mods/31612) and [Unique Item Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/33723) overhauls a lot of unique items and artifacts to make the gameplay feel fresh
11. [Know Your Enemy](https://www.nexusmods.com/skyrimspecialedition/mods/13807) adds trait based weakness and resistances based on armor and enemy type. You will be doing less damage to draugr for example by using frost spells on them

### Quest and Encounter Mods

Equanimity comes with a wide variety of new quest and encounters. A few are listed below.

[Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802) is a very large mod that shapes the way how you play the game. The museum is a very robust house mod with the ability to display almost every item in the game and also has an extensive mod support which is utilised to some extent in Equanimity.

[Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194) adds over 250 fully voiced NPCs, 25+ followers, 15+ marriage candidates and 50+ quests to fully flesh out the world of Skyrim. Every hold will feel more lively with more NPCs walking and talking with each other

[Missives](https://www.nexusmods.com/skyrimspecialedition/mods/17576?tab=files) adds a large number of localized radiant quests found at Missive Boards of varying difficulty and with varying rewards. Missives has been extended to Solstheim as well as Wyrmstooth.

[Vigilant](https://www.nexusmods.com/skyrimspecialedition/mods/11849) adds a whole new set of quests, enemies, equipment to the game revolving around the Vigilants of Stendar and Daedra. Vigilant has been tweaked to only start at level 30 to prevent easy access to daedric equipment as well as prevent you from getting your ass kicked by bosses.

[Wyrmstooth](https://archive.org/details/wyrmstooth1.18SSE) adds a new world and a series of quests involving killing a dragon for a bounty. It's a very well done quest mod.

[Helgen Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/5673) adds a lengthy questline with the aim of rebuilding Helgen.

[Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179) is a really good choice driven quest mod with a lot of endings surrounding the disappearance of a civilisation.

[Project AHO](https://www.nexusmods.com/skyrimspecialedition/mods/15996) is a medium sized DLC questline surroudning the Great House Telvanni.

[Undeath](https://www.nexusmods.com/skyrimspecialedition/mods/6180) and [Undeath Classical Lichdom](https://www.nexusmods.com/skyrimspecialedition/mods/40802) is a quest and expansion mod that delves deep into necromancy and offers a new lich transformation.

[Wheels of Lull](https://www.nexusmods.com/skyrimspecialedition/mods/748) is an expansive questline filled with puzzles, infiltration, poltergeists, mad science, and butter. Note that the questline starts at level 40.

[Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168) adds a questline and multiple dungeons and new artifacts to uncover.

[The Gray Cowl of Nocturnal](https://www.nexusmods.com/skyrimspecialedition/mods/4509) sends you off on a quest to obtain the coveted gray cowl. While thieving around you will receive a vision that takes you on this quest to retrieve the cowl.

[Relics of Hyrule](https://www.nexusmods.com/skyrimspecialedition/mods/12244) integrates quite a fair amount of content from the Zelda universe that surprisingly doesn't feel out of place. There are no quests or markers to lead you on your way. Keep an eye and an ear open for glowing fairies and tinkling noises as those mark most locations of Hyrule content.

Equanimity also has a lot of modified vanilla quests such as:

1. [Save the Icerunner - Lights Out Alternate Route](https://www.nexusmods.com/skyrimspecialedition/mods/34681)
2. [Finding Derkeethus](https://www.nexusmods.com/skyrimspecialedition/mods/19550)
3. [Finding Helgi and Laelette](https://www.nexusmods.com/skyrimspecialedition/mods/28973)
4. [Finding Velehk Sain](https://www.nexusmods.com/skyrimspecialedition/mods/19815)

### Expanded Cities Towns and Villages

Equanimity uses the full suite of [JK's Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/6289) along with all of the interior patches for it.

### NPC Retextures

I have to give credits to Darkladylexy from the popular [Lexy's Legacy of the Dragonborn Special Edition](https://lexyslotd.com) guide for her extremely well done choices of NPC mods. It is a combination of a lot of NPC mods with carefully picking which npc comes from which mod itself. For an overview of every single NPC that is retextured. Please see [this section on her guide](https://lexyslotd.com/guide/npc-retextures-page/)

The NPC retextures are largely in this order except a select few NPCs

1. WICO - Windsong Immersive Character Overhaul
2. Followers Hirelings and Housecarls
3. Metalsabers Beautiful Orcs of Skyrim
4. The Ordinary Women
5. Pandorable's NPCs
6. Kalilies NPCs
7. Fresh Faces
8. Pandorable's NPCs - Dawnguard
9. Pandorable's NPCs - Dragonborn
10. Bijin Warmaidens
11. Bijin Wives
12. Bijin NPCs
13. Seranaholic
14. Valerica
15. eeekie's Enhanced NPCs
16. RS Children Overhaul
17. Cuyima Interesting NPCs
18. High Poly Inigo
19. Legacy of the Dragonborn NPC Overhaul

For an overview of every single NPC that is retextured. Please see [this section on her guide](https://lexyslotd.com/guide/npc-retextures-page/).

### Followers

[Inigo](https://www.nexusmods.com/skyrimspecialedition/mods/1461) is a fully voiced khajiit adventuring companion with over 7000 lines of unique dialogue - much of it about you. He'll level alongside you and avoid most traps. If you're sneaking he won't chatter and he'll whisper if you talk to him. He can run out of arrows. He's highly skilled in archery, one-handed, and sneak.

[Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035) is a fully voiced Imperial follower with around 3000 lines of immersive, lore-friendly dialogue. Though he arrives in Skyrim as a cowardly scholar, he'll gradually gain strength and confidence by your side until he grows into a hero in his own right.

[M'rissi's Tails of Trouble](https://www.nexusmods.com/skyrimspecialedition/mods/9666/) adds a questline, and a new female khajit follower that is also a marriage candidate.

### Audio and Weather

[Audio Overhaul Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/12466) and [Immersive Sounds Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/523) offer an amazing base for skyrim's ambiance and foley.

### New Equippables

[Amulets of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/487) adds new amulets as well as the ability to turn standing stone/artifact effects into necklaces and rings.

[Black Mage Armor](https://www.nexusmods.com/skyrimspecialedition/mods/356) adds a new cloth/light/heavy armor that looks incredibly cool for a mage/battlemage.

[Bosmer Armor Pack](https://www.nexusmods.com/skyrimspecialedition/mods/5597) adds a new craftable armor set suitable for bosmer/druid playstyles.

[Cloaks of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/6369) provides cloaks to various NPCs.

[Dawnguard Arsenal](https://www.nexusmods.com/skyrimspecialedition/mods/25094) expands the weapon choices of the dawnguard with new and improved variety.

[Heavy Armory](https://www.nexusmods.com/skyrimspecialedition/mods/6308) adds around 100 new weapons into the game that is evenly distributed to all the enemies and NPCs.

[Common Clothes and Armors](https://www.nexusmods.com/skyrimspecialedition/mods/21305) adds more variety of common clothes to leveled lists.

[Nordic Wanderer](https://www.nexusmods.com/skyrimspecialedition/mods/7943) adds two new swords and a new armour set for male and females. There is full weight-slider support and the armour should be compatible with all body mods.

[Volkihar Knight - Vampire Armor](https://www.nexusmods.com/skyrimspecialedition/mods/4806) is a really cool Vampire armour set that can be crafted or found in the Volkihar Castle from progressing in the Dawnguard Questline

[Sithis Armor](https://www.nexusmods.com/skyrimspecialedition/mods/39080) is an incredible armor set. The addon [Sithis Armor - Mastercraft Version](https://www.nexusmods.com/skyrimspecialedition/mods/39209/) adds additional sets, makes it easier to craft as well as adding CCOR compatibility.

## Creating your Character

Upon entering the game you will be greeted with a notification from the Curator's Companion. Hit OK and wait for another pop-up from it, usually takes about a minute. Wait until there are no more messages on the top left corner. Then you can hit escape and click on Mod Configuration to continue this section.

Mods or sections with (Preference) next to their name is solely preferential and do not affect the balance of the game.

## In-Game MCM Options

The required MCM options have been automated for you. Enjoy the game or tweak the following to your liking:

- Immersive HUD
- All Geared up Derivative
- SkyUI
- Lucien (If you set a nickname that's supported he can call you by that name)
- XP32 Skeleton Styles

**NOTE. Dodging is provided by the Mod "The Ultimate Dodge Mod". Please head to System > Controls > Sneak and change the Keybind to  whatever you want to use to dodge with. I recommend side mouse buttons. If you do not change this to something else, your character will not be able to sneak or will be stuck sneaking.**

## Other Post Installation FAQ

### Controlmap

These are currently the custom controls added by Mods. Feel free to customize them within the Mod's MCM menus

- Immersive HUD - Toggle HUD: X
- Predator Vision - Hunter's Nightvision: V
- Predator Vision - Hunter's Predator Vision: H
- Simple Horse - Horse Whistle: Y
- The Ultimate Dodge Mod - Dodge: Ctrl **Note to change this keybind you want to rebind the Sneak key in Skyrim Settings > Controls**
- The Ultimate Dodge Mod - Change Dodging Style: G (This changes between side stepping and rolling) **Note your character may be stuck in the air the first time you dodge. Pressing this will fix it**
- Classical Lichdom - Death Grip/Staff Equip Key: C

### Ultrawide Options

If you have an ultrawide monitor (21:9), the UI will be off. You will want to reinstall Dear Diary with the widescreen option. Pick any options on the FOMOD you want but ensure Extended UI, More Informative Console and Morehud is ticked.
You will also want to install the SkyHud - High Resolution Widescreen Fix from [here](https://www.nexusmods.com/skyrimspecialedition/mods/1778/?).

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

### Zoomed in Display

This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

- Set the display scaling back to 100% in the Screen Resolution Settings for Windows
- Edit the mod SSE Display Tweaks.
  - Under `[Render]`
    - Set Fullscreen to `True`
    - Set Borderless to `False`

### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- jdsmith2816 - for incredible help with getting mods working/patches/navmesh help
- DarkladyLexy for her consistency patches which I have used and modified upon as well as her colleciton of NPC overhauls which look amazing
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/ixanza/equanimity/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
