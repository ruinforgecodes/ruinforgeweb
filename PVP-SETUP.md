# RuinForge PvP and FPS settings

The 0.3.2 profile adds the RuinForge main menu and Ember UI resource pack alongside the client-side PvP menu, configurable keystrokes/CPS HUD, and FPS cap. Import it as a **new instance** so your current playable instance stays available.

## RuinForge Ember UI

The profile selects RuinForge Ember UI automatically. Launch the new instance and the custom title screen should appear immediately.

The pack adds an original RuinForge title logo and volcanic panorama behind the main menu, while leaving the familiar Minecraft menu buttons in place. It also adds an ember reticle and selected hotbar frame, a recolored diamond sword, ember sun, pack icon, and original menu splashes. It keeps vanilla block textures and does not add shaders, so it retains Minecraft's blocky look without shader performance cost.

## FPS cap

1. Open **Options → Video Settings**.
2. In **Max Framerate**, choose the new **FPS-Sync** option at the left end to enable the mod.
3. Set a custom cap up to 1,000 FPS in the FPS-Sync settings.

If your FPS stops at 240, FPS-Sync may be matching a 240 Hz monitor; that is its default monitor-sync behavior. Use its custom limit instead. A 1,000 FPS cap is only a ceiling, not a promise—the computer must be able to render that fast, and a graphics-driver cap can also limit it. FPS-Sync supports Minecraft 26.3 and custom caps up to 1,000 FPS ([official project page](https://modrinth.com/mod/fps-sync)).

## PvP settings

- Press **Right Shift** to open Tenite's PvP Client menu. Its HUD editor lets you toggle, move, and scale the FPS, ping, armor, and potion displays, and configure options such as zoom, toggle sprint, hit color, and view model.
- Type `/keystrokes` in chat to open Modern Keystrokes settings. Toggle or move the key, mouse/CPS, FPS, and ping overlay components.
- Minecraft's standard crosshair and attack-indicator settings remain under **Options → Video Settings**.

These are client-side displays and controls. Server rules differ, so check them before using optional camera features such as Freelook.
