<p align="center">
  <img src="release/RuinForge-R-Orange-Logo.png" alt="RuinForge logo" width="128">
</p>

<h1 align="center">RuinForge Client</h1>

<p align="center">
  A Minecraft Java 26.3 profile with a custom ember look, PvP options, and a built-in LAN host menu.
</p>

## Download

**Latest project profile: RuinForge Client 3.26.3 for Minecraft Java 26.3**

- [Download the XMCL profile](release/RuinForge-Client-3.26.3+mc26.3.mrpack)
- [Read the full install and play guide](release/RuinForge-Client-3.26.3-README.md)
- [Download the optional PvP HUD add-ons](release/RuinForge-PvP-Mods-26.3.zip)
- [Download the World Host mod by itself](release/RuinForge-World-Host-3.26.3+mc26.3.jar)
- [Check the profile SHA-256](release/RuinForge-Client-3.26.3+mc26.3.mrpack.sha256)

The `.mrpack` is an importable Minecraft profile, **not a standalone launcher installer**. Use XMCL to install and run it.

## Install with XMCL

1. Install and open [XMCL](https://xmcl.app/).
2. Sign in with a Microsoft account that owns Minecraft Java Edition.
3. Import `RuinForge-Client-3.26.3+mc26.3.mrpack` as a new instance.
4. Let XMCL finish installing Minecraft 26.3, Fabric, and the profile files.
5. Select **RuinForge Client 3.26.3** and click **Play**.

The profile installs as a separate instance and does not replace other Minecraft profiles or worlds.

## Features

- **RuinForge Ember UI:** custom title screen styling, reticle, and hotbar accents.
- **PvP resource packs:** SpearMace, Sword, Crystal, Mace, SMP, UHC, Axe and Shield, and Legacy 1.8. Enable packs in **Options → Resource Packs**.
- **Performance and HUD mods:** Fabric mods are listed with their original names in `RuinForge-Credits.txt` inside the imported instance.
- **RuinForge World Host:** open a single-player world to LAN from the in-game pause menu. Choose whether visitors can use commands; they are off by default.
- **Optional PvP HUD add-ons:** the separate bundle contains 20 information displays and a shared core. Install only the displays you want.

FPS depends on your computer, settings, drivers, and monitor. A 1,000 FPS setting is a maximum cap, not a promise that the game will render 1,000 frames per second. Turn VSync off and choose a custom FPS limit in **Options → Video Settings** if you want to set a cap above your monitor's refresh rate.

## Host a world with a remote friend

Both players need to launch the **same RuinForge version through XMCL**. They do not need to join the same XMCL room.

1. In XMCL, open **Multiplayer → Manual Connect → Initiate Connection**. Start it and wait for the connection token to finish generating.
2. Send the token privately to your friend. They open **Multiplayer → Manual Connect → Join Manual**, paste it, and generate an answer token.
3. Have your friend send the answer token back privately. Paste it into the initiate window and wait for XMCL to show that the connection is active.
4. The host opens a single-player world, presses **Esc**, selects **RuinForge: Host World**, then chooses **Start Hosting**.
5. The friend opens Minecraft's **Multiplayer → LAN** list and joins the advertised world.

Keep XMCL open and the direct connection active while playing. This hosts the world on the player's own computer; RuinForge does not provide a paid server. Direct connections can be blocked by some router or firewall settings. XMCL may report when its relay service is needed. Share connection tokens only with the intended friend.

## Install the optional PvP HUD add-ons

1. Download and extract `RuinForge-PvP-Mods-26.3.zip`.
2. In XMCL, open the RuinForge instance folder and its `mods` folder.
3. Copy the feature JARs you want from the bundle's `mods` folder into the instance's `mods` folder. Keep **RuinForge PvP HUD Core** installed with any feature JARs.
4. Keep Fabric API installed and restart Minecraft.

These add-ons display information such as FPS, ping, coordinates, keystrokes, armor, health, and item counts. They do not automate combat or modify network packets. Follow the rules of the server you play on.

## Build the World Host mod

The original World Host mod source is in [`apps/launcher/world-host-mod`](apps/launcher/world-host-mod). Build it on a Windows development setup with Java 25 and the Minecraft 26.3 mapped jars plus Fabric dependencies cached by Gradle:

```powershell
powershell -ExecutionPolicy Bypass -File apps/launcher/world-host-mod/build.ps1
```

The JAR is written to `apps/launcher/world-host-mod/build/`. The profile builder at `apps/launcher/build-modpack.ps1` includes it when building version 3.26.3. Community mods are distributed under their own names and license terms; see the included credits and each project's license.

## Troubleshooting

- **No Host World button:** launch RuinForge Client 3.26.3 and open a single-player world before pressing **Esc**. The option is not shown while connected to a multiplayer server.
- **Friend cannot see the hosted world:** first connect in XMCL Manual Connect, then stop and restart hosting. Allow Java through the host computer's firewall if Windows asks.
- **XMCL cannot connect peers:** router or firewall rules may prevent a direct connection. Follow XMCL's relay guidance if shown.
- **Custom menu look is missing:** confirm **RuinForge Ember UI** is selected in **Options → Resource Packs**.
- **Game fails to start:** check XMCL's task list for failed downloads and wait for profile setup to finish.

## Credits and project status

Community mods keep their original names and are credited in `RuinForge-Credits.txt` in the installed profile. The RuinForge menu styling, Host World mod, and PvP textures are project assets. Minecraft is a Microsoft trademark. RuinForge is independent and is not affiliated with Mojang, Microsoft, or XMCL.
