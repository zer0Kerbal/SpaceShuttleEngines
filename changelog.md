# Changelog  
  
| modName    | Space Shuttle Engines (SSE)                                       |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-ND-4.0                                                      |
| author     | dtobi, sarbian and zer0Kerbal                                     |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209177-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/SpaceShuttleEngines)    |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/SpaceShuttleEngines)  |
| spacedock  | (https://spacedock.info/mod/3009)                                 |
| ckan       | SpaceShuttleEngines                                               |

## Version 2.3.99.0-adoption - `<EDITION>` edition

* 31 Jul 2022
* Released for KSP 1.12.3

* #2 - [Request]: New Name!

---

## Version 2.3.0.0-release

* Update for 1.1

* Use the stock gimbal
* Require Gimbal Trim for the trimming

---

## Version 2.2.0.0-release

* 15 May 2015
* Updated for 1.0

* DDS textures
* Fixed nodes
* Updated ISP to 1.0 level

---

## Version 2.1.0.0-release

* Fixed KM_Gimbal limitation for asymmetrical gimbal restraints

---

## Version 2.1.3.0-release

* Moved km_gimbal to a new dir
* renamed to module to avoid problem with older installs
* SSE part now use the module called "KM_Gimbal_3" and the launch effect requires SmokeScreen

---

## Version 2.0.0.0-release

* .24 compatibility
* New KM Folder Structure

* Recompiled with .net 3.5
* New folder structure
* SmartParts are not included any more. Install SmartParts separately.
* !!! Please delete all 23.5 Klockheed Martian Folders before installing this update

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
