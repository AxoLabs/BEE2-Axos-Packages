# Version 1.9
The main package took: 29 development versions, with `Beta 9 Build 7 RC 7` being the one which got released.

The hybrid style took: 65 development versions, with `Beta 21 Build 3 RC 8` being the one which got released.

The hazard identification boards did not receive any changes.
### Changelog
- *Literally nothing, that's it! Nothing's changed in this update at all!*
---
# Version 1.8
The main package took: 9 development versions, with `Beta 1 Build 9 RC 2` being the one which got released.

The hybrid style took: 8 development versions, with `Beta 4 Build 3 RC 4` being the one which got released.

The hazard identification boards did not receive any changes (*yet* again).
### Changelog
- Fixed #11.
- Fixed #5.
- Fixed hybrid style's ceiling goo textures being set to use BTS yellow plastic textures.
- Implemented #14.
- Added a check if there's space for the camera above the entry/exit doors to spawn in the hybrid style.
- Added hybrid-styled versions of asd417's HD pellet catchers.
- Added on option to enable the Portal 1 color correction in the hybrid style.
- Tweaked the metal tile variety in the hybrid style. The 4x4 textures will appear much less often on walls, and ceilings now use several textures, instead of only one.
- Tweaked the lights in medium obs. rooms in the hybrid style.
- Tweaked how heavy the gel flow will be when it's set to 'very heavy' on cube dropper gel droppers.
- Tweaked the editor icons for the protruding autoportal, the angled autoportal, the unlinked autoportal, the cube hole, and Schrödinger's cubes.
- Normal gel droppers will now use their P1-styled variants in the hybrid style.
- Normal permanent pellet catchers will now turn yellow when activated in the hybrid style.
- Cleaned up some of the comments in the packages' files.
- Removed several light entities from the large obs. room in the hybrid style.
- Removed vertical entrances and exits from the hybrid style, they were broken.
- Removed support for several cut fizzlers from the hybrid style in order to keep the files tidy.
---
# Version 1.7.2
The main package took: 1 development version, with `Beta 1 Build 1 Release Candidate 1` being the one which got released.

The hybrid style took: 6 development versions, with `Beta 2 Build 4 Release Candidate 1` being the one which got released.

The hazard identification boards did not receive any changes (again).
### Changelog
- Added a new item: The cube hole. It is a hole that cubes and such can pass through, but the player can't.
- Changed the bumpmap hybrid style's the white tile textures use, because the old one was awful.
- Merged the stair variants (small stairs and half stairs) into one item.
- Stair items will now automatically use their darker variants if they are placed on a dark tile.
- Fixed cube dropper gel dropper's description not matching other items' descriptions.
- Removed some leftover files from the physics obliteration field, I forgot to purge them.
- Removed the portal condensation grid and the concentrated particle field.
- Removed Herobrine.
---
# Version 1.7.1
The main package took: 6 development versions, with `Beta 1 Build 6` being the one which got released.
The hybrid style took: 9 development versions, with `Beta 1 Build 9 Release Candidate 3` being the one which got released.
The hazard identification boards did not receive any changes.
### Changelog
- The hybrid style now uses custom versions of the default white tiles. The custom versions were made by me.
- Removed the SP exit corridor 3#, it was utterly broken.
- Implemented #12.
- Added a new item, the large glass panel. Surprisingly enough, it's a large glass panel. Comes in 128x128 and 128x256 versions. Input A/B can be used to control which animation will be played upon activation.
---
# Version 1.7
The main package took: 18 development versions, with `Beta 3 Build 5 Release Candidate 4` being the one which got released.

The hazard identification boards took: 4 development versions, with `Beta 1 Build 4 Release Candidate 2` being the one which got released.

The hybrid style took: 37 development versions, with `Beta 7 Build 11 Release Candidate 2` being the onw which got released.
### Changelog
- Added a brand-new style: The hybrid style. It is a combination of Portal 1's and Portal 2's aesthetics, with some additional, minor changes. Heavily inspired by Zepalesque's *Portal: Enrichment* videos.
- Added a way to link Schrödinger's cubes using the **cube type** property (#6).
- Added darker variants of the geometry items. Simply check **start reversed** to use them.
- Added an unlinked autoportal - An autoportal with a diffrent design that is not linked to your portal gun. The linkage ID can go from `3` to as high as `28`. Best used as an alternate chamberlock.
- Added a list of packages this package pulls assets from to the `info.txt` file, so that you don't run into missing models and such.
- Partially resolved #11.
- Fixed protruding and angled autoportals being able to stay activated, after being deactivated.
- Fixed all the items not having OccupiedVoxels in their `editoritems.txt` files.
- Fixed the textures on hazard identification boards being misaligned for some reason in some cases.
- Fixed a few inconsistencies in the items' descriptions.
- Changed the amplitude and frequency of the shake effect used by the autoportal variants, so that it is actually noticeable now.
- Changed the white tile materials used by several geometry items to match the PeTI textures.
- Changed 'AxoLabs' to 'Axo' in the items' descriptions.
---
# Version 1.6
This update took: 17 development versions, with `Beta 7 Build 2 Release Candidate 2` being the one which got released.
### Changelog
- Cube dropper gel droppers now glow orange when they are enabled.
- Changed the 'plastic' materials used by the various decoration/geometry items.
- Fixed a typo in protruding surfaces' description.
- Schrödinger's cube droppers now have options to enable/disable auto-respawning and auto-dropping. 
- Partially fixed #5.
- Added suspended panels.
- Added angled autoportals.
- Moved the portal on the protruding autoportal to the middle.
- Added customizable chamber boards. To make using them easier, they are their own, separate package. Make sure to read the file with the instructions.
- Removed the portal lights enabler due to it being a completely and entirely pointless item.
- Removed the Portal Support Grid due to a lack of practical applications and being replicable with other items.
---
# Version 1.5
This update took: 46 development versions, with `Beta 8 Build 8 Release Candidate 6` being the one which got released.
### Changelog
- Catcher Schrödinger's cubes now use a weighted cube as their parent entity.
- Fixed catcher Schrödinger's cubes not being affected by gels.
- Fixed catcher Schrödinger's cubes not pressing buttons
- Implemented #7.
- Catcher Schrödinger's cubes now emit a red glow effect when they are activated.
- Schrödinger's cubes have a new icon made by PieCreeper.
- Cube dropper gel droppers no longer support P1 style.
- You can now control the gel flow of a cube dropper gel dropper with `button type`.
- New item: Small stairs - Static stairs designed to fit a single voxel, inspired by some of *Blue Portals*' designs.
- New item: Half stairs - Static stairs that are only half a voxel high. *Start reversed* controls whether they occupy the bottom or the top part of the voxel.
- New item: Protruding surface - A portalable surface protruding out of the wall, with a built-in, powerful portal magnet.
- New item: Protruding autoportal - A protruding surface with an orange autoportal attached to it. *Start enabled* controls whether the portal starts enabled or not.
---
# Version 1.5 b3-7
Since it doesn't seem like I will find a way to fix Schrödinger's cubes any time soon, I thought I'd release the most stable development build so far, one so stable I keep switching over to it, because all later builds have completely broken Schrödinger's cubes (in every way possible, including mentally), as opposed to my aim of fixing them. 
### Changelog
- Schrödinger's cubes have a new icon made by PieCreeper.
- Cube dropper gel droppers no longer support P1 style.
- You can now control the gel flow of a cube dropper gel dropper with `button type`.
---
# Version 1.4
This update took: 50 development versions, with `Beta 9 Build 3 Release Candidate 1` being the one which got released.
### Changelog:
- Removed the bomb protector.
- Removed the AAAAAAAARRRRRRRRRRGGGGGGGGGHHHHH Theraphy skybox.
- Removed leftovers of a crash gel item.
- Removed the Physics Obliteration Field.
- Removed a random leftover file from back when the purple paint fizzler was meant to override the default one.
- Fixed CPFs and PSGs being broken when `start enabled` is unchecked.
- Fixed portals being placeable behind cube dropper gel droppers.
- Added **Schrödinger's cubes** - a cut testing element, now reimplemented from scratch. They are a bit buggy, but should work fine in most cases. They were the hardest item to create yet, but totally worth it.
---
# Version 1.3
This update took: 26 development versions, with `Beta 12 Build 7 Release Candidate 4` being the one which got released.
### Changelog:
- Removed my name from several items' names, as it was simply pointless and a little spammy.
- Added a "bomb protector". It will cause `prop_exploding_futbol`s, or bombs if you prefer, to stop inflicting harm upon exploding.
- Added indication which gel will a cube dropper gel dropper drop.
- Added a "reflection gel fixer". Fixes Reflection gel using Conversion and Propulsion paints' colors.
- Added an "AAAAAARRRRRGGGGGHH Theraphy" skybox, revealing the BTS areas of Aperture. Recommended to use alongside Alexus' visible skybox item.
---
# Version 1.2
### Changelog:
- Purple Paint Fizzler now has a proper icon, thanks to PieCreeper.
- Fixed Portal 1-styled cube dropper gel droppers being off the ceiling.
- Physics Obliteration Field was functionally nearly entirely remade. It should now properly fizzle all physic objects. Expect me to improve the filter system in the future, as currently it causes larger POFs to generate lag whenever fizzling something (https://github.com/AxoLabs/BEE2-Axos-Packages/issues/2)
- Added a new item: The Portal Support Grid - A custom fizzler that essentially acts like a toggle-able wall, except you can place portals on it! Inspired by the Portalable Field from the _Divinity_ series.
- The packages have been unified and merged into a single `.bee_pack`.
---
# Version 1.1
Changelog:
- All custom fizzlers now also have P2-styled emitter models!
- Cleaned up the Portal Condensation Grid, removed leftovers of Paint Fizzler's functions.
- New package: The Concentrated Particle Field, invented by PHOBoS. It is a combination of my PCG and the Physler. Comes with a signage!
- New package: Portal Lights Enabler. This item will enable `r_portal_use_dlights` when placed in a map, making portals glow!
- New package: Cube Dropper Gel Droppers: Gel droppers that use a cube dropper model. You can select the gel type using `Cube Type`, and choose whether it starts enabled or not using `Start Enabled`. Supports both Clean and Portal 1 style. When set to drop Reflection Gel, it will also properly pack it's particles into the map. Bonus: Does _**NOT**_ use a separate instance for every gel type!!!!

This version contains: 
- Purple Paint Fizzler version 14.
- Portal Condensation Grid version 7.
- Physics Obliteration Field version 12.
- Concentrated Particle Field version 6.
- Portal Lights Enabler version 4.
- Cube Dropper Gel Dropper version 10.
---
# Version 1.0
The first release. Contains:
- The purple paint fizzler version 14.
- The portal condensation grid version 5.
- The physics obliteration field version 11.
