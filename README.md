# How to Install and Use RuinForge Client

RuinForge Client is a Minecraft Java Edition profile for version 26.3. It adds performance and PvP helper mods, configurable on-screen displays, and a RuinForge-themed Minecraft title screen and resource pack. This guide explains how to install it with XMCL and where to find its main features.

## What you need

Before installing RuinForge, make sure you have:

- A computer that can run Minecraft Java Edition.
- A Microsoft account that owns Minecraft: Java Edition.
- XMCL, the X Minecraft Launcher, installed on your computer.
- The RuinForge Client `.mrpack` file.

Download XMCL from its [official website](https://xmcl.app/). XMCL supports importing Modrinth modpacks, which is the format used for the RuinForge profile. [XMCL source and feature information](https://github.com/Voxelum/x-minecraft-launcher)

RuinForge does not include Minecraft itself or a Minecraft license. You must sign in to XMCL with the Microsoft account that owns Minecraft Java Edition.

## Install RuinForge in XMCL

1. Download the RuinForge Client `.mrpack` file to your computer.
2. Open XMCL and sign in with your Microsoft account. Follow the launcher’s sign-in steps.
3. Import the `.mrpack` into XMCL. You can use its import option or drag the downloaded file into the launcher.
4. XMCL will create a **new game instance** for RuinForge. It does not replace your existing Minecraft profile.
5. Wait for the import and downloads to finish. The profile may need to download Minecraft, Fabric, and its mod files before it is ready.
6. Select the new RuinForge instance in XMCL and press **Play**.

The first launch can take longer while the launcher finishes setting up the game. Keep XMCL open and let its download tasks complete. If the RuinForge profile does not appear right away, check the instance list and the launcher’s task or download area.

## The custom RuinForge menu

The custom screen appears **inside Minecraft after you launch the RuinForge instance**. It does not replace XMCL’s own launcher window.

RuinForge 0.3.2 is set up to select its Ember UI resource pack automatically when imported as a new instance. Its pack adds the RuinForge logo and volcanic panorama to the Minecraft title screen, plus ember-colored details such as the crosshair and selected hotbar slot. It keeps Minecraft’s block textures and does not require shaders.

If the title screen still looks vanilla:

1. Make sure you launched the new **RuinForge 0.3.2** instance, not your old Minecraft profile or an older RuinForge instance.
2. From Minecraft, open **Options → Resource Packs**.
3. Check that **RuinForge Ember UI** appears in the Selected list. If it is on the Available side, move it to Selected and click **Done**.
4. Return to the title screen or restart the game.

## FPS settings

RuinForge includes FPS-Sync. Its refresh-rate syncing behavior can limit the game to your monitor’s refresh rate; for example, a 240 Hz display may result in about 240 FPS in that mode. FPS-Sync also supports custom limits up to 1,000 FPS. [FPS-Sync project details](https://modrinth.com/mod/fps-sync)

To adjust it:

1. Open **Options → Video Settings**.
2. Turn **VSync** off.
3. Find **Max Framerate** and choose **FPS-Sync** at the left end of the slider.
4. Open the FPS-Sync settings and choose a custom limit if you want a cap above your monitor’s refresh rate.
5. If the game still stops at the same number, check your graphics driver’s per-game frame limit as well.

A 1,000 FPS setting is a maximum limit, not a promise that the computer will reach 1,000 FPS. Actual performance depends on your processor, graphics card, memory, resolution, render distance, world, and other settings. A very high FPS cap can also make a computer work harder and run hotter.

## PvP HUD and controls

RuinForge includes client-side displays and settings for PvP:

- Press **Right Shift** to open the PvP Client settings menu. Use it to find and configure the available HUD and client options.
- Type `/keystrokes` in chat to open the Modern Keystrokes settings. Use these settings to show, hide, or position keystrokes and mouse or CPS displays.
- Use Minecraft’s **Options → Video Settings** for the regular crosshair and attack-indicator controls.

The exact choices available can depend on the mods included in the profile. HUD displays are client-side: they change what you see on your screen, not what other players see.

Always follow the rules of the server you join. Some servers restrict particular client features, even when those features only affect your display or controls.

## Troubleshooting

**The game will not start:** Confirm that you selected the RuinForge instance and that XMCL has finished its downloads. If XMCL shows a failed download or launch task, open it and read the error details.

**I imported the pack but cannot find RuinForge:** Check XMCL’s instance list. Modpacks are imported as new instances rather than added to the profile you were already using.

**The Minecraft title screen did not change:** Confirm that you imported version 0.3.2 and launched that new instance. Then check **Options → Resource Packs** and make sure RuinForge Ember UI is Selected.

**My FPS is still around 240:** FPS-Sync may be syncing to a 240 Hz monitor. Select a custom limit in the FPS-Sync settings, turn VSync off, and check for a frame-rate limit in your graphics driver. Even with a 1,000 FPS cap, the computer may not render that many frames.
