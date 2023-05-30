---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.1.0
Space Shuttle Engines (SSE)
created: 05 Aug 2022
updated: 29 May 2023

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->

## [Space Shuttle Engines (SSE)][mod]

[Home](./index.md)

[Space Shuttle Engines (SSE)](https://curseforge.com/kerbal/ksp-mods/SpaceShuttleEngines) adds thirty-six (36) space shuttle themed parts by [Klockheed Martian Ltd (KML)](https://www.curseforge.com/kerbal/ksp-mods/KlockheedMartianLtd)

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `KlockheedMartian` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KlockheedMartian/SpaceShuttleEngines`
* Extract the package's `KlockheedMartian` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KlockheedMartian` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/KlockheedMartian/SpaceShuttleEngines`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/KlockheedMartian/SpaceShuttleEngines`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KlockheedMartian/SpaceShuttleEngines`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [KlockheedMartian]
      + [KlockheedMartianLtd][kml]
        + [Agencies]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        ...
      + [SpaceShuttleEngines][mod]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [FX]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-ND-4.0.txt
        * changelog.md
        * ManualInstallation.htm
        * readme.htm
        * SpaceShuttleEngines.version
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Klockheed Martian Ltd (KML)][KML]

[KML]: https://www.curseforge.com/kerbal/ksp-mods/KlockheedMartianLtd "Klockheed Martian (KM)"

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/SpaceShuttleEngiens "Space Shuttle Engines (SSE)"
