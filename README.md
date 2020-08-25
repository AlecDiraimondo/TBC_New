# Fork targets

This fork's focus is mainly to port back the removed scripts and eventually do more optimizations on the current code.
If you have played TBC and you know how stuff works - feel free to give it a test and update us with bugs.
Any PRs are welcome.

Current progress:


> Arenas

[ ] Ring of Trials

[ ] Circle of Blood

[ ] Ruins of Lordaeron


> Battlegrounds 

[ ] Warsong Gulch

[ ] Arathi Basin

[ ] Alterac Valley

[ ] Eye of the Storm


> Dungeons


[ ] Hellfire Ramparts	

[ ] Blood Furnace

[ ] Slave Pens	

[ ] Underbog	

[ ] Mana-Tombs	

[ ] Auchenai Crypts	

[ ] Escape from Durnholde Keep	

[ ] Sethekk Halls	

[ ] Shadow Labyrinth	

[ ] Shattered Halls	

[ ] The Botanica	

[ ] The Mechanar	

[ ] The Steamvault	

[ ] Magisters' Terrace	 

[ ] Opening of the Dark Portal	

[ ] The Arcatraz	  


> Raids


[ ] Karazhan

[ ] Gruul's Lair

[ ] Magtheridon's Lair

[ ] Zul'Aman

[ ] Serpentshrine Cavern

[ ] Tempest Keep: The Eye

[ ] Battle for Mount Hyjal

[x] Black Temple

[x] Sunwell Plateau



# Sunstrider-related

*_Please note_*: this is a legacy version of the project which is no longer supported or developed. All development is now private.
If you'd like to work on the project or ask questions, join our Discord!

https://discordapp.com/invite/wGzmdXY

Sunstrider is a WoW 2.4.3 emulator.
Development started in 2009 from a [trinitycore1](https://bitbucket.org/KPsN/trinitycore-243) fork and the core was being used on WoWMania, a french server. It was then rebranded to "Windrunner", where it was continuously developed for about 5 years. You can find the last Windrunner version [here](https://github.com/kelno/windrunner). Starting with our departure from WoWMania the core was renamed to Sunstrider.

## Installation

* [Windows](/doc/install_win.md)
* [Linux](/doc/install_linux.md)
 
## Main features

* Close to TrinityCore  
You can think of this core as TrinityCore for TBC.  
Over the years all major systems were rewritten using TC as a base. This allows us to continuously make use of the TrinityCore's recent developments and have a dev-friendly core using the well known infrastructure of TC. 
When a system has been imported from TC, differences (either improvements or TBC adaptations) from original TC are usually highlighted by comments.
* Automated testing system  
Our star feature! Mainly used for spells at the moment.
* [Continuous integration](https://travis-ci.org/sunstrider/sunstrider-core)  
Including tests results!
* Dynamic spawn system (see [here](https://github.com/TrinityCore/TrinityCore/pull/19056))
* Scripts and tests can be compiled in dynamic libraries and reloaded on runtime (see [here](https://trinitycore.atlassian.net/wiki/spaces/tc/pages/18874377/Using+the+script+hotswapping+system))
* Improved VMaps and MMaps  
Up to date with TC with some fixes of our own as well as some from Nostalrius.
* Spells
    * "A more powerful spell is active" mechanic
    * Binary spells
    * Heartbeat resist
    * Custom blinks and charges
    * A LOT of misc fixes in addition to TC systems
* EventAI has been dropped in favor of SmartAI  
Furthermore SmartAI has been used extensively in the last years of development on Sunstrider and has received various fixes and extensions on our part.
* Reworked map update logic  
Instances and battlegrounds may be updated multiple times while continents are updated, making instances/bgs less sensible to lag when the server is under high load.
* Creature soft evade on inaccessible targets
* Movemaps on transports!
* Years of service
A lot of improvements were made when the server was live:
* Large debugged quest base  
A LOT of quests of all levels have been fixed, so we're benefiting from a good base on quests.
* Good instance and boss scripts  
Most high level instance scripts are decent seeing other BC server ones (but still need work). Black temple and Sunwell scripts have been the most worked on and are close to perfect.
* A lot of abuse prevention fixes  
* Most world creatures use correct spells and have correct equipment

## Additional features (non blizzlike)

* [Playerbots](https://github.com/ike3/mangosbot)
* Fully reworked stealth mechanics
* Transports including static npcs (ship crew), purely cosmectic. Selling and combat is disabled for them.
* Dynamic PvP titles system depending on player rank in arena ladder (Disabled by default)
* ArenaSpectator (Not tested for a long while, we'll probably just trash it)
* Duel zone
* Pack58 item packs


And much more.
