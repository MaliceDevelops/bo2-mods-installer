# MaliceDevelops BO2 Mods - installer

One installer for all of my Black Ops 2 Zombies (Plutonium) mods. Tick the ones you want: only those are downloaded and installed, and they all work together in the same game, with or without Zombies Declassified.

### [⬇ Download the installer](https://github.com/MaliceDevelops/bo2-mods-installer/releases/latest)

Under **Assets**, download `MaliceDevelops_BO2_Mods_Installer_v<version>.zip`. Every mod's own download has the same installer in it, so you can also start from a mod's page.

## The mods

| Mod | What it is |
| --- | --- |
| [Apothicon Servant](https://github.com/MaliceDevelops/apothicon-servant-bo2) | Black Ops 3's Shadows of Evil wonder weapon: black holes that drag zombies in and crush them. In the Mystery Box. |
| [Upgraded Cymbal Monkey](https://github.com/MaliceDevelops/upgraded-cymbal-monkey-bo2) | Black Ops 3's Pack-a-Punched Cymbal Monkey: hold your monkeys out at Pack-a-Punch for BO3's bass pulse, dubstep song and bigger explosion. |

## Install

1. Close Black Ops 2.
2. Unzip the download anywhere and double-click **Install.bat**.
3. Tick the mods you want in the window and press **Install**.
4. Play:
   - **With Zombies Declassified:** launch it like always. The mods work on its maps and on the normal BO2 maps.
   - **Without it:** start Zombies, open **Mods**, pick **MaliceDevelops Mods**, then play any map.

Install.bat needs Windows 10 or 11 and an internet connection. To install by hand instead, follow `README.txt` in the download.

Windows may warn about running a downloaded `.bat`. Install.bat only downloads my mods from github.com/MaliceDevelops (checking every file's SHA-256) and copies them; you can read `installer\install.ps1` to check.

## Add, remove or update mods

Run **Install.bat** again: tick a mod to add it, untick it to remove it. It always installs the newest versions and keeps your settings.

## Uninstall

Close BO2 and double-click **Uninstall.bat**. It removes all of my mods and puts back anything it set aside.

## How it stays lean

- **One small shared file.** BO2 only loads a mod's fastfiles from a couple of fixed slots, so all of my mods share one small file (a few MB: weapon stats, models, animations, effects). With Zombies Declassified, that leaves its second free slot for someone else's mod.
- **Everything heavy is per mod.** Each mod's textures, scripts and sounds are separate files, and only the ticked mods' files are downloaded and installed. The game streams the textures in when they're on screen.
- **Each mod comes from its own GitHub page,** and every file is checked (SHA-256) before anything is installed. Nothing changes until all downloads are done.

## Good to know

- **Co-op:** everyone in the game needs the same mods ticked.
- **Other mods:** script mods like B2OP work fine alongside.
- **After a Zombies Declassified update or install:** if a mod stops working, run Install.bat again.
- **Bugs:** open an issue on that mod's page.

## Credits

The mods are made by **MaliceKy** - see each mod's page for its own credits. Built with [OpenAssetTools](https://github.com/Laupetin/OpenAssetTools) and [Plutonium](https://plutonium.pw).

Free fan mods, not affiliated with or endorsed by Activision. Don't sell them.
