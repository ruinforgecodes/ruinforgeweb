# How to Install and Use RuinForge Client

RuinForge Client 0.4.0 is a Minecraft Java Edition profile for **Minecraft 26.3**. It combines performance-focused Fabric mods, PvP HUD options, and an original ember-forged Minecraft interface while keeping the familiar block-built world.

## Download RuinForge

[Download RuinForge Client 0.4.0 for Minecraft 26.3](release/RuinForge-Client-0.4.0+mc26.3.mrpack)

## What you need

Before installing RuinForge, make sure you have:

- A computer that can run Minecraft Java Edition.
- A Microsoft account that owns Minecraft: Java Edition.
- XMCL, the X Minecraft Launcher, installed on your computer.
- The RuinForge Client `.mrpack` profile from the download link above.

RuinForge does not include Minecraft itself or a Minecraft license. Sign in to your launcher with the Microsoft account that owns Minecraft Java Edition. You can get XMCL from its [official download page](https://xmcl.app/).

## Install RuinForge in XMCL

1. Download the RuinForge `.mrpack` file to your computer.
2. Open XMCL and sign in with your Microsoft account.
3. Import the `.mrpack` using XMCL's import option, or drag the file into the launcher.
4. XMCL creates a **new game instance** for RuinForge. It does not replace your other Minecraft profiles or worlds.
5. Wait for the import and downloads to finish. The launcher needs to install Minecraft, Fabric, and the profile's mod files.
6. Select the new **RuinForge Client 0.4.0** instance and press **Play**.

The first launch can take longer while the launcher finishes downloading and setting up the files. If the profile does not appear right away, check XMCL's instance list and its task or download area.

## The RuinForge title screen and menu

The RuinForge menu appears **inside Minecraft after you launch the RuinForge instance**. It does not replace XMCL's own launcher window.

Version 0.4.0 automatically selects RuinForge Ember UI in a newly imported profile. It adds:

- An original RuinForge title logo and volcanic panorama.
- Ember-styled Minecraft buttons, sliders, tabs, and text fields.
- Dark basalt menu panels and warmer section dividers.
- Ember details for the crosshair and selected hotbar slot.
- A recolored diamond sword, ember sun, pack icon, and original menu splashes.

Minecraft's block textures remain vanilla, and the pack does not require shaders.

If the title screen still looks like the default Minecraft screen:

1. Confirm that you launched the new **0.4.0** instance, not your old Minecraft profile or an older RuinForge instance.
2. In Minecraft, open **Options → Resource Packs**.
3. Check that **RuinForge Ember UI** is in the **Selected** list. If it is under Available, move it to Selected and click **Done**.
4. Return to the title screen or restart the game.

## PvP HUD and controls

RuinForge includes client-side PvP displays and options:

- Press **Right Shift** to open Tenite's PvP Client settings. From there, configure supported armor, potion-effect, ping, and FPS displays, and available options such as zoom, toggle sprint, hit color, and view model.
- Type `/keystrokes` in chat to open Modern Keystrokes settings. Use them to show, hide, or position keystrokes, mouse buttons, CPS, FPS, and ping displays.
- Open **Options → Video Settings** for Minecraft's standard crosshair, attack-indicator, and video controls.

These displays are client-side: they change what you see, not what other players see. Server rules vary, so check them before using optional features such as Freelook.

## FPS settings

RuinForge includes FPS-Sync. In its default sync mode, it can match the monitor's refresh rate. For example, a 240 Hz display may result in a cap around 240 FPS. FPS-Sync also supports custom caps up to 1,000 FPS. See the [FPS-Sync project information](https://modrinth.com/mod/fps-sync).

To adjust the frame-rate cap:

1. Open **Options → Video Settings** and turn **VSync** off.
2. In **Max Framerate**, choose **FPS-Sync** at the far left of the slider.
3. Open the FPS-Sync settings and choose a custom cap if you want a limit above your monitor's refresh rate.
4. If FPS still stops at the same number, check for a per-game frame limit in your graphics-driver settings.

A 1,000 FPS cap is a maximum limit, not a promise that the computer will reach 1,000 FPS. Actual performance depends on the processor, graphics card, memory, resolution, render distance, world, and other settings. A very high cap can make the computer work harder and run hotter.

## Troubleshooting

**The game will not start:** Confirm that you selected the RuinForge instance and that XMCL has finished its downloads. If XMCL shows a failed download or launch task, open it and read the error details.

**I imported the profile but cannot find RuinForge:** Look in XMCL's instance list. Modpacks are imported as new instances; they are not merged into your currently selected profile.

**The Minecraft title screen did not change:** Check that you imported version 0.4.0 and launched that new instance. Then open **Options → Resource Packs** and confirm RuinForge Ember UI is Selected.

**My FPS is still around 240:** FPS-Sync may be matching a 240 Hz monitor. Turn VSync off, select a custom cap in FPS-Sync, and check for a frame-rate limit in your graphics driver. Even with a 1,000 FPS cap, the computer may not render that many frames.

## RuinForge desktop launcher

The separate RuinForge-branded Windows launcher is still being prepared. Its Microsoft sign-in needs RuinForge's own Microsoft app registration before a playable public release can be built. For now, use XMCL with the RuinForge profile. Do not distribute the old 0.1.0 development installer as a ready-to-play launcher.

## Project notice

RuinForge Client is an independent community project and is not affiliated with or endorsed by Mojang or Microsoft. Minecraft is a trademark of Microsoft.
