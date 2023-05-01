![AxoLabs' UCPs](https://user-images.githubusercontent.com/125143965/220545356-dc6fc292-efe7-4334-b8f5-97226796dd05.png)
# BEE2-Axo's-Packages
Supported version of BEEMod: 2.4.43.0.

Supported styles: OG clean and hybrid. Some items might have variants for other styles, but usually it's because removing the styled variants takes more effort than keeping them.

By the way, if you are going to use one or more of my items in a map, I'd greatly appreciate being credited for making them.

If you want to suggest an enhancement, or report a bug, please read the **contributing guidelines**: https://github.com/AxoLabs/BEE2-Axos-Packages/blob/main/docs/CONTRIBUTING.md

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
### Cube dropper gel dropper
A custom variant of the gel dropper that uses a cube dropper model instead.
- **Cube type** controls the type of the gel the dropper drops.
- **Button type** controls the gel flow.
- **Start enabled** controls whether the dropper starts active or not.
### Personalized hazard identification board
A test sign that can be easily customized. Read the `Instructions.txt` file carefully for more info.
- Use Omnicoder's Sign Maker to generate a template for this item to load: https://developer.valvesoftware.com/wiki/Sign_Maker
### Suspended panel
A surface held by a panel a voxel above the ground.
- Check **start reversed** to make it non-portalable.
### Protruding surface
A portalable surface, protruding out a wall. Comes with a powerful portal magnet implemented into it. **Start reversed** makes the plastic textures darker.
### Autoportal variants
- Protruding autoportal: An orange autoportal mounted on a protruding surface. **Start reversed** makes the plastic textures darker.
- Angled autoportal, an orange autoportal mounted on an angled surface. **Start reversed** makes the plastic textures darker.
- Unlinked autoportal, an autoportal that is not linked to your portal gun. Use the **timer** to select the linkage ID, and **start reversed** to control whether the portal is orange or blue.
- For all three, the start **start enabled** option controls whether the portal starts active or not.
### Stair variants
- Small stairs, which are a set of static stairs, shrunk down to fit a single voxel.
- Half stairs, a set of static stairs which are only half a voxel high. You can line them next to each other so that they reach a full voxel of height. **Start active** controls which part of the voxel they occup: The bottom, or the top.
- Both items have a **start reversed** option, which when checked makes the plastic textures darker.
### New fizzlers
- Portal condensation grid, blocks portal shots and fizzles portals, but does not affect cubes. Comes with a 1997 quality guaranteed signage.
- Concentrated particle field, originally made for PHOBoS. It is a combination of my Portal Condensation Grid and the Physics Repulsion Field. Also comes with a 1997 quality guaranteed signage.
- Purple paint fizzler, a modified version of the default paint fizzler that is purple. Fully compatible with the original. It was also used as a base for all of my custom fizzlers, and was the seed my packages sprouted from.
### Reflection gel fixer
Changes the color of Reflection gel to be gray when splashed on surfaces and your face.

## Screenshots:
*New fizzlers, cube dropper gel droppers and recolored reflection gel*
![axos_ucps_v7](https://user-images.githubusercontent.com/125143965/235433603-a9cf4417-7918-4150-9b5f-051495929abf.png)
*Hybrid style's preview image*
![hybrid_style_1](https://user-images.githubusercontent.com/125143965/235435706-d7532228-1b74-4292-944e-67f6d10d2f16.png)
*Schrödinger's cubes*
![schrodinger's_cubes](https://user-images.githubusercontent.com/125143965/235433342-4fff0be9-8e95-4355-9c35-562f04444b30.png)
*Suspended panels*
![suspended_panels](https://user-images.githubusercontent.com/125143965/235435765-9598e6a9-588e-4260-8a25-b1b29f8b33d4.png)
*Hybrid style in action [Map](https://steamcommunity.com/sharedfiles/filedetails/?id=2961094236)*
![hybrid_style_2](https://user-images.githubusercontent.com/125143965/235436555-d9f7ef68-f394-46f6-b2d9-48bb184c639d.png)
*Hybrid style's exit corridor 4#*
![hybrid_style_4](https://user-images.githubusercontent.com/125143965/235436348-02d82d12-6b9f-4592-8985-22dfd66d75bf.png)
*Stair variants*
![stair_variants](https://user-images.githubusercontent.com/125143965/235435948-5cadf695-c126-4ea1-a83b-29da3c0acefa.png)
*Schrödinger's cubes alongside some geometry items*
![schrodinger's_cubes_and_geometry](https://user-images.githubusercontent.com/125143965/235432974-71fce47e-cc7b-47ed-a023-f11755958695.png)
*Autoportal variants*
![autoportal_variants](https://user-images.githubusercontent.com/125143965/235436062-9aa1d682-ba51-44af-886d-fd0b39df4935.png)
*Hybrid style's entrance corridor 6#*
![hybrid_style_3](https://user-images.githubusercontent.com/125143965/235433086-73aefefa-2c79-47df-b3f7-7f2defad46aa.png)
*Protruding autoportal, protruding surface, and a cube dropper gel dropper dropping a gel bomb*
![autoportals_and_gel_bombs](https://user-images.githubusercontent.com/125143965/235436211-0b3e0a82-2925-4031-aaf1-f0b87309592d.png)
*An unnecessarily complicated setup of Schrödinger's cubes used to activate an unlinked autoportal*
![schrodinger's_cubes_and_unlinked_autoportals](https://user-images.githubusercontent.com/125143965/235436489-838b4939-b813-49e8-bead-19f03c710845.png)
