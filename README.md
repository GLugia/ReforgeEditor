# ReforgeEditor
Better Reforges is a configurable mod that changes what reforges every item can get based on their original stats.
As well as a personal QoL option to make every tool as fast as possible while maintaining their power. This option removes existing prefixes from all tools.

# Update
* If you have any issues please message me via Discord @Lulu#1628
* I am in the following servers if you don't want to add me: tModLoader, Calamity, Thorium, Anarchist

# !! WARNING !!
* Expect this mod to remove prefixes from existing items. Even if you are only updating.
* Enabling the "Max Speed Tools" config removes prefixes from all tools and disallows reforging them.

# TODO
* Heavily increase the price of reforging
* Remove the ability for items to gain a prefix on creation
* Finally add my own custom prefixes to help weaker classes a bit

# Changelog
* 3.9:
  * Improved loading time
  * Reduced RAM usage by about 30%
  * Fixed an issue with attempting to load prefixes for walls
  * Fixed a bug causing Terraria to stop loading
* 3.8:
  * Added a config option to remove prefixes from items when they are created. Defaults to true.
  * Cost of reforging is now configurable. Defaults to 3x.
    * This is only temporary while I figure out some math involving the amount of removed prefixes compared to the average cost of reforging the best prefix
* 3.7:
  * Doubled the price of reforging items that already have a prefix
  * Fixed an bug where non-sword melee weapons could recieve melee prefixes (ie yoyos getting Legendary)
* 3.6:
  * Fixed an bug where Max Speed Tools was not properly set on items
  * Fixed a crash
* 3.5:
  * Now normalizes valid prefix stat changes. This fixes a number of items not having prefixes to roll.
    * Due to this, the default Minimum Tool Threshold has been raised to 0.7
* 3.4
  * Fixed a crash caused by certain mods calling GlobalItem.ChoosePrefix when loading
  * Disabled prefixes for "unlimited"/"endless" items that count as ammo or fire projectiles
* 3.3
  * Fixed the icon being too small
* 3.2
  * Added a dummy github homepage
  * Added an icon
* 3.0:
  * Completely revamped how prefixes are chosen for items. Each item is now individually tested with each valid prefix.
  * Fully fleshed out mod support. Should now work with any mod's prefixes and for any modded item. As a side note, any ModPrefix that applies to accessories is immediately assumed to be Tier 4.  Thus they will always be rollable assuming the config allows it.
  * Made every config change require a reload. Sadly there's no getting around this due to the way I've cached prefixes. Due to this possibly being an issue, I have pre-set config values to what I think should be a good threshold for the "best" prefixes.  Keep in mind this threshold is just a default and you are free to change it if need be.
  * Fixed a bug where max speed tools would not be properly reset.
  * Fixed a bug where max speed tools would lose their favoriting if they somehow gained a prefix.
  * Fixed a bug where max speed tools could gain a prefix via reforging.
* 2.1:
  * Added mod support for Calamity's Rogue class
  * Added mod support for Thorium's Bard class
  * Added mod support for Anarchist's Dark Artist class
* 2.0:
  * Fixed an issue with magic weapons getting incorrect prefixes
* 1.9:
  * Now forces a reload when toggling 'Fastest Tools'
  * Fixed an issue with summon items having duplicate prefixes in their pool
  * Fixed an issue with items not rolling for certain prefixes
* 1.8:
  * Fixed an issue with inifnite ammo sources gaining prefixes
* 1.7:
  * Fixed an issue with stackable weapons gaining prefixes
  * Fixed an bug where some summon weapons couldn't recieve knockback prefixes
* 1.6:
  * Fixed a crash
* 1.5:
  * Small refactor
* 1.4:
  * Fixed weapons getting the wrong 'quick' prefix
* 1.3:
  * Ok actually fixed accessories getting the wrong 'quick' this time
* 1.2:
  * Fixed accessories getting the wrong 'quick' prefix
* 1.1:
  * Fixed tools getting prefixes while max speed config is active
* 1.0:
  * Initial release
