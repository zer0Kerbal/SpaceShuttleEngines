---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- 
hdr-changelog.md v1.0.0.0
Space Shuttle Engines (SSE)
created: 13 May 2022
updated:
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  
  
| modName    | Space Shuttle Engines (SSE)                                       |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-ND-4.0                                                      |
| author     | dtobi, sarbian and zer0Kerbal                                     |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209177-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/SpaceShuttleEngines)    |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/SpaceShuttleEngines)  |
| spacedock  | (https://spacedock.info/mod/3009)                                 |
| ckan       | SpaceShuttleEngines                                               |

## Version 2.3.99.1-prerelease - `<Thank you dtobi and sarbian>` edition

* Released
  * 04 Nov 2022
  * for Kerbal Space Program 1.12.4
  * by zer0Kerbal

### Summary 2.3.99.1

* Phase II pass:
  * localization complete
  * parts pass complete (including tanks)
* <ghostparts.cfg> is provided for now for testing. This file will not active for version 2.4.0.0-release.
* Can now search for `sse` or `km` in the editor search bar to find all parts in this pack.
* DRAG_CUBES

### Changes 2.3.99.1

This is the next in a series of updates to this addon. Each update will update some of the parts and patches so that instead of one massive update I can update the addon in a more manageable way.

### Parts 2.3.99.1

* Rename part files to match part names
* Rename parts to match naming scheme
* corrected BulkheadProfiles for 1.875m tanks from size1 to size1p5
* Inital pass on all remaining parts completed
  * sse-tank-bottom-3
  * sse-tank-bottom-15
  * sse-tank-mid-1
  * sse-tank-mid-2
  * sse-tank-mid-3
  * sse-tank-mid-15
  * sse-tank-mid-small-1
  * sse-tank-mid-small-2
  * sse-tank-mid-small-3
  * sse-tank-mid-small-15
  * sse-tank-top-1
  * sse-tank-top-2
  * sse-tank-top-3
  * sse-tank-top-15
  * sse-tank-bottom-1
  * sse-tank-bottom-2

### Compatibility 2.3.99.1

* Move out from part.cfg's
* Create <KlockheadMartian.cfg>
  * KM_Stager into <KlockheadMartian.cfg>
  * KM_PreLaunchEffect_SmkS into <KlockheadMartian.cfg>

### Asset Updates 2.3.99.1

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * Rename model files to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * remove duplicates textures/models
    * <cloud.dds> 22kb
    * <orange-top-COMPLETE.dds> 342kb
    * <orange-mid-large-complete.dds> 342kb
    * <orange-top-COMPLETE.dds> 342kb
    * <orange-top.dds> 683kb
    * <orange-top-bump_NRM.dds> 1.366mb
    * <orange-top-bump_NRM.dds> 1.366mb
    * total reduction of ~7.944mb
      * current total: 4.35 mb
      * previous total: 3.594mb
* relocate part.cfg to Parts/Tanks/
* closes #55 - Asset Updates

### docs/ 2.3.99.1

* Move
  * @thumbs to docs/
* Update
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Part-Catalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* updates #56 - docs/

### Localization 2.3.99.1

* Update
  * [SpaceShuttleEngines.cfg] v1.0.1.0
    * adds localized tags to parts
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
  * updates #17 - Localization - Master
  * closes #18 - English <us-en.cfg>
  * closes #35 - Part Localization

### Status 2.3.99.1

* Issues
  * closes #63 - Space Shuttle Engines (SSE) 2.3.99.1-prerelease `<Thank you dtobi and sarbian>`
  * closes #64 - 2.3.99.1 Verify Legal Mumbo Jumbo
  * closes #65 - 2.3.99.1 Update Documentation
  * closes #66 - 2.3.99.1 Update Social Media

---

## Version 2.3.99.0-adoption - `<T-Minus>` edition

* 05 Aug 2022
* Released for KSP 1.12.3

### Summary 2.3.99.0

* Initial
  * localization pass
  * parts pass complete (except for tanks)
* Not ready yet for live saves, although most game breaking changes are made.
* <ghostparts.cfg> is provided for now for testing. This file will not active for version 2.4.0.0-release.
* Can now search for `sse` or `km` in the editor search bar to find all parts in this pack.

### Changes

This is the first in a series of updates to this addon. Each update will update some of the parts and patches so that instead of one massive update I can update the addon in a more manageable way.

### Previous Releases (Archive)

* Create archival releases
  * Version 2.0.0.0 - 27-Jul-2014
  * Version 2.0.1.0 - 27-Jul-2014
  * Version 2.1.1.0 - 25-Aug-2014
  * Version 2.1.2.0 - 25-Aug-2014
  * Version 2.1.3.0 - 21-Dec-2014
  * Version 2.1.0.0 - 09-Aug-2014
  * Version 2.2.0.0 - 20-May-2015
  * Version 2.3.0.0 - 07-Jul-2016

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
    * double-oms --> sse-engine-oms-double
      * oms --> sse-engine-oms-single
      * km_ma0 --> sse-multiadaptatron-0
      * km_ma1 --> sse-multiadaptatron-1
      * sh1 --> sse-shoulder-1
      * kmssh0 --> sse-shoulder-small-0
      * kmssh1 --> sse-shoulder-small-1
      * km_se0 --> sse-engine-0
      * km_se0-oms --> sse-engine-0-oms
      * km_ssme_rs25s --> sse-engine-1-a
      * km_ssme_rs25ss --> sse-engine-1-s
      * se2 --> sse-engine-2
      * km_se3 --> sse-engine-3
      * km_se4L --> sse-engine-4
      * KM_sparkler --> sse-sparkler
      * km-tank-top-? --> sse-tank-top-?
      * km-tank-mid-? --> sse-tank-mid-?
      * km-tank-mid-small-? --> sse-tank-mid-small-?
      * km-tank-bottom-? --> sse-tank-bottom-?
  * Rename model files to unique names
    * bb1.mu -> sse-engine-bigbang-1.mu
    * bb2.mu -> sse-engine-bigbang-2.mu
    * double-oms.mu -> sse-engine-oms-double.mu
    * oms.mu -> sse-engine-oms-single.mu
    * model.mu -> sse-multiadaptatron.mu
    * sh1.mu -> sse-shoulder-1.mu
    * module.mu -> sse-engine-1-a.mu
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * remove duplicates textures/models
    * [bb-HEAT 1.dds] 42.8kb
    * [cloud.dds] 21.4kb
    * [cloud.dds] 21.4kb
    * [cloud.dds] 21.4kb
    * [cloud.dds] 21.4kb
    * [cloud.dds] 21.4kb
    * [cloud.dds] 21.4kb
    * [FX/cloud.dds] 21.4kb
    * [x0-alpha-heat.dds] 42.8kb
    * [x0-complete.dds] 341.kb
    * [ssmeeffect.dds] 2.80kb
    * [ssmeeffect.dds] 2.80kb
    * [ssme-map.dd]s 341kb
    * [ssme-map-ALPHA-COMPLETE.dds] 1.33mb
    * [ssme-map-bump_NRM.dds] 1.33mb
    * [ssme-map-heat.dds] 10.8kb
    * total: 3.594mb
* relocate part.cfg to Parts/
* updates #55 - Asset Updates

### Parts

* Add
  * <ghostParts.cfg> v1.3.0.0
* Rename part files to match part names
  * part.cfg -> sse-engine-bigbang-1.cfg
  * part.cfg -> sse-engine-bigbang-2.cfg
  * part.cfg -> sse-engine-oms-double.cfg
  * part.cfg -> sse-engine-oms-single.cfg
* Rename parts to match naming scheme
  * double-oms --> sse-engine-oms-double
  * oms --> sse-engine-oms-single
  * km_ma0 --> sse-multiadaptatron-0
  * km_ma1 --> sse-multiadaptatron-1
  * sh1 --> sse-shoulder-1
  * kmssh0 --> sse-shoulder-small-0
  * kmssh1 --> sse-shoulder-small-1
  * km_se0 --> sse-engine-0
  * km_se0-oms --> sse-engine-0-oms
  * km_ssme_rs25s --> sse-engine-1-a
  * km_ssme_rs25ss --> sse-engine-1-s
  * se2 --> sse-engine-2
  * km_se3 --> sse-engine-3
  * km_se4L --> sse-engine-4
  * KM_sparkler --> sse-sparkler
  * km-tank-top-? --> sse-tank-top-?
  * km-tank-mid-? --> sse-tank-mid-?
  * km-tank-mid-small-? --> sse-tank-mid-small-?
  * km-tank-bottom-? --> sse-tank-bottom-?
* Fix
  * Missing closes PART brace
    * Parts/Shoulders/part.cfg
    * Parts/Multi Adapter/ma1.cfg
    * Parts/Multi Adapter/ma0.cfg
    * Parts/Smallshoulders/Sh1.cfg
    * Parts/Smallshoulders/Sh0.cfg
* closes #54 - Fix part.cfgs

### docs/

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Part-Catalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* closes #56 - docs/

### Localization

* Create
  * [SpaceShuttleEngines.cfg] v1.0.0.0
    * adds localized tags to parts
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
  * updates #17 - Localization - Master
  * updates #18 - English <us-en.cfg>
  * closes #35 - Part Localization

### Add localized tags to parts

* [SpaceShuttleEngines.cfg] v1.0.1.0
  * adds localized tags to parts
  * fix inadvertant passengers
* closes #58 - [BUG:] <SpaceShuttleEngines.cfg> fix inadvertent passengers
* closes #57 - Localization: Add localized tags to parts

### Thumbnails

* Add
  * add @thumbs
* closes #59 - Thumbnails

### License

* Updated License: CC BY-ND 4.0
  * was: CC BY-NC-ND 3.0
* closes #60 - License

### Status 2.3.99.0

* Issues
  * closes #13 - Space Shuttle Engines (SSE) 2.3.99.0-adoption `<T-Minus>`
  * closes #14 - 2.3.99.0 Verify Legal Mumbo Jumbo
  * closes #15 - 2.3.99.0 Create Documentation
  * closes #16 - 2.3.99.0 Create Social Media
  * closes #2 - [Request]: New Name!

---

## Version 2.3.0.0-release - `<Thank you sarbian>` edition

* 03 Jul 2016
* Update for 1.1

* Use the stock gimbal
* Require Gimbal Trim for the trimming

### Status 2.3.0.0

* Issues
  * closes #44 - 2.3.0.0-release
  * updates #36 - Previous Releases (Archive)

---

## Version 2.2.0.0-release

* 15 May 2015
* Updated for 1.0

* DDS textures
* Fixed nodes
* Updated ISP to 1.0 level

### Status 2.2.0.0

* Issues
  * closes #43 - 2.2.0.0-release
  * updates #36 - Previous Releases (Archive)

---

## Version 2.1.3.0-release

* 21 Dec 2014

* Moved km_gimbal to a new dir
* renamed to module to avoid problem with older installs
* SSE part now use the module called "KM_Gimbal_3" and the launch effect requires SmokeScreen

### Status 2.1.3.0

* Issues
  * closes #41 - 2.1.3.0-release
  * updates #36 - Previous Releases (Archive)

---

## Version 2.1.2.0-release

* 25 Aug 2014
* no changelog found

### Status 2.1.2.0

* Issues
  * closes #40 - 2.1.2.0-release
  * updates #36 - Previous Releases (Archive)

---

## Version 2.1.1.0-release

* 22 Aug 2014
* no changelog found

### Status 2.1.1.0

* Issues
  * closes #39 - 2.1.1.0-release
  * updates #36 - Previous Releases (Archive)

---

## Version 2.1.0.0-release

* 09 Aug 2014
* Fixed KM_Gimbal limitation for asymmetrical gimbal restraints

### Status 2.1.0.0

* Issues
  * closes #42 - 2.1.0.0-release
  * updates #36 - Previous Releases (Archive)

---

## Version 2.0.1.0-release

* 27 Jul 2014
* .24 compatibility

* no changelog found

### Status 2.0.1.0

* Issues
  * closes #38 - 2.0.1.0-release
  * updates #36 - Previous Releases (Archive)

---

## Version 2.0.0.0-release

* .24 compatibility
* New KM Folder Structure
* 27 Jul 2014

* !!! Please delete all 23.5 Klockheed Martian Folders before installing this update
* Recompiled with .net 3.5
* New folder structure
* SmartParts are not included any more. Install SmartParts separately.

### Status 2.0.0.0

* Issues
  * closes #37 - 2.0.0.0-release
  * updates #36 - Previous Releases (Archive)

---

## Version 1.4.3.0-release

* Recompiled for .24
* Fixed valve problem

---

## Version 1.4.2.0-release

* KM_Gimbal Fixes and Improvements
* Fixed an issue that the gimbaling would go the wrong way with multiple pods (at least one reverted) on the same rocket
* Added gimbal constraint to reduce max gimbaling (if things shake too much)

---

## Version 1.4.1.0-release

* Performance improvement and smaller fixes
* Roll is now disabled for engines without symmetric counterpart. Can be enabled manually.
* FX performance improvements
* Significant KM_Gimbal performance tuning
* Engine shroud and bottom node for the straight SSME
* Reduced gimbal range of the straight SSME
* Fixed slightly off center straight SSME
* Removed S0 engine shroud from editor picture
* Fixed missing prelaunch effect for straight SSME

---

## Version 1.4.0.0-release

### sarbian

* Removed old changelog from before V1.0
* Straight SSME, better FX, better KM_Gimbal, better performance
* Added straight X25 SSME engine for normal lifters
* FX overhaul. Less blue, fixed smoke.
* Improved KM Gimbal, fixed a bug that occured when the COM moved past the engine
* KM Gimbal now uses .Net 3.5
* KM Gimbal now allows for Yaw trimming, too
* KM Gimbal now supports multi mode engines
* Improved CPU performance by further reducing the collision meshes
* Added multi adapter part for creating engine clusters below tanks

---

## Version 1.3.1.0-release

* Performance improvements
  * Simpler collision meshes for orange tank system - better performance
  * km_lib update to stay synced with asteroid cities

---

## Version 1.2.1.0-release

* Small fixes
  * Reduced memory footprint by deleting unused textures
  * Smart parts update
  * Rotated SSME engine to match positive x axis
  * Added +5 degree pitch option to action groups

---

## Version 1.2.0.0-release

* RS-25 high detail SSME and improved FAR compatibility
  * New SSME lookalike engine
  * Improved FAR compatibility (tank node sizes fixed)

---

## Version 1.1.0.0-release

* Sparkers and gimbal fixes
  * Space shuttle spakers as launch effects (attach to launch clamps)
  * Gimballing now also activates when engine is activated via action groups
  * Gimballing now automatically turns off when the engine is deactivated
  * Pitch can now be changed (+/-) via action groups. Close the context menu to adjust pitch during flight!
  * New example craft
  * Gimbal support for ModuleEnginesFX
  * Smart Parts update (see smart parts for details)

---

## Version 1.0.0.0-release

* Art Pass, Cryo Effects, Balancing, OMS
  * Particle based pre-launch effect
  * Art pass: Better looking tank system (more similar to the actual shuttle tank textures)
  * Switched vacuum and sea level LSP. The engines are more realistic now. 
  * Fixed offset for dual OMS engines. They fly straight now.
  * Added OMS version of X0 engine.
  * Fuel valve for getting rid of excess fuel before reentry
  * The tank system has built-in smart part fuel sensors now. Right click on a tank.
  * Smart parts update (see smart parts for details)

---

## Version 0.9.2.0-release

* Updated Smart Parts
  * Heading control over radio
  * Improved altimeter device (thanks to Firov)
  * Bugfix in the timer code
  * Corrected size descriptions of fuel breakers and tanks
  * Fixed bug with engine tweakables that made the CoM disappear
  * Increased the weight of the OMS engines to match the TWR of the LV-909
  * Reduced the heat production of the X3 engine
  * Updated Firefly example craft (was broken)

---

## Version 0.9.4.0-release

* Smart Parts Update and Bufix of Explorer craft
  * Example craft for smart parts
  * Minor fixes for smart parts
  * Fixed Explorer example craft
  * New KM_Lib.dll

---

## Version 0.9.2.0-release

* Updated Smart Parts
* Heading control over radio
* Improved altimeter device (thanks to Firov)
* Bugfix in the timer code
* Corrected size descriptions of fuel breakers and tanks
* Fixed bug with engine tweakables that made the CoM disappear
* Increased the weight of the OMS engines to match the TWR of the LV-909
* Reduced the heat production of the X3 engine
* Updated Firefly example craft (was broken)

---

## Version 0.9.1.0-release

* New Smart Parts Version (Caution! Compatibility notice below!)
* Complete overhaul of the smart parts
* New remote controller part (control other vessel's action groups over radio)
* Altimeter action group trigger
* Updated example craft
* Trim can now be toggled

---

## Version 0.9.0.0-release

* Tweakables, new gimbal logic and linear aerospike
* Added a completely new gimbal logic:
  * Proper roll support (can be activated on demand)
  * Proper part-based x and y limitations (even when the part is rotated)
  * Tweakables: tweak gimballing speed and trim the 0 position (it does not change the gimbal range)
* Added tweakables to timer (now you can set the duration with a slider)
* Added linear aerospike with mechanic gimballing
* Added Atlantis C craft as demonstration for the aerospike
* Updated the other example craft

---

## Version 0.8.2.0-release

* 0.23 Compatibility
* Reverted to normal gimbal logic. It does not feel and look like the previous logic but it works.
* Adjusted attachment node positions. Squad has finally fixed the attachment node vectors.

* Removed redundancy to exsurgent engineer .dll (it is not used any more)

---

## Version 0.8.1.0-release

* Maintenace update
* Corrected spelling mistake in countdown counter
* Corrected wrong Isp setting for x3 engine
* Corrected wrong size of flameout detectors
* Improved visual appearance of flameout detectors
* Corrected heat animation of OMS engine
* Updated Falcon example craft

---

## Version 0.8.0.0-release

* Performance improvements and new automatic parts
* Reduced the size of the textures to save a total of 200MB RAM
* Replaced any colliders with box colliders - easier to compute, lighter on the CPU
* Removed an unnecessary collider from the BB1 engine. It should perform better now.
* Added fuel controller. It can turn on and off the fuel crossfeed. It is used with fuel lines.
* Added fuel controller functionality to in-line fuel breaker. They can now control the fuel flow, too
* Moved in-line fuel breakers tu Utility section in the editor
* Added timer device. It can even trigger actions on separated stages! Control it with action groups.
* Added Flameout detector. This should make building spaceplanes with more than one jet engine easier.
* Added an example vessel Falcon to show the new functions.

---

## Version 0.7.0.0-release

* Automatic staging and action groups plus minor fixes
* Added staging and action group trigger thingies (see pictures)
* Removed surface attachment property from fuel breakers
* Adjusted drag values for fuel tanks and caps a bit until I found out that all values of the stock parts are bogus. If someone wants to make a sane suggestion - go ahead.

---

## Version 0.6.0.0-release

* BB2 Non-rotating Big Bang Engine
* Added non-rotating BB engine. Maybe this solves the lag problem.

---

## Version 0.5.0.0-release

* New engines and radial mount options
* Two new engines (X0 and X3) for smaller and larger shuttles
* Two radial mount points that make clusters of engines easier
* Two new example craft files: Firefly and Endeavour (stock and B9 as well as Procedural Dynamics)
* Added Atlantis B craft as alternative NASA Shuttle like craft

---

## Version 0.4.0.0-release

* External tank system
* slight graphical overhaul of the BB engine (it has additional static shadows now)
* 16 Tank elements for shuttles of many sizes
* 4 Fuel flow breaker elements to separate one tank into several independent pieces
* Some minor improvements of the BB engine's visuals
* The X2 engine was moved from "heavier rocketry" to "heavy rocketry"
* Tech tree integration for the new tanks
* Spellchecked this document
* Added example crafts: Explorer and Atlantis. Both require B9. Atlantis also requires Procedural Dynamics (Wings)

---

## Version 0.3.0.0-release

* Gimbal animation, limited yaw range and balancing
* Complete visual overhaul of the BB engine. It looks more shuttle-like now.
* Added gimbal animation. Now the X2 and BB1 engines gimbal correctly.
* Increased atmospheric efficiency of OMS engines
* Increased thrust of the X2 engine (three X2s can now lift a shuttle plus payload)
* Limited strong gimbaling to pitch axis
* Removed heat animation from BB1 engines (it gets stuck whenever the engine rotates)
* Added Big Bang rotating 2m engine.
* Slightly changed the appearance of the "shoulder" radial connector.
* Added tech tree integration.

---

## Version 0.2.0.0-release

* Parts and tech Tree
* Added tech tree integration.
* Slightly changed the appearance of the "shoulder" radial connector.
* Added Big Bang rotating 2m engine.

---

## Version 0.1.0.0-release

* dtobi
* Initial release
* April 19, 2013

---
