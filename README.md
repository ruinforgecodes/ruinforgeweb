RuinForge Client 2.26.3

RuinForge Client 2.26.3 is a Minecraft Java profile for **Minecraft 26.3**. It combines community Fabric mods with the RuinForge pixel-art menu and eight optional PvP texture packs. Community mods keep their original names and are credited in `RuinForge-Credits.txt`.

## Download the profile

[Download RuinForge Client 2.26.3](RuinForge-Client-2.26.3+mc26.3.mrpack)

The `.mrpack` is a game profile, not a standalone launcher installer. You need Minecraft Java Edition and a compatible launcher such as [XMCL](https://xmcl.app/). Sign in with a Microsoft account that owns Minecraft Java Edition.

## Install in XMCL

1. Download the `.mrpack` above.
2. Install and open XMCL.
3. Sign in with the Microsoft account that owns Minecraft Java Edition.
4. Import the `.mrpack` as a new instance.
5. Wait for XMCL to install Minecraft 26.3, Fabric, and the profile's listed mods.
6. Select **RuinForge Client 2.26.3** and press **Play**.

Importing creates a separate instance and does not replace your other Minecraft profiles or worlds.

## RuinForge menu and resource packs

The RuinForge menu appears inside Minecraft after launching the new instance. **RuinForge Ember UI** is selected automatically. It adds the pixel-art title mark, ember-and-basalt menu styling, reticle and hotbar accents.

The profile also includes eight optional PvP packs: SpearMace, Sword, Crystal, Mace, SMP, UHC, Axe and Shield, and Legacy 1.8. To use one, open **Options → Resource Packs**, move the pack from Available to Selected, then click **Done**. These packs change visuals only.

## Add the 20 RuinForge PvP HUD add-ons

[Download the installable PvP add-on bundle](RuinForge-PvP-Mods-26.3.zip). It contains 20 individual information HUD mods and one shared **RuinForge PvP HUD Core** mod. The add-ons are separate from the `.mrpack` profile.

1. Extract the bundle.
2. Open the RuinForge instance folder in XMCL, then open its `mods` folder.
3. Copy the JARs from the bundle's `mods` folder into the instance's `mods` folder. Keep the Core JAR installed with any of the feature JARs you use.
4. Keep Fabric API installed, then restart the instance.

The add-ons show information such as FPS, ping, coordinates, keystrokes, armor, health, item counts, attack strength, and movement. Each feature has its own JAR; remove a feature JAR to hide that display. Some overlap with the profile's existing PvP HUD mods, so turn off duplicate displays in those mods if needed.

These are client-side information displays. They do not automate combat, change reach, or modify packets. Follow the rules of the server you play on.

## FPS settings

RuinForge includes FPS-Sync. Its default sync mode can match your monitor's refresh rate, so a 240 Hz monitor can result in a cap around 240 FPS. For a custom limit:

1. Open **Options → Video Settings** and turn **VSync** off.
2. Select **FPS-Sync** in the **Max Framerate** control.
3. Open the FPS-Sync settings and set the custom cap you want.
4. If the limit remains unchanged, check your graphics driver for another frame-rate cap.

A 1,000 FPS cap is only a maximum limit. The computer may not be able to render that many frames, and actual FPS depends on the hardware and game settings.

## Troubleshooting

**The RuinForge menu does not appear:** Make sure you launched the new 2.26.3 instance. Open **Options → Resource Packs** and confirm **RuinForge Ember UI** is Selected.

**The add-ons do not appear:** Confirm the feature JARs and `RuinForge PvP HUD Core` are in this instance's `mods` folder, and that Fabric API is installed.

**The game does not start:** Check XMCL's task or download area for failed downloads. Confirm you selected the RuinForge instance and allowed its setup to finish.

**The FPS cap stays near the monitor rate:** Turn VSync off and choose a custom FPS-Sync limit. Also check the graphics driver for a separate cap.

## Credits and launcher status

## The profile contains third-party Fabric mods with their original names and download references. See `RuinForge-Credits.txt` in the imported instance folder and each project page for current license terms. The RuinForge menu art and PvP textures are original project assets.

## The separate RuinForge-branded desktop launcher is still in development. For now, use XMCL or another launcher that supports `.mrpack` imports. RuinForge is independent and is not affiliated with Mojang or Microsoft. Minecraft is a Microsoft trademark.

## RUINFORGE CLIENT 2.26.3 — CREDITS
Minecraft Java Edition 26.3 / Fabric

## RuinForge original project assets
- RuinForge Ember UI: pixel-art logo, title screen, widgets, icons, reticle, menu copy, and packaging scripts.
- RuinForge PvP texture packs: original item and shield textures.
- RuinForge FPS Booster: original item and Non-Fake
Third-party mods included by reference in this profile
- Sodium — https://modrinth.com/mod/sodium
- Lithium — https://modrinth.com/mod/lithium
- FerriteCore — https://modrinth.com/mod/ferrite-core
- ImmediatelyFast — https://modrinth.com/mod/immediatelyfast
- Entity Culling — https://modrinth.com/mod/entityculling
- FPS Sync — https://modrinth.com/mod/fps-sync
- PvP Client — https://modrinth.com/mod/DMngTx3u
- Modern Keystrokes — https://modrinth.com/mod/modern-keystrokes
- BetterF3 — https://modrinth.com/mod/betterf3
- Mod Menu — https://modrinth.com/mod/modmenu
- Cloth Config — https://modrinth.com/mod/cloth-config
- Fabric API — https://modrinth.com/mod/fabric-api

## RuinForge does not copy, rename, or claim authorship of these mods. The
## modrinth.index.json records each selected version, download URL, and file hash.
## Check each project page for its current license and redistribution terms. The
## .mrpack references the original downloads.

## RuinForge is an independent community project, not affiliated with Mojang or
## Microsoft. Players need a valid Minecraft Java Edition license.
