# Oblivion Remastered
[Steam](https://store.steampowered.com/app/2623190/The_Elder_Scrolls_IV_Oblivion_Remastered/)

## Setup
- UEVR (nightly 1046)
- FSR4 with OptiScaler
- Virtual Desktop

### UEVR
Since the game does not natively support VR, we use [UEVR](https://github.com/praydog/UEVR). Oblivion Remastered uses UnrealEngine 5 for the graphics part.

We use the [nightly build 1046](https://github.com/praydog/UEVR-nightly/releases/tag/nightly-01046-5d12735a10c146ea7ff73ac2c37bdd529bc1214d).

Download and extract it somewhere.

Next we want to use the "6dof Attached Items Profile(Right hand Aiming), FOR NIGHTLY 1046" profile pinned by Pande4360 here: https://discordapp.com/channels/747967102895390741/1361794273707561050

We import this in UEVR.

### OptiScaler
We install [OptiScaler](https://github.com/cdozdil/OptiScaler) into our game folder.

Then we need to find the `amdxcffx64.dll` inside our windows folder and copy it next to optiscaler.

I also prefer to set `ShortcutKey=36` in the `optiscaler.ini` to use the home key to open optiscaler as it would conflict with the UEVR default key.

### Mods
- Controller Icons for my Quest: https://discord.com/channels/747967102895390741/1361794273707561050/1364436781205950535
- [Better HUD](https://www.nexusmods.com/oblivionremastered/mods/13)
- [Less Ugly Black Infoboxes](https://www.nexusmods.com/oblivionremastered/mods/222)
- [No Vignettes](https://www.nexusmods.com/oblivionremastered/mods/177)
- [No Hit Marker](https://www.nexusmods.com/oblivionremastered/mods/18)
- [Better Reticle](https://www.nexusmods.com/oblivionremastered/mods/164)
- [Ultimate Engine Tweaks](https://www.nexusmods.com/oblivionremastered/mods/35)
- [Oblivion Optimizer](https://www.nexusmods.com/oblivionremastered/mods/39)

### Virtual Desktop
We will try to run it at Godlike resolution with 90FPS with SSW active.

That should give us high visual clarity while maintaining a somewhat smooth experience.

### FSR
We try to go for Quality

### Ingame settings
- Hardware RT off
- Low settings for effects and post processing
- View distance high
- Rest medium
