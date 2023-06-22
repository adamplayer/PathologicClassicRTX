# PathologicClassicRTX

A (Work In Progress) RTX-Remix mod for the classic game Pathologic.

## Installation
1. Set up the game. _Recommended version: [Pathologic Classic HD](https://www.gog.com/en/game/pathologic_classic_hd)_
2. Download **bridge-remix** (`bf0984b`) from GitHub (must be logged in): [bridge-remix](https://github.com/NVIDIAGameWorks/bridge-remix/actions/runs/5225910924)
3. Extract the contents of **bridge-remix** to `<game-folder>\bin\Final`
4. Download **dxvk-remix** (`0a9d916`) from GitHub (must be logged in): [dxvk-remix](https://github.com/NVIDIAGameWorks/dxvk-remix/actions/runs/5272240553)
5. Extract the contents of **dxvk-remix** to `<game-folder>\bin\Final\.trex`
6. Download the custom version of **DXVK-Remix** (`0a9d916`) with ImGui support for lightmap textures, or build it yourself: [Custom DXVK-Remix](https://github.com/anchorlightforge/dxvk-remix/releases/tag/qol-improvement)
7. Extract `d3d9.dll` and `d3d9.pdb` to `<game-folder>\bin\Final\.trex`
8. Use the provided files to configure the game.

## Issues
- [ ] Lightmaps still present in many scenes.
- [ ] Invisible water.
- [ ] Broken skyboxes.
- [ ] Lightmap tags result in fullbright issues - see [Issue #210](https://github.com/NVIDIAGameWorks/rtx-remix/issues/210)
- [ ] Original lighting mostly lost with removal of lightmaps -- a lighting replacement will be needed in the future to fix this.
- [ ] Lights do not carry over to Remix renderer.
- [ ] Frequent crashes while loading between areas.
- [ ] Skyboxes are entirely broken and artifacting is common.
- [ ] Geometry hashes for floors, walls, and ceilings are unstable.
- [ ] Whenever the mouse moves in outdoor areas, geometry deforms and wobbles.
- [ ] Texture reading is broken when dealing with forced metallic/opacity values.

## Resources for Debugging
- [Useful console commands](https://pathologic.fandom.com/wiki/Console_Commands)
- [Modding info (wiki)](https://pathologic.fandom.com/wiki/Debug/Modding/Pathologic#Extracting_Game_Files)
- [Open-Source file viewer](https://github.com/somevideoguy/pathologic)
- [Forum Post - Mod Syntax](https://forum.ice-pick.com/viewtopic.php?f=12&t=4650#p58685)
