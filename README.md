# PathologicClassicRTX
A RTX-Remix mod for the classic game Pathologic.

### INSTALLATION:
- Set up the game.  Recommended version: https://www.gog.com/en/game/pathologic_classic_hd
- Download bridge-remix bf0984b from GitHub (must be logged in): https://github.com/NVIDIAGameWorks/bridge-remix/actions/runs/5225910924
- Extract bridge-remix to <game-folder>\bin\Final
- Download dxvk-remix 0a9d916 from GitHub (must be logged in): https://github.com/NVIDIAGameWorks/dxvk-remix/actions/runs/5272240553
- Extract dxvk-remix to to <game-folder>\bin\Final\.trex
- Download custom version of DXVK-Remix 0a9d916 with ImGui support for lightmap textures, or build it yourself: https://github.com/anchorlightforge/dxvk-remix/releases/tag/qol-improvement
- Extract d3d9.dll and d3d9.pdb to <game-folder>\bin\Final\.trex
- Use the files included to configure the game.

### ISSUES:
- Lightmaps still present in many scenes.
- Invisible water.
- Broken skyboxes.
- Lightmap tags result in fullbright issues- see Issue #210 https://github.com/NVIDIAGameWorks/rtx-remix/issues/210
- Original lighting mostly lost with removal of lightmaps-- a lighting replacement will be needed in the future to fix this.
- Lights do not carry over to Remix renderer.
- Frequent crashes while loading between areas.
- Skyboxes are entirely broken and artifacting is common.
- Geometry hashes for floors, walls, and ceilings are unstable.
- Whenever the mouse moves in outdoor areas, geometry deforms and wobbles.
- Texture reading is broken when dealing with forced metallic/opacity values.

### RESOURCES FOR DEBUGGING
- [Useful console commands](https://pathologic.fandom.com/wiki/Console_Commands)
- [Modding info (wiki)](https://pathologic.fandom.com/wiki/Debug/Modding/Pathologic#Extracting_Game_Files)
- [Open-Source file viewer](https://github.com/somevideoguy/pathologic)
- [Forum Post - Mod Syntax](https://forum.ice-pick.com/viewtopic.php?f=12&t=4650#p58685)
- 
