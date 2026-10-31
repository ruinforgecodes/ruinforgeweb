# RuinForge Client

RuinForge Client is a Minecraft Java Edition profile for version 26.3. It is designed to improve performance, add PvP utility tools, and bring a custom RuinForge-themed look to the game.

## Overview

RuinForge is built for players who want:

- Faster and smoother gameplay
- PvP-focused HUD and control options
- A distinct RuinForge-style title screen and UI
- A simple, importable client profile for Java Edition

This project includes a custom Fabric-based client setup with performance mods and visual enhancements, while keeping the overall Minecraft experience familiar.

## What you need

Before installing RuinForge, make sure you have:

- A computer that can run Minecraft Java Edition
- A Microsoft account that owns Minecraft: Java Edition
- XMCL, the X Minecraft Launcher, installed on your computer
- The RuinForge Client `.mrpack` file

Download XMCL from the official XMCL website. XMCL supports importing Modrinth modpacks, which is the format used for the RuinForge profile.

RuinForge does not include Minecraft itself or a Minecraft license. You must sign in to XMCL with the Microsoft account that owns Minecraft Java Edition.

## Installation

1. Download the RuinForge Client `.mrpack` file to your computer.
2. Open XMCL and sign in with your Microsoft account.
3. Import the `.mrpack` into XMCL using the launcher’s import option or by dragging the file into the launcher.
4. XMCL will create a new game instance for RuinForge. This does not replace your existing Minecraft profile.
5. Wait for the import and downloads to finish.
6. Select the new RuinForge instance in XMCL and press Play.

The first launch can take longer while the launcher finishes setting up the game. Keep XMCL open and let its download tasks complete. If the RuinForge profile does not appear immediately, check the launcher’s instance list and import status.

## Custom RuinForge menu

The custom RuinForge screen appears inside Minecraft after you launch the RuinForge instance. It does not replace XMCL’s own launcher.

RuinForge 0.3.2 is set up to select its Ember UI resource pack automatically when imported as a new instance. This pack adds the RuinForge logo and volcanic theme to the Minecraft title screen.

If the title screen still looks vanilla:

1. Make sure you launched the new RuinForge 0.3.2 instance, not an older profile.
2. Open Minecraft and go to Options → Resource Packs.
3. Check that RuinForge Ember UI appears in the Selected list.
4. If it is on the Available side, move it to Selected and click Done.
5. Return to the title screen or restart the game.

## FPS settings

RuinForge includes FPS-Sync. Its refresh-rate syncing behavior can limit the game to your monitor’s refresh rate. For example, a 240 Hz display may result in roughly 240 FPS in that mode.

To adjust it:

1. Open Options → Video Settings.
2. Turn VSync off.
3. Find Max Framerate and choose FPS-Sync at the left end of the slider.
4. Open the FPS-Sync settings and choose a custom limit if you want a cap above your monitor’s refresh rate.
5. If the game still stops at the same number, check your graphics driver’s per-game frame limit as well.

A 1,000 FPS setting is a maximum limit, not a guarantee that your computer will reach 1,000 FPS. Actual performance depends on your processor, graphics card, memory, resolution, render distance, and world conditions.

## PvP HUD and controls

RuinForge includes client-side displays and settings for PvP:

- Press Right Shift to open the PvP Client settings menu.
- Type `/keystrokes` in chat to open the Modern Keystrokes settings.
- Use Minecraft’s Options → Video Settings for regular crosshair and attack indicator controls.

The exact choices available depend on the mods included in the profile. HUD displays are client-side: they change what you see on your screen, not what other players see.

Always follow the rules of the server you join. Some servers restrict certain client features, even when those features only affect your display or controls.

## Troubleshooting

### The game will not start
Confirm that you selected the RuinForge instance and that XMCL has finished downloading everything. If XMCL shows a failed download or launch task, open it and read the error details.

### I imported the pack but cannot find RuinForge
Check XMCL’s instance list. Modpacks are imported as new instances rather than added to the profile you were already using.

### The Minecraft title screen did not change
Confirm that you imported version 0.3.2 and launched that new instance. Then check Options → Resource Packs and make sure RuinForge Ember UI is selected.

### My FPS is still around 240
FPS-Sync may be syncing to a 240 Hz monitor. Select a custom limit in the FPS-Sync settings, turn VSync off, and check for a frame-rate limit in your graphics driver settings.

## Repository structure

This repository includes:

- `README.md` — installation and usage guide
- `index.html` — the project landing page
- `styles.css` — website and visual styling
- `assets/` — branding and menu artwork
- `downloads/` — downloadable client files
- `PVP-SETUP.md` — PvP setup information

## Project note

RuinForge Client is an independent community project. Minecraft is a trademark of Microsoft; RuinForge is not affiliated with or endorsed by Mojang or Microsoft.

This project is intended for players who own Minecraft Java Edition and want a custom client setup tailored for performance and PvP gameplay.
