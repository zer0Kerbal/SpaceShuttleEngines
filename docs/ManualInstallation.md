---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Space Shuttle Engines (SSE)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Space Shuttle Engines (SSE)

[Home](./index.md)

Space Shuttle Engine (SSE) pack by Klockheed Martian Engine Manufacturer - for Kerbal Space Program.

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
      + [KlockheedMartianLtd]
        + [Agencies]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        ...
      + [SpaceShuttleEngines]
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
        * changelog.md
        * CC-BY-ND-4.0.txt
        * ManualInstallation.htm
        * readme.htm
        * SpaceShuttleEngines.version
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Klockheed Martian Ltd (KM/L)][KML]

[KML]: https://forum.kerbalspaceprogram.com/index.php?/topic/207651-*/ "Klockheed Martian (KM)"
