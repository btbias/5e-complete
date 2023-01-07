# 5e Complete
[![Supported Foundry Versions](https://img.shields.io/endpoint?url=https://foundryshields.com/version?url=https://github.com/btbias/5e-complete/releases/latest/download/module.json)](#)
[![Total Downloads](https://img.shields.io/github/downloads/btbias/5e-complete/total?label=Total%20Downloads)](#)
[![Latest Release Download Count](https://img.shields.io/github/downloads/btbias/5e-complete/latest/total?label=Latest%20Downloads)](#)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-btbias-00B9FE?logo=kofi&color=blue)](https://ko-fi.com/btbias)

Welcome to the 5e Complete module for Foundry VTT! This module adds the classes, races, spells, and other resources that are missing from the 5e System Reference Document (SRD). With this module installed you'll have access to everything you need to run a complete 5th edition Dungeons & Dragons campaign within Foundry VTT.

## Installation
In Foundry's Install Module menu, copy the following link into the Manifest URL field:

```
https://github.com/btbias/5e-complete/releases/latest/download/module.json
```

## Features
5e Complete is a collection of compendiums that operate identically to the SRD compendiums. Simply open the compendium with the desired content, ex. **5e Classes**, and click an item to view it, or click and drag it to a character to apply it.

All classes and their subclasses leverage Foundry's built-in advancement tables. When you level up, you'll have features and spells granted by your class or subclass added to your character automatically.

Each item will have a Source value tied to the volume it came from, such as `TCE` for Tasha's Cauldron of Everything. Any items from 3rd-party sources will be marked with an asterisk (\*), such as `KCCC*` for Kibble's Compendium of Craft and Creation.

### Disclaimers
- This is a work in progress. Some content may be missing or have errors. Please submit a [new issue](https://github.com/btbias/5e-complete/issues) if you have any issues.
- The best method for including creature artwork has not been decided yet.

## Recommended Modules
5e Complete has been designed utilizing the following modules; it's recommended you use them, but they are not required:

### Visual Enhancements

In order of simplicity:
- [Dice So Nice](https://gitlab.com/riccisi/foundryvtt-dice-so-nice)
- [Tidy5e Sheet](https://github.com/sdenec/tidy5e-sheet)
  - To set Tidy5e as the default sheet, open the **5e Macros** compendium and run the `Tidy5e Default Sheet` macro.
- [JB2A](https://www.patreon.com/JB2A) with [Automated Animations](https://github.com/otigon/automated-jb2a-animations) and [Sequencer](https://github.com/fantasycalendar/FoundryVTT-Sequencer)
  - JB2A's discord server has a preset you can download for Automated Animations, highly recommended!
  - Not absolutely required, but JB2A patrons get access to a larger set of animated assets, and it's cheap.

### Automation &amp; Utility

In order of simplicity:
- [SmallTime](https://github.com/unsoluble/smalltime)
- [Roll Groups](https://github.com/krbz999/rollgroups)
- [Item Macro](https://github.com/sdenec/tidy5e-sheet)
  - Enable `Character Sheet Hook` in Item Macro's settings.
- [Wild Magic Surge 5e](https://github.com/johnnolan/wild-magic-surge-5e)
  - Open the **5e Roll Tables** compendium and add `Wild Magic Surge Table` and `Barbarian Wild Surge` to your local roll tables.
  - In Wild Magic Surge 5e's settings, change the values of `Roll Table Name` and `Path of Wild Magic Roll Table` to match the tables you just added. Also set `Auto Roll Table` to Auto Roll Table if you want surges to automatically roll.
- [Magic Items](https://gitlab.com/riccisi/foundryvtt-magic-items)
- [Dynamic Active Effects](https://gitlab.com/tposney/dae) with [Effective Transferal](https://github.com/GamerFlix/effective-transferral), [Warp Gate](https://github.com/trioderegion/warpgate), and [Times Up](https://gitlab.com/tposney/times-up)
  - If you want users to be able to automate their own effects, open `Permission Configuration` and allow Players to Configure Token Settings. WARNING: This will grant access to browsing your Foundry assets! A workaround is to promote players you trust to the Trusted Player role.

## Final Remarks
A special thanks goes to my friends that have helped get this compendium to where it is, and also a big thank you to [Zhell](https://github.com/krbz999?tab=repositories), [Honeybadger](https://ko-fi.com/badgerwerks), Freeze, Flix, and everyone else over on the [Foundry discord server](https://discord.gg/foundryvtt) for helping with the macros.