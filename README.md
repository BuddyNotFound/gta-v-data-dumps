# GTA-V Extracted Data Dumps
This is a collection of various GTA V data dumps mostly useful for modding &amp; scripting. All of these are auto generated and some are enhanced with data from my GTA V researches.

[![Durty Map Editor Logo](https://i.imgur.com/WsRJv3u.png)](https://discord.gg/hgSutAU)
If you are in search for an easy way to browse those GTA V data ingame, feel free to join my Map Editor Discord: https://discord.gg/hgSutAU

## All data up2date as of GTA V update: **v1868.1 (Online 1.50)**
---
## Please create an issue if you have any problems with the data, so I can improve my generator. You are also welcome to create issues for dumps you would like to see.
---
## **Featured data dumps**
- **IPLs** (ipls.json) **1018** ipls, **537** interiors & **4973** interior entity sets in total (Usable with IPL & entity / interior set natives)
- **Speech Voices** (speeches.json) **1018** speech voices with **150055** speeches in total (Usable with PLAY AMBIENT SPEECH natives)
- **Particle Effects** (particleEffectsCompact.json) **273** particle effect dictionaries & **1286** particle effects in total (Usable with START PARTICLE FX natives)
- **(Ped) Scenarios** (scenariosCompact.json) **239** scenarios in total (Usable with scenario related natives)
- **Animations** (animDictsCompact.json) **16363** animation dictionaries & **167315** animations in total (Usable with TASK PLAY ANIM native)
- **Movement Clipsets** (movementClipsetsCompact.json) **557** movement clipsets in total (Usable with SET PED MOVEMENT CLIPSET native)
- **(Walking) Movement Clipsets** (movementClipsetsWalkingCompact.json) **207** movement clipsets in total (Usable with SET PED MOVEMENT CLIPSET native)
- **(Navigation) Nodes** (nodes.json) **259** node cells with **77991** nodes in total (Mostly useful for vehicle navigation, see navigation meshes dump for ped navigation data)
- **Navigation Meshes** (navigationMeshes.msgpack) **4404** navmeshes with **6384911** polygons in total (See navigationmesh.md for the messagepack model)
- **Ped Overlay Collections (Tattoos)** (pedOverlayCollections.json) **29** ped overlay collections with **2676** overlays in total (Usable tattos/badges with ped decoration native)
- **Timecycle Modifiers** (timecycleModifiers.json) **2806** timecycle modifiers in total (Usable with TIMECYCLE MODIFIER natives)
- **Explosion Types (Names)** (explosionTypesCompact.json) **74** explosion types in total (Usable with ADD EXPLOSION native)
- **Cam Shake Types (Names)** (camShakeTypesCompact.json) **21** cam shake types in total (Usable with SHAKE CAM & SHAKE GAMEPLAY cam natives)
- **Audio / Sound names & ref names** (soundNames.json) **1906** audio names from a total of **62** unique audio refs (Usable with PLAY_SOUND natives)
- **Pickup Types (Names)** (pickupTypes.json) **150** pickup types in total (Usable with CREATE PICKUP natives)
- **Vehicle Mod Kits** (vehicleModKits.json) **394** vehicle mod kit infos in total (Usable with SET_VEHICLE_MOD_KIT & SET_VEHICLE_LIVERY natives)
- **Vehicles** (vehicles.json) **687** vehicle infos in total (Usable with VEHICLE natives)
- **AnimpostFX names** (animPostFxNamesCompact.json) **147** animpostfx names in total (Usable with ANIMPOSTFX natives)
- **Ped Component Variations** (pedComponentVariations.json) **19958** component variations & **2986** ped props from a total of **58** ped component variation collections (Usable with COMPONENT VARIATION & PED PROP natives)
- **Ped Apparel Restriction tag names** (animPostFxNamesCompact.json) **375** ped apparel restriction tags in total (Usable with PED RESTRICTION natives)
- **Waypoint recording names** (waypointRecordings.json) **791** waypoint recording infos in total (Usable with WAYPOINT RECORDING natives)
- **Garages** (garages.json) **16** garage infos in total (Usable with GARAGE natives)
- **Vehicle Handlings** (vehicleHandlings.json) **611** vehicle handling infos in total (Shared for all existing vehicles, see handling id in vehicles dump)
- **Zones** (vehicleHandlings.json) **96** zone infos in total (Usable with some ZONE natives, contains all bounds coords for the zones)

## **Featured objects location dumps**
Object location dumps contain positions of various objects of a specific type, on the GTA V map (including all interiors / MLOs).
- **Vending Machines** (worldVendingMachines.json) **324** in total ([Click for more info](https://forum.altv.mp/topic/346-all-gta-v-vending-machine-prop-positions-rotations/))
- **Bin/Dumpster/Recycle Bins** (worldBinsDumpsters.json & worldRecycleBins.json) **7601** bins/dumpsters in total & **127** recycle bins in total ([Click for more info](https://forum.altv.mp/topic/369-all-gta-v-bindumpsterrecycle-bin-prop-positions-rotations/))
- **Gas Pump Stations** (worldGasPumps.json) **157** in total ([Click for more info](https://forum.altv.mp/topic/368-all-gta-v-gas-pump-prop-positions-rotations/))
- **Jukeboxes** (worldJukeboxes.json) **6** in total ([Click for more info](https://forum.altv.mp/topic/365-all-gta-v-jukebox-prop-positions-rotations/))
- **Dart Discs** (worldDartDiscs.json) **11** in total ([Click for more info](https://forum.altv.mp/topic/364-all-gta-v-dart-discs-positions-rotations/))
- **Bus Stops** (worldBusStops.json & worldBusStopSigns.json) **48** bus stops in total & **1** bus stop sign in total ([Click for more info](https://forum.altv.mp/topic/342-all-gta-v-bus-stops-positions-rotations/))
- **Parknmeters** (worldParknmeters.json) **547** in total ([Click for more info](https://forum.altv.mp/topic/345-all-gta-v-parknmeters-prop-positions-rotations/))
- **Telescopes** (worldTelescopes.json) **106** in total ([Click for more info](https://forum.altv.mp/topic/344-all-gta-v-telescope-prop-positions-rotations/))
- **News Paper Dispenser** (worldNewsPaperDispensers.json) **796** in total ([Click for more info](https://forum.altv.mp/topic/343-all-gta-v-news-paper-dispenser-prop-positions-rotations/))
- **ATMs** (worldAtms.json) **121** in total ([Click for more info](https://forum.altv.mp/topic/340-all-gta-v-atm-prop-positions-rotations/))
- **Public Phones** (worldPublicPhones.json & worldExtraPhones.json) **432** public phones in total & **294** extra phones in total ([Click for more info](https://forum.altv.mp/topic/341-all-gta-v-public-phone-prop-positions-rotations/))
- **Radio Towers** (worldRadioTowers.json) **86** in total ([Click for more info](https://forum.altv.mp/topic/570-all-gta-v-radio-tower-prop-positions-rotations/))
- **Antennas** (worldAntennas.json) **5** in total
- **Mobile Masts** (worldMobileMasts.json) **8** in total
- **Air Masts** (worldAirMasts.json) **16** in total
- **Fire Hydrants, Hoses & Drisers** (worldFireHydrantDriser.json) **1425** in total
- **Post Boxes** (worldPostBoxes.json) **195** in total
- **Letter Boxes** (worldLetterBoxes.json) **379** in total
- **Harvest fields** (orange trees, vine grapes, corns, salad, pumpkin, tomatoes) (worldHarvestFields.json) **623** in total
- **Fruit stands** (worldFruitStands.json) **13** in total