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
3. Tick the mods you want in the window.
4. Choose where they go, press **Install** and play:
   - **Into Zombies Declassified:** launch it like always. The mods work on its maps (in **Private Match**) and on the normal BO2 maps. To play Zombies Declassified without them, press **Turn off** (see below).
   - **Into a copy of Zombies Declassified:** your own Zombies Declassified stays exactly as it is. Open **Mods**, pick **Zombies Declassified + MaliceDevelops Mods**, then **Private Match** for its maps.
   - **As a mod of their own** (the only choice without Zombies Declassified): open **Mods**, pick **MaliceDevelops Mods**, then play any map.

The installer stays on your PC: a **MaliceDevelops BO2 Mods** shortcut on your desktop and in the Start menu opens it again, so you don't need to keep the zip. Its **Play** button opens Plutonium's launcher.

Install.bat needs Windows 10 or 11 and an internet connection. To install by hand instead, follow `README.txt` in the download.

Windows may warn about running a downloaded `.bat`. Install.bat only downloads my mods from github.com/MaliceDevelops (checking every file's SHA-256) and copies them; you can read `installer\install.ps1` to check.

## Add, remove or update mods

Open the **MaliceDevelops BO2 Mods** shortcut (or run Install.bat again): tick a mod to add it, untick it (or press its **Uninstall** button) to remove it. It always installs the newest versions, keeps your settings, and doesn't download again what's already up to date. When a newer installer is out, it updates itself first.

## Repair

If a mod acts broken, press **Repair**: it checks every installed file against the published version and downloads again only what's missing or damaged. Your settings are kept.

## Turn off / Turn on

Installed into Zombies Declassified? **Turn off** sets my mods aside so Zombies Declassified plays exactly as it came, and **Turn on** puts them back. Nothing is downloaded again and your settings are kept.

## Settings

A mod with settings gets a **Settings** button in the window once it's installed: tick what you want and press **Save**. **Reset to defaults** puts back the mod's own settings. Your settings are kept when you update.

## Uninstall

Close BO2 and press **Uninstall all** in the window (or double-click **Uninstall.bat**). It removes all of my mods, the shortcuts and the installer kept on your PC, and puts back anything it set aside.

## How it stays lean

- **One small shared file.** BO2 only loads a mod's fastfiles from a couple of fixed slots, so all of my mods share one small file (a few MB: weapon stats, models, animations, effects). With Zombies Declassified, that leaves its second free slot for someone else's mod.
- **Everything heavy is per mod.** Each mod's textures, scripts and sounds are separate files, and only the ticked mods' files are downloaded and installed. The game streams the textures in when they're on screen.
- **Each mod comes from its own GitHub page,** and every file is checked (SHA-256) before anything is installed. Nothing changes until all downloads are done.

## Good to know

- **Co-op:** everyone in the game needs the same mods ticked.
- **Other mods:** script mods like B2OP work fine alongside.
- **Zombies Declassified's maps** are listed in **Private Match** (Solo shows the normal BO2 maps only), in Zombies Declassified and in its copy alike.
- **After a Zombies Declassified update or install:** if a mod stops working, open the shortcut and press **Repair**. A copy of Zombies Declassified gets the update then too.
- **Bugs:** open an issue on that mod's page.

## Credits

The mods are made by **MaliceDevelops** - see each mod's page for its own credits. Built with [OpenAssetTools](https://github.com/Laupetin/OpenAssetTools) and [Plutonium](https://plutonium.pw).

Free fan mods, not affiliated with or endorsed by Activision. Don't sell them.
