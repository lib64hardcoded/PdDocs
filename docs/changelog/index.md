# Changelog

## Commit changes to version 5


### 1.0.3 <small>Febuary 20, 2025</small> { id="1.0.3" }

#### added

- **The Demon Tower** dungeon has been completely restructured; it is now fully aligned with the official version. The dungeon benefits from RE-ENTRY.
- **The Devil’s Catacomb** dungeon has been entirely restructured, now being completely identical to the official version (all rooms included). The dungeon benefits from RE-ENTRY.
- **The Baroness’s Chamber** dungeon has been fully restructured; it is now mandatory to complete all quests in order to access the dungeon. The dungeon benefits from RE-ENTRY.
- **The Dragon Temple** has been completely restructured; moreover, it now includes both RX and RT versions, exactly as on the official server. The dungeon also benefits from the buffs and debuffs provided by the stones within the temple.
- **The Razador Fortress** has been entirely restructured and now includes both RX and RT versions, identical to the official version. The dungeon benefits from RE-ENTRY (ONLY WITH A PARTY).
- **The Nemere Tower** has been fully restructured. Access now requires a party that includes both a Ninja and a Shaman, as certain levels within the tower can only be cleared using their specific abilities to deal damage to stones or enemies. The dungeon benefits from RE-ENTRY.
- **The Ochao Temple** is now fully functional.
- **The Jotun Temple** is now fully functional.
- **The Meley Dungeon** has not been modified, as it was already functioning properly.
-  At the end of the **Hydra dungeon**, a portal now appears, allowing players to ascend to the Conqueror Level.
- Details regarding the **Sung-Mahi Tower** can be found below.
- All dungeons have their settings implemented at the source level, and the quest system is designed to be intuitively modifiable, ensuring ease of customization if needed.
- We have successfully completed the **Yohara** section that was available in version 5 Prodomo. As a result:
- All three **Conqueror** maps are now available, where the respective bosses, monsters, and Yohara stones spawn.
- Bonus effects now exist on the **Conqueror** maps, depending on the Yohara status you have developed.
- Random bonuses now apply to **Conqueror** items (**Random Sung-Ma bonuses**).
- You can now add **Conqueror** stones to gloves (currently in development).
- Character evolution can now be triggered directly from the Hydra dungeon. Once the mission is completed, a portal will appear, allowing teleportation directly to the Conqueror Totem, where you can upgrade your normal level to a Conqueror Level.
- **Conqueror-type** experience is now applied only within the Conqueror maps, regardless of the type of monster encountered. To facilitate character progression, the experience gained in Conqueror maps can now be obtained from any type of monster present in that specific map.
- With the completion of the Conqueror maps and evolution on Prodomo, the Sung-Mahi Tower now makes its appearance.
- The map includes all 50 available levels of Sung-Mahi.
- The map offers rewards to players who manage to climb as high as possible within the dungeon.
- The map features random buffs and debuffs, including Sung-Ma bonuses.
- The map includes all Sung-Mahi monsters, along with their respective resistances.
- The **Biologist system** has been completely reworked in version 5 of Prodomo. As a result:
- Upon reaching level 30, a special quest will be marked in the game's quest table.
- Once you reach the **Biologist**, you can begin assisting him by collecting and delivering all the required materials.
- The **Biologist** now allows you to choose your bonus from the level 92/94 quest rewards.
- A scroll is now available for resetting the level 92/94 quest.
- Bonuses, quests, and quest requirements are now much easier to modify, and changes reload instantly without requiring a server restart.
- It is no longer possible to deliver quest items directly from the quest table; you must be physically near the **Biologist** to hand over the required item. However, a teleport button has been added, allowing you to teleport to him from any location (except dungeons).
- The **previous optimization** system has been **removed** and replaced with a new optimization in version 5 of Prodomo.
- The **new optimization** significantly reduces RAM usage by the client.
- The **new optimization** is faster and more stable, ensuring better performance for both new and older computers.
- The **new optimization** efficiently stores GR2 files in memory, enabling faster and more efficient loading without overloading the player's RAM.
- A new **Battle Pass system** has been added, featuring three new functions: Free, Premium, and Skip Mission.
- The missions are categorized into three types: Daily, Weekly, and Monthly.
- Completing missions grants EXP, which unlocks both Free and Premium rewards.
- The missions are easily configurable.


#### removed

- The previous optimization system has been removed and replaced with a new one.
- The old Biologist system has been removed and replaced with a new version.
- DumpProto has been replaced with a faster and more stable version.
- The Solo & Global Rewards system has been removed.
- The Bonus Set Item system has been removed and replaced.
- The Multi-Farm Block system has been removed.
- The old Cube Renewal system has been removed and replaced with a refactored version.
- The previous Render-Target system has been removed.
- The Loot-Filter system has been removed and will be replaced with a simpler and more organized version.
- The Pin Code system has been completely removed and replaced with inventory protection; additionally,
- Sentry can be added as an extra security measure.
- Removed unused item icons, client icons, client images.
- Removed new-costumes / items.. from pc/pc2. (clean-up)
- Removed trivia-event (clean-up)
- Removed unused systems (clean-up | commondefines.h and non-defined ones)
- Removed textureset / terrain /  map / season / monster / npc (unused textures).


#### fixed

- The old version occasionally caused random client crashes, either at unexpected moments or when launching the client.
- We learn from our mistakes, and recently, we have had both the luck and misfortune of having to fix numerous optimization and system-related issues.
- Fixes have been applied to the Offline Shop system.
- Fixes have been implemented for the Shop / Shopex system.
- Various game functions have been modified.
- The client has been cleaned of outdated code and unused systems.
- Unused old effects have been removed from the client.
- All existing quests on the server have been reorganized, cleaned, and reverified; they can now be compiled using the 777 command in the Prodomo menu in PuTTy.
- Unnecessary images and .dds files have been deleted.
- The multi-language system has been fixed to ensure blocked languages are no longer visible in chat/shout.
- The highlight feature in the special inventory system has been fixed (previously, activating a potion caused the highlight to appear on all pages, regardless of their nature).
- Additional fixes and improvements related to server/client optimization and performance.
- Additional fixes and improvements related to QoL (Quality of Life).
- All system functionality issues have been fully resolved, ensuring that you can confidently use all available systems in version 5 of Prodomo.
- By running Asan, we identified and fixed multiple memory leaks and issues, both in the binary and server components.
- Fixed Talisman & Glove & Aura equip slot
- Fixed Event Manager not displaying events
- Fixed not showing boss icon on minimap & above head
- Fixed alchemy bonus changer & add
- Fixed duplications based on extern py loader
- Fixed DumpProto LZO error based on latest VS update.
- Fixed Sash error where you cannot combine two sashes
- Fixed Chest Drop visual bug where in spcial inventory the shortcut was not displayed.
- conf.txt is now conf.json
- blend.txt is now blend.json
- CONFIG (server/game) is now .json
- atlasinfo.txt is now .json
- group.txt is now .json
- group_group.txt is now .json
- item_desc / item_list / item_scale / sash_scale / aura_scale .txt are now .json
- race_height.txt is now .json
- shop_deco.txt is now .json
- item_names / mob_names are now .json
- npclist.txt is now .json
- fishing.txt is now .json




### 1.0.2 <small>September 1, 2024</small> { id="1.0.2" }

#### added

- New Achievement System,
- New Special Inventory System,
- New Multi Refine system,
- New Switchbot with addons for premium users,
- New global & individual rewards for users,
- New dungeons: Sung-Mahi, Queen Nethis, Alastor (White Dragon),
- New Yohara Expansion updates: Sung-Mahi curse,
- New Yohara Expansion updates: Yohara maps & mobs,
- New Yohara Expansion updates: Yohara missions
- New Battlepass,
- New function for inventory: Toggle and search items,
- World Boss,
- Event Manager refactorized with new events and new UI,
- Buffi system.



#### removed

- Old optimisation,
- Old unused functions,
- Old unused systems.

#### fixed

- Login Patcher - updated m2socket for web transfer,
- Special Inventory - rewritten UseInventoryEx,
- Switchbot code - p2p transfer rewritten,
- Offflineshop kashmir bundle,
- UpdateFollowAI() function has been rewritten,
- More systems moved to x64.


### 1.0.1 <small>July 29, 2024</small> { id="1.0.1" }

#### added

- New optimisation.
- New pick-up filter.

#### removed

- Old optimisation.
- Old unused functions. 

#### fixed

- Ranking-buttons hover.
- Offlineshop p2p errors.
- Dungeon-info errors generated by "setinsiderender"

### 1.0.0 <small>July 29, 2024</small> { id="1.0.0" }

### fixed
- Game-options crash.

