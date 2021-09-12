# Payday 2: Useful Mods
<img src="https://i.imgur.com/Ka3L5F6.png" width="100%" />

Payday 2 was released in 2013 and is now eight years old.
In the eight years time far more than thousands of mods have been released. This shows that Payday 2 has a really great modding community, there are really many good developers and mods that are updated regularly.

But I also found, in my opinion, real "trash mods". If you're a waifu or a little memelord, you'll be happy there safely. If you enjoy it, then go for it. But this quickly makes it confusing in the mod workshops and you lose the overview. 

That's why I spent hours searching relevant Payday 2 mod forums, communities and workshops for quality and useful mods.

### Updates and Suggestions

I do my best to keep the list regularly up to date. 
Old mods that don't work anymore will be removed from the list. <br>If you have found a cool and useful mod for Payday 2, feel free to suggest it to me. 

# Table of Contents

 - [Clientside Mods vs Lua Mods](#Clientside-Mods-vs-Lua-Mods)
 - [Requirements](#Requirements)
     - [SuperBLT](#SuperBLT)
 - [Other Libaries and Frameworks](#Other-Libaries-and-Frameworks)
     - [BeardLib](#BeardLib)
     - [HopLib](#HopLib)
     - [WeaponLib and WeaponLib Fixes](#WeaponLib-and-WeaponLib-Fixes)
 - [Installation](#Installation)
     - [Clientside Mods](#Clientside-Mods-mod_overrides)
     - [Lua Mods](#Lua-Mods-mods)
 - [Mods](#Mods)
     - [HUD](#HUD)
     - [Quality of Life](#Quality-of-Life)
     - [Gameplay Changing](#Gameplay-Changing)

# Clientside Mods vs Lua Mods	
Not all mods are created equal. The difference is made between client-side mods and Lua-based mods.<br>
Thanks to the [Payday Fandom Wiki](https://payday.fandom.com/wiki/) for the detailed summary below.

https://payday.fandom.com/wiki/PAYDAY_2_mods_and_tools

### Clientside Mods

> Client-side modifications (/mod_override) usually do not cause any problems in multiplayer. They usually have little impact on the game experience of other players and are unnoticeable to other players.
> 
> The two most common types of client-side mods are texture and sound mods. They change textures or sounds of various objects, characters or the environment. This only affects the mod user's experience, even if they are the host.
> 
> Client-side modifications are unofficially supported by Overkill through the mod_override system. This allows the game to load unpacked assets from a special folder instead of archived files. This has made it much easier to use mods, although there are restrictions on the types of files that can be loaded using this system to prevent malicious behavior.

### Lua Mods

> Lua mods use a "hook" .dll (or .so for Linux users) and associated files to insert, overwrite, or append code to the Lua scripts used by the game itself while the game is running. 
> 
> Lua mods affect the structure of the game and range from HUD mods that display additional information (e.g., enemy health and damage), to small quality of life changes (e.g., the ability to press a button once instead of having to hold it down during an interaction), to full game overhauls (usually aimed at fixing balance and difficulty issues), and cheats (e.g., spawning loot bags or invulnerability).
>
>It is important to note that most Lua-based modifications are not considered cheats. As of February 2016, game-changing mods, including rebalance mods, are tolerated by Overkill as long as they do not amount to blatant cheating (e.g. invulnerability, free money, experience, or achievements, etc.) and are only used in single-player mode or with the consent of other players in your lobby. Nevertheless, caution is advised, as a poorly written or outdated script can easily cause the game to crash or cause serious glitches.

# Requirements

As explained above, there is a hookloader for Lua-based mods. 

### SuperBLT
[SuperBLT](https://superblt.znix.xyz/) is a fork of the BLT mod-loading hook for PAYDAY 2, with a number of major improvements, such as a cross-platform audio API and the ability to alter any base-game XML file without the hassle of modifying bundle files (greatly alleviating the need for Bundle Modder). SuperBLT is mandatory to use Lua-based mods.

# Other Libaries and Frameworks

Additionally, there are other Payday 2 libaries and frameworks that are needed for certain mods.

### BeardLib
[BeardLib](https://github.com/simon-wh/PAYDAY-2-BeardLib/) is a large library that assists in mod creation.
The purpose of BeardLib is to provide tools for modders to create quality and more advanced mods without repetitive implementation of basic or advanced features.

-   Script File Manipulation.
-   Custom maps
-   Easy ability to add content. Such as masks, melee weapons, weapon mods, suits, gloves, etc
-   Modules system

### HopLib
[HopLib](https://github.com/segabl/pd2-hoplib) is a collection of utilities and functions that are needed if you want to use mods from [Hoppip](https://modworkshop.net/user/3972).

### WeaponLib and WeaponLib Fixes
[WeaponLib](https://modworkshop.net/mod/24177) is a mod which aims to provide a compilation of utilities and other helpful things for custom weapon creators to use in their own mods.

[WeaponLib Fixes](https://modworkshop.net/mod/29987) is a community-developed fix that addresses known bugs in WeaponLib.

# Installation

### Clientside Mods (/assets/mod_overrides)
Clientside mods are stored in the Payday 2 installation directory under `/assets/mod_overrides`. 

### Lua Mods (/mods)
Lua mods are stored in the Payday 2 installation directory under `/mods`.

# Mods
I divide the mods into different categories.

- [HUD](#HUD) mods add useful information to your user interface.
- [Quality of Life](#Quality-of-Life) mods make the game a lot more comfortable without changing the core gameplay.
- [Gameplay Changing](#Gameplay-Changing) mods, as the name suggests, will change your gameplay experience by adding new or old features.

### HUD

| Mod | Description | Require|
| -------- | -------- | -------- |
| [WolfHUD](https://github.com/Kamikaze94/WolfHUD) | WolfHUD is probably the most famous HUD mod for Payday 2. It includes many individual HUD mods and has gradually become an all-in-one HUD solution for the community | SuperBLT<br>BeardLib
| [HoloUI](https://modworkshop.net/mod/12501) | HoloUI is a UI mod that changes most of the UI design of the game to look more flat and "modern". It's also highly customizable! | SuperBLT<br>BeardLib
| [PDTH HUD Reborn](https://modworkshop.net/mod/19900) | PDTH HUD Reborn brings the classic HUD from Payday: The Heist to Payday 2. | SuperBLT<br>BeardLib
| [HEV HUD](https://modworkshop.net/mod/27954) | A recreation of the HUD from Valve's Half-Life 2 (2004).This HUD is extremely unfinished, but due to time constraints, development is greatly slowed, so I would prefer to let people try it out in the meantime. It's technically usable and should be stable. | SuperBLT<br>BeardLib
| [Hotline Miami HUD](https://modworkshop.net/mod/27294) | The Hotline Miami HUD brings Payday 2 back to the 80s. True to the Hotline Miami vibes. | SuperBLT<br>BeardLib
| [Kill Feed](https://modworkshop.net/mod/20055) | This mod provides you with a fully customizable kill feed. | SuperBLT<br>HopLib
| [Item Hunter](https://modworkshop.net/mod/26200) | This mod adds waypoints to items for collectible achievements/trophies. The mod is activated via a keybind and can be toggled on/off. | SuperBLT
