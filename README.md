# Magus Class in FoundryVTT (WIP)
This is a work in progress containing the base Magus class by Laserllama and four subclasses (Blade Dancer, Spellbreaker, Spellsword, Arcane Archer)
It can imported into your game by using Mana's Compendium Importer: https://foundryvtt.com/packages/mkah-compendium-importer
The class uses a few custom icons, which you need to place in your Data folder, on the same level as your systems/worlds etc. folders. Put the custom-icons folder into it in order to have all the icons display properly.

Requires:
* Mana's Compendium Importer
* Dynamic Active Effects

## Notable features
* Automatic Level Progression features granted
* Functioning Subclass Support
* Subclass spells are automatically added
* Active Effects that can be applied for Blade Dance and other similar abilities
  * These are currently still work in progress and most likely will need to be applied by the GM
* All Martial Exploits from Laserllama's Alternate Fighter that the Spellsword can learn, bound to a "Martial Exploits" consumable resource. Rolls inside of the descriptions of these adjust automatically with levels and increasing ability modifiers.
* Actions to display your Spellstrike, Shunting things from your Arcane Armory, empowering your spells, and more.
* New and Revised spells from the Subclass Spell lists from Laserllama's Compendium of Spells (Steel Wind Strike, and more)

## Caveats
* Most active Effects currently have no duration and will need to be toggled manually
* Some damage rolls will need to be adjusted on the fly because I don't know how to handle some of the conditional damage bonuses that Exploits or other features grant
* Swapping Fighting Styles / Martial Exploits needs to be done manually, only the new ones are added via level progression
* Not all spells in the Magus spell list are yet part of this compendium, especially not the homebrew ones
* Most fighting styles assume that you fulfill the requirements for their bonuses all the time, and will need to be disabled if you don't
