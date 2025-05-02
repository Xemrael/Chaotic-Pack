[**BACK**](https://xemrael.github.io/Chaotic-Pack/)

# Chaotic Pack 1.1.1

- First ModPack Iteration

* * *

# Chaotic Pack 1.1.2

## Added

- Chunk sending - Optimizes chunk packet sending through sorting and distributing them over time.
- Client crafting - client-side utility which makes crafting UI's much more responsive through eliminating the server delay.
- Connectivity - Lightweight mod which solves several connection problems like Login-Timeouts, DecoderException, Packet size limits, Ghostblock issues
- Fix GPU memory leak - A mod that fixes some bugs which leak resources within GPU memory, causing issues like these:
    GL_OUT_OF_MEMORY
    GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT
    GL_INVALID_FRAMEBUFFER_OPERATION

- Better chunk loading - 
	Predicts player movement and pre-loads chunks in an area ahead of them asynchronously.
    Slightly increases chunk loading speed in general.
    Controls the vanilla chunkloading around the player by smartly adjusting the size to the player's movementspeed, reducing the server's load.

- AttributeFix - Minecraft uses an attribute system to handle many entity properties like max health, movement speed, and attack damage. While this system is very flexible Mojang has artifically limited many of these properties. This mod addresses this issue by significantly raising these limits to a reasonable range.

- Random Village Names - Not only the villagers deserve names.
- Healing Campfire - Healing Campfire creates an area around the campfire where players and/or passive mobs receive the regeneration effect in a configurable radius.
- Pet Names - minimalistic configurable mod which gives tamable baby animals a pre-defined name. 

- «Chunk Pregenerator - This is an admin only use. Creates Chunks with predifined settings to be faster in world generation. Not in use until I undesrtand all it does.»


## Readded

- BetterCompatibilityChecker - Gimmicky to solve the "Incorrect mod pack version"


## Updated

- moonlight-1.20-2.13.64-forge to moonlight-1.20-2.13.65-forge
- AdvancementPlaques-1.20.1-forge-1.6.7 to AdvancementPlaques-1.20.1-forge-1.6.9
- villagernames-1.20.1-8.1 to villagernames-1.20.1-8.2
- accessories-neoforge-1.0.0-beta.44+1.20.1 to accessories-neoforge-1.0.0-beta.45+1.20.1
- PeepingTom-forge-1.20.1-1.4 to PeepingTom-forge-1.20.1-1.5 - Still don't know what he is peeping at tho
- EnhancedVisuals_FORGE_v1.8.1_mc1.20.1 to EnhancedVisuals_FORGE_v1.8.2_mc1.20.1
- balm-forge-1.20.1-7.3.14-all to balm-forge-1.20.1-7.3.15-all
- polytone-1.20-3.2.6 to polytone-1.20-3.2.8
- collective-1.20.1-7.90 to collective-1.20.1-7.91
- born_in_chaos_[Forge]1.20.1_1.6.2_chilling-horror-event to born_in_chaos_[Forge]1.20.1_1.6.3
- AmbientSounds_FORGE_v6.1.4_mc1.20.1 to AmbientSounds_FORGE_v6.1.6_mc1.20.1
- betterchunkloading-1.20.1-5.2 to betterchunkloading-1.20.1-5.3


## Removed

- BetterVanillaBuilding_Overlays - This resource pack is intended to use with another of the same kind, was being buggy and halting performance, removed unless the resourcepack BetterVanilla gets interesting

* * *

# Chaotic Pack 1.1.2_1


## Added
\\\\\\\\\\\\\\\\\\


## Readded
\\\\\\\\\\\\\\\\\\


## Updated

- Forge to version 47.3.33
- Lodestone to version 1.6.4.1
- Accessories to version 1.0.0-beta.46
- Connectivity to version 7.0
- Balm to version 7.3.18
- Collective to version 7.93
- Better Chunk Loading to version 5.4
- Moonlight lib to version 2.13.69
- Waystones to version 14.1.10


## Changed

- View Distance of the server reduced to 20 chunks from 24 (default is 10)
- Simulation Distance of the server reduced to 12 from 16 chunks (default is 10)
- Removed SpawnProtection (keep in mind theres still one single block protected no matter what, still this should help)
- Deleted and cleaned some .config files


## Removed

- SereneSeasonsExtended - Massive TPS losses, mod not being updated by creator.
- The snow removal after snowstorms caused by the mod Weather2 if it ocurred in a biome where snow is not common, specially in a cold season, won't happen - still pending of testing
- Time of day and night changes depending of the season are vanilla again.

- The mod HourGlass was a dependancy, but I chose to maintain it seen that it has some good quality of life changes, such as no need to all sleep to make time pass faster.


## Known issues

- Tough as nails mod - Drinking water by hand is not working - believe to be a mod related bug/issue
- Weather2 - Shaders are not working correctly with how the mod changes the particles, specially with snowstorms
- Tough As Nails: A Curios Expansion - The slot for insulation pads appears to be broken, will be fixed next patch

* * *

# Chaotic Pack 1.1.3 - changelog versão portuguesa?

## Adicionado

- Sodium/Embeddium Options Mod Compat - adds Sodium video settings for various rendering-related mods that don't have them, using Sodium Options API.
- Sodium/Embeddium Extras - adds a lot of features to Sodium (and Embeddium on older versions) to improve the experience and performance.
- Alguns destes novos mods novos, incluindo os atuais que substituiem o optifine em questão de performance, ainda vão estar em revisão para garantir que não se atropelam, embora um deles já faça o mesmo que outro (Rubidium Extra, ver Problemas conhecidos no fim)


## Readicionado
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Actualizado

- alltheleaks-0.1.2-beta+1.20.1-forge.jar - Maioritariamente fixes
- Better villages 3.3.0
	"Banners, item frames, and armor stands (and other similar blocks) have been reduced or removed to improve performance. A future update will further enhance performance by optimizing each houses with well-defined parameters.
	Increased separation distances and spacing to prevent villages from being too close to each other! Additionally, a configuration option has been added, allowing you to adjust these parameters yourself. If you're using other mods that provide similar functionality, an option is available to disable our configuration and let the other mod take over. By default, our configuration is applied. This has been tested with various mods. If you encounter any issues, please contact us so we can resolve the problem quickly!"
- entityculling-forge-1.7.3 - Fixes
- fallingleaves-1.20.1-2.1.2.jar - sem changelog por parte do modcreator
- ImmediatelyFast-Forge-1.5.0+1.20.4.jar
    "Made horse armor layering fix compatible with modded horse armor
    Added mechanism to allow resource packs with modified core shaders to declare compatible features
    Changed the versioning of ImmediatelyFast. The minor version is now incremented with every Minecraft update. The patch version is incremented with every ImmediatelyFast release. This aims to group all releases for a specific Minecraft version together. It also allows for more frequent releases because I can do a release for a single Minecraft version instead having to accumulate enough changes to justify a release for all supported versions."
- PeepingTom-forge-1.20.1-1.6.jar - "Increased Spawnrate"
- rightclickharvest-forge-4.5.3+1.20.1.jar - "Backport latest versions to 1.20.1!"
- connectivity-1.20.1-7.1.jar - Fixes
- SereneSeasons-forge-1.20.1-9.1.0.1.jar
	"Backport of add year_round_crops Block and Item Tags, and Fix Forge Logo not showing up (#532)
    Backport of add year_round_crops Block and Item Tags
    Fix Logo not displaying on Forge
    Build Updates
    Push Loom to 1.10"
- smoothchunk-1.20.1-4.1.jar - "Reduced vanilla lag on saving by skipping protochunk saving"
- voicechat-forge-1.20.1-2.5.28.jar
    "Save username cache asynchronously
    Only store cached usernames that are necessary
    Fixed issues with config reading
    Fixed audio devices containing unicode characters not saving properly in some cases
    Updated Chinese Simplified translation
    Fixed create group screen text field size
    Fixed join group password screen text field size
    Added Persian translation"
- soul-fire-d-forge-1.20.1-4.0.11.jar - "Add Korean localization."
- waystones-forge-1.20.1-14.1.11.jar
    "Moved JourneyMap waypoints two blocks up so you don't end up inside the waystone if you use JourneyMap's teleport feature
    Fixed sorting not working correctly when you have more than 128 waystones activated"
- watut-forge-1.20.1-1.2.3.jar - os ultimos changelogs foram fixes, a versão 1.2.0 introduziu uma nova gui dinamica
    "New dynamic gui support for all guis including almost all modded guis.
    See full detail of the open gui, getting updates twice a second
    See items transferring between player and the open container with a visual of the item itself moving between them
    Extensive set of configs to tweak it to your liking, with some new server side configs that are synced to clients.
    Various bugfixes
    Fix incompatibility with Better Ping Display that caused crashes."
	
- Better-Leaves-9.1.zip - Fixes e compatibility para outros mods


## Mudanças

- As versões do modpack passam a ter uma letra no fim se houver um hotfix em vez de underscore e mais um número. A versão vai tentar seguir o padrão de no primeiro ser a "Major" - caso haja uma grande mudança no modpack, segundo - mudanças, remover ou adicionar novos mods, terceiro - updates de mods e forge, assim como os fixes | Espero seguir este esquema :)
- Weather2 - Passa a usar o "Vanilla Weather", em vez de criar sistemas de tempestades, estas acontecem quando o server disser que "Chove".
- Para resolver a compatibilidade entre o mod ToughAsNails


## Removido
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
## Problemas conhecidos

- Embeddium/Rubidium - Nas settings a opção de search não está a funcionar
- Sodium/Embeddium Extras e Embeddium Extra, embora façam coisas diferentes ambos tem opção de mostrar fps, escolham qual delas preferem para ver nas opções
- Tough as nails mod - Para beber água a mão, shift + right click
- Weather2 - Já sabem os shaders podem meter o mod meio estranho, principalmente com as snowstorms
- Tough As Nails: A Curios Expansion - O slot para as insulation pads tem que ser usado manualmente, right click num insulation pad não o equipa, portanto arrastem :P
- Areas - Entrar numa vila não está a mostrar o nome gerado aleatoriamente no ecrã, mas a sign existe

* * *

# Chaotic Pack 1.2.0

## Added

- [Immersive Snow](https://www.curseforge.com/minecraft/mc-mods/immersive-snow)
    - Snow recalculation upon chunk loading. No more winter chunks in the summer!
    - Changing day cycle duration depending on the season. Longer nights in the winter.

- [Small Ships](https://www.curseforge.com/minecraft/mc-mods/small-ships)
    - Vanilla friendly Ships for Minecraft. Now with cannons!

- [AstikorCarts Redux](https://www.curseforge.com/minecraft/mc-mods/astikor-carts-redux)
    - Carts to various uses! Bring that pig with you wherever you go now!

- [Clear Despawn](https://www.curseforge.com/minecraft/mc-mods/clear-despawn)
    - Dropped items will now flash when they're about to despawn!

- [Inventory Profiles Next](https://www.curseforge.com/minecraft/mc-mods/inventory-profiles-next)
  - This mod will:
  - Help you keep your inventory sorted
  - Replace your quasi-broken tool
  - Dump everything in that chest with one click
  - Move the items you have that are also already in the chest                                         
  - Lock item slots in place so that sorting ignores them
  - Keep locked slots empty
  - Allow you to press R+C to set your shortcuts
  - Be pure client-side, so that it works everywhere

- [Jade](https://www.curseforge.com/minecraft/mc-mods/jade)
  - See what you are looking at, be it a mob, a block, whatever. Finally that cave dweller will show its life and weaknesses!

## Updated

- Some mods updated to latest versions


## Changed

- Weather2 - Working as Aesthetic mode only until it gets updated to resolve compatibility issues


## Removed

- [Inventory Sorter](https://www.curseforge.com/minecraft/mc-mods/inventory-sorter) made way for [Inventory Profiles Next](https://www.curseforge.com/minecraft/mc-mods/inventory-profiles-next)


## Known Issues

- Embeddium/Rubidium - Options Search Menu is not working
- Areas - Entering a village is not showing its name, bug from mod
- Motschen's Better Leaves 9.1 has issues with some textures from Immersive Weathering, recommended to use version 9.0 instead

* * *

# Chaotic Pack 1.2.0a

## Added

- none

## Updated

- Some mods updated to latest versions
	- THE UNDEAD REVAMPED
	- AmbientSounds 6
	- Jade 🔍
	- Just Enough Items
	- ModernFix
	- Polytone
	- SCP-939, With Many Voices - increased spawn rate
	- Serene Seasons
	- Simple Voice Chat
- [Thalassophobia](https://www.curseforge.com/minecraft/mc-mods/thalassophobia) has had a major update, new mobs and drops

## Changed

- SirenHead spawn adjusted, should still be rare
- Cave Dweller spawn adjusted to be less intrusive of an encounter

## Removed

- none

## Known Issues

- Embeddium/Rubidium - Options Search Menu is not working
- Areas - Entering a village is not showing its name, bug from mod
