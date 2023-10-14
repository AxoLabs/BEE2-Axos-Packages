![AxoLabs' UCPs](https://user-images.githubusercontent.com/125143965/220545356-dc6fc292-efe7-4334-b8f5-97226796dd05.png)
# BEE2-Axo's-Packages
Supported version of BEEMod: 2.4.43.0.

Supported styles: OG clean and hybrid.

If you are going to use my items/assets I made for them in a map, I'd greatly appreciate being credited for them.

If you want to suggest an enhancement, or report a bug, please read the **contributing guidelines**: https://github.com/AxoLabs/BEE2-Axos-Packages/blob/main/docs/CONTRIBUTING.md

**NOTICE**: Redistributing *any* of my packages and/or their contents, modified or unmodified, without my explict permission is prohibited.

## A list of the packages' contents and their functions, ordered by significance
### Schrödinger's cubes
A cut testing element reimplemented by me from scratch. They are a pair of cubes, when a laser one cube, other. You can read more about them here: https://tcrf.net/Portal_2#Schr.C3.B6dinger.27s_Cube.
- **Start enabled** controls whether the cube will drop automatically when the map is loaded or not.
- **Start active** controls whether a replacement cube will be delivered automatically when the cube is destroyed.
- **Cube type** allows you to link cubes together - For example, a cube with the cube type set to sphere will activate all other cubes with the cube type set to sphere, one with the type set to standard will activate all with the type set to standard, and so on.
- Due to an editor bug, this item can be attached to floor surfaces. It will not work when floor-oriented, however.
- Due to various limitations of Portal 2, it is not possible to restore the paint-sharing functionality, unfortunately.
### Hybrid style
A style that aims to combine Portal 1's and Portal 2's aesthetical styles. Inspired by Zepalesque's *Portal: Enrichment* videos.
- Portal 1-styled observation rooms are used.
- The pool of metal tile textures has been given more variety.
- Portal 1's fizzling effect has been brought back.
- Several entry and exit corridors have been overhauled.
- Portal 1-esque fizzlers are used used.
- Weighted cubes have new textures.
- And a lot more.
### Enhanced Surface Marker
A fixed and expanded version of the surface marker item that can force 5 different tile patterns and 5 different textures onto walls. For a more in-depth guide on how to use it, please consult the [wiki](https://github.com/AxoLabs/BEE2-Axos-Packages/wiki/Enhanced-surface-markers).
### Cube hole
A hole cubes and such can pass through, but the player can not.
### Autoportal variants
- Protruding autoportal: An autoportal mounted on a surface protruding from the wall by 8 units.
- Angled autoportal, an autoportal mounted on an angled surface. **Button type** allows you to switch between an angle of 60, 45, and 30 degrees.
- Unlinked autoportal, an autoportal that is not linked to your portal gun. Use the **timer** to select the linkage ID.
- For all three, the start **start enabled** option controls whether the portal starts active or not.
- For all three, **start reversed** controls whether the portal is orange or blue.
### Large glass panels
A larger, unembedded version of the normal glass panel.
- **Start deployed** controls whether the panel starts raised/extended or not.
- **Start reversed** when checked, switches to the 128x256 model.
- If input B is used, instead of raising by 90 degrees, upon activation, the panel will extend by a voxel.
### Suspended panel
A surface held by a panel a voxel above the ground.
- Check **start reversed** to make it non-portalable.
### Protruding surface
A portalable surface, protruding out a wall. Comes with a powerful portal magnet implemented into it. **Start reversed** makes the plastic textures darker.
### Personalized hazard identification board
A test sign that can be easily customized. Read the `Instructions.txt` file carefully for more info.
- Use Omnicoder's Sign Maker to generate a template for this item to load: https://developer.valvesoftware.com/wiki/Sign_Maker (Important note: The Sign Maker was not made, or worked on by me).
### Purple paint fizzler
A modified version of the default paint fizzler that is purple. The first item made for this package.
