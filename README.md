![AxoLabs' UCPs](https://user-images.githubusercontent.com/125143965/220545356-dc6fc292-efe7-4334-b8f5-97226796dd05.png)
# BEE2-Axo's-Packages
Supported version of BEEMod: 2.4.43.0.

Supported styles: OG clean and hybrid. Some items might have variants for other styles, but usually it's because removing the styled variants takes more effort than keeping them.

If you are going to use my items/assets I made for them in a map, I'd greatly appreciate being credited for making them.

If you want to suggest an enhancement, or report a bug, please read the **contributing guidelines**: https://github.com/AxoLabs/BEE2-Axos-Packages/blob/main/docs/CONTRIBUTING.md

**NOTICE**: Redistributing *any* of my packages and/or their contents, modified or unmodified, without my explict permission is prohibited.

## A list of the packages' contents and their functions, ordered by significance
### Schrödinger's cubes
A cut testing element reimplemented by me from scratch. They are a pair of cubes, when a laser hits the catcher cube, it'll come out of the emitter cube. You can read about them here: https://tcrf.net/Portal_2#Schr.C3.B6dinger.27s_Cube
- They are a bit buggy, but should work mostly fine. I have plans to slightly improve them in future updates, but don't take it as a promise.
- **Start reversed** controls whether the cube is a catcher cube (will power emitter cubes when touching a laser), or an emitter cube (will fire a laser when powered by a catcher cube).
- **Start enabled** controls whether the cube will drop automatically when the map is loaded or not.
- **Start active** controls whether a replacement cube will be delivered automatically when the cube is destroyed.
- **Cube type** allows you to link catcher cubes and emitter cubes together. So for example, a catcher cube with the cube type set to sphere will activate an emitter cube with the cube type set to sphere.
### Hybrid style
A style that aims to combine Portal 1's and Portal 2's aesthetical styles. Inspired by Zepalesque's *Portal: Enrichment* videos.
- Portal 1 cameras are used.
- Portal 1-styled observation rooms are used.
- More variety to metal tiles.
- Portal 1's dissolving effect has been brought back.
- Singleplayer entry and exit corridors have been largely overhauled.
- Portal 1-esque fizzlers are used used.
- And a lot more.
### Large glass panels
A larger, unembedded version of the normal glass panel.
- **Start deployed** controls whether the panel starts raised/extended or not.
- **Start reversed** when checked, switches to the 128x256 model.
- If input B is used, instead of raising by 90 degrees, upon activation, the panel will extend by a voxel.
### Cube hole
A hole cubes and such can pass through, but the player can't.
### Cube dropper gel dropper
A custom variant of the gel dropper that uses a cube dropper model instead.
- **Cube type** controls the type of the gel the dropper drops.
- **Button type** controls the gel flow.
- **Start enabled** controls whether the dropper starts active or not.
### Personalized hazard identification board
A test sign that can be easily customized. Read the `Instructions.txt` file carefully for more info.
- Use Omnicoder's Sign Maker to generate a template for this item to load: https://developer.valvesoftware.com/wiki/Sign_Maker (Important note: The Sign Maker wasn't made or worked on by me).
### Protruding surface
A portalable surface, protruding out a wall. Comes with a powerful portal magnet implemented into it. **Start reversed** makes the plastic textures darker.
### Autoportal variants
- Protruding autoportal: An orange autoportal mounted on a protruding surface. **Start reversed** makes the plastic textures darker.
- Angled autoportal, an orange autoportal mounted on an angled surface. **Start reversed** makes the plastic textures darker.
- Unlinked autoportal, an autoportal that is not linked to your portal gun. Use the **timer** to select the linkage ID, and **start reversed** to control whether the portal is orange or blue.
- For all three, the start **start enabled** option controls whether the portal starts active or not.
### Stair variants
An item that can either appear as a set of stairs that fit a single voxel, or a set of stairs that are only half a voxel high. 
- Place the item on metal tiles to make it darker.
### Suspended panel
A surface held by a panel a voxel above the ground.
- Check **start reversed** to make it non-portalable.
### Purple paint fizzler
A modified version of the default paint fizzler that is purple. The first item made for this package.
### Reflection gel fixer
Changes the color of Reflection gel to be gray when splashed on surfaces and your face.

## Screenshots:
*Purple paint fizzler, cube dropper gel droppers and recolored reflection gel*
![axos_ucps_v8](https://user-images.githubusercontent.com/125143965/236700629-a61780be-dae8-4160-874b-87c1ba39e3ff.png)
*Hybrid style's preview image*
![hybrid_style_1](https://user-images.githubusercontent.com/125143965/235435706-d7532228-1b74-4292-944e-67f6d10d2f16.png)
*Schrödinger's cubes*
![schrodinger's_cubes_2](https://github.com/AxoLabs/BEE2-Axos-Packages/assets/125143965/2fba3a27-0423-44b7-8b16-3e61f2f71016)
*Suspended panels*
![suspended_panels](https://user-images.githubusercontent.com/125143965/235435765-9598e6a9-588e-4260-8a25-b1b29f8b33d4.png)
*Hybrid style in action, the map can be found [here](https://steamcommunity.com/sharedfiles/filedetails/?id=2961094236)*
![hybrid_style_2](https://user-images.githubusercontent.com/125143965/235436555-d9f7ef68-f394-46f6-b2d9-48bb184c639d.png)
*Hybrid style's exit corridor 3#*
![hybrid_style_4_2](https://github.com/AxoLabs/BEE2-Axos-Packages/assets/125143965/2b57ac95-65df-4dbb-99cb-eafd82320850)
*Stair variants*
![stair_variants](https://user-images.githubusercontent.com/125143965/235435948-5cadf695-c126-4ea1-a83b-29da3c0acefa.png)
*Large glass panels*
![large_glass_panels](https://user-images.githubusercontent.com/125143965/235834993-7876ae42-6ba3-4040-83c6-bc95a9bccd55.png)
*Autoportal variants*
![autoportal_variants](https://user-images.githubusercontent.com/125143965/235436062-9aa1d682-ba51-44af-886d-fd0b39df4935.png)
*Hybrid style's entrance corridor 6#*
![hybrid_style_3](https://user-images.githubusercontent.com/125143965/235433086-73aefefa-2c79-47df-b3f7-7f2defad46aa.png)
*Cube hole*
![cube_hole](https://user-images.githubusercontent.com/125143965/236700207-e3dcbafa-d8a3-406c-b0b0-25c444ef32c3.png)
*Protruding autoportal, protruding surface, and a cube dropper gel dropper dropping a gel bomb*
![autoportals_and_gel_bombs](https://user-images.githubusercontent.com/125143965/235436211-0b3e0a82-2925-4031-aaf1-f0b87309592d.png)
*An unnecessarily complicated setup of Schrödinger's cubes used to activate an unlinked autoportal*
![schrodinger's_cubes_and_unlinked_autoportals_2](https://github.com/AxoLabs/BEE2-Axos-Packages/assets/125143965/d944ff63-8452-416c-b7e5-0435af2826e0)
