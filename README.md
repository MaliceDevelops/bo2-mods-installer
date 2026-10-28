# MaliceDevelops BO2 Mods - installer

One installer for all of my Black Ops 2 Zombies (Plutonium) mods. Tick the ones you want: only those are downloaded and installed, and they all work together in the same game, with or without Zombies Declassified.

### [⬇ Download the installer](https://github.com/MaliceDevelops/bo2-mods-installer/releases/latest)

Under **Assets**, download `MaliceDevelops_BO2_Mods_Installer_v<version>.zip`. **This is the download for combining my mods.** Each mod's own page also has a download with just that mod.

![The installer window](images/installer-window.png)

## The mods

| Mod | What it is |
| --- | --- |
| [Apothicon Servant](https://github.com/MaliceDevelops/apothicon-servant-bo2) | Black Ops 3's Shadows of Evil wonder weapon: black holes that drag zombies in and crush them. In the Mystery Box. |
| [Upgraded Cymbal Monkey](https://github.com/MaliceDevelops/upgraded-cymbal-monkey-bo2) | Black Ops 3's Pack-a-Punched Cymbal Monkey: hold your monkeys out at Pack-a-Punch for BO3's bass pulse, dubstep song and bigger explosion. |

## Before you start

- Black Ops 2 with [Plutonium](https://plutonium.pw), and you've played Zombies at least once.
- Windows 10 or 11 and an internet connection. (Anywhere else: follow `README.txt` in the download to install by hand.)
- Optional: **Zombies Declassified**, to play the mods on its Black Ops 1 maps too.

## Install, step by step

### 1. Close Black Ops 2

The installer won't run while the game is open.

### 2. Unzip the download and double-click `Install.bat`

Unzip it anywhere (your Downloads folder is fine). Windows may warn about running a downloaded `.bat`: Install.bat only downloads my mods from github.com/MaliceDevelops, checks every file's SHA-256, and copies them into place. You can read `installer\install.ps1` to see exactly what it does.

### 3. Tick the mods you want

![The mods list](images/mods-list.png)

- Each mod shows its version and whether it's **Not installed**, **Installed**, or has an **Update** waiting.
- The mod's name links to its own page.
- Below each one is its download size; the top right shows the total for what you ticked.
- Only the ticked mods are downloaded, each from its own GitHub page.

### 4. Choose where they go

![Install location](images/install-location.png)

| Choice | What it does | How you play |
| --- | --- | --- |
| **Into Zombies Declassified** | Adds the mods to your Zombies Declassified itself (`mods\dlc5`). | Start Zombies Declassified like always. Its maps are under **Private Match**; the normal BO2 maps work too. **Turn off** gives you plain Zombies Declassified back any time. |
| **Alongside Zombies Declassified** | Your Zombies Declassified stays exactly as it is. The Mods menu gets a second entry with the mods. | Open **Mods**, pick **Zombies Declassified + MaliceDevelops Mods**, then **Private Match** for its maps. Pick the plain **Zombies Declassified** entry to play without the mods. |
| **As a mod of their own** | The mods in their own Mods menu entry, without Zombies Declassified. The only choice if you don't have it. | Open **Mods**, pick **MaliceDevelops Mods**, then play any normal BO2 map. |

**Open the mods folder** opens Plutonium's mods folder (`%LOCALAPPDATA%\Plutonium\storage\t6\mods`), if you want to see what's where.

### 5. Press Install

A console window shows each step: what it downloads, every file it copies, and where. When it says **Installed.**, type **P** and press Enter to open Plutonium (pick Black Ops II Zombies there), or just press Enter to close it.

### 6. Play

Start Black Ops 2 Zombies through Plutonium and play as described in step 4. If you put the mods into or alongside Zombies Declassified, remember that **its own maps are only listed in Private Match**: Solo shows the normal BO2 maps.

## The shortcut

<img src="images/shortcut.png" width="150" alt="The MaliceDevelops BO2 Mods shortcut">

The installer stays on your PC: a **MaliceDevelops BO2 Mods** shortcut on your desktop and in the Start menu opens it again, so you don't need to keep the zip. Use it to add, remove, update, repair or set up the mods. When a newer installer is out, it updates itself first.

## Managing your mods

Open the shortcut. Your installed mods are ticked and marked **Installed**:

![Installed mods](images/mods-installed.png)

- **Add a mod:** tick it and press **Install**.
- **Remove a mod:** untick it and press **Install**, or press its **Uninstall** button.
- **Update:** a mod with a newer version shows **Update from ...**. Press **Install**. Your settings are kept, and nothing that's already up to date is downloaded again.
- **Move them:** pick another install location and press **Install**.

The buttons at the bottom:

![The buttons](images/buttons.png)

| Button | What it does |
| --- | --- |
| **Play** | Opens Plutonium's launcher. |
| **Repair** | Checks every installed file against the published version and downloads again only what's missing or damaged. Your settings are kept. Use it if a mod acts broken, or after a Zombies Declassified update. |
| **Turn off** / **Turn on** | Only for mods installed into Zombies Declassified. **Turn off** sets them aside so Zombies Declassified plays exactly as it came; **Turn on** puts them back. Nothing is downloaded again. |
| **Uninstall all** | Removes all of my mods, the shortcuts and the installer kept on your PC, and puts back anything it set aside. |
| **Cancel** / **Install** | Close without changes / apply what you ticked and chose. |

## Settings

A mod with settings gets a **Settings** button once it's installed:

<img src="images/settings.png" width="620" alt="A mod's settings">

Tick or untick what you want and press **Save**; it takes effect in your next game. **Reset to defaults** puts back the mod's own settings. **Open the file** opens the settings file in Notepad. Your settings are kept when you update.

## Each mod's own download

Each mod's GitHub page also has a download with **just that mod**. Its window shows only that mod, with a link back here:

<img src="images/single-mod-window.png" width="620" alt="A mod's own download">

It installs, updates or removes only that mod, and leaves any other mod of mine alone. Its install locations are the same three. To combine mods, use this installer.

## Uninstall

Close BO2 and press **Uninstall all** in the window (or double-click **Uninstall.bat**). It removes all of my mods, the shortcuts and the installer kept on your PC, and puts back anything it set aside. Your Zombies Declassified is left as it came.

## How it stays lean

- **One small shared file.** BO2 only loads a mod's fastfiles from a couple of fixed slots, so all of my mods share one small file (a few MB: weapon stats, models, animations, effects). With Zombies Declassified, that leaves its second free slot for someone else's mod.
- **Everything heavy is per mod.** Each mod's textures, scripts and sounds are separate files, and only the ticked mods' files are downloaded and installed. The game streams the textures in when they're on screen.
- **Each mod comes from its own GitHub page,** and every file is checked (SHA-256) before anything is installed. Nothing changes until all downloads are done.
- **Alongside Zombies Declassified** copies Zombies Declassified's own small files (about 16 MB) into the second entry; its maps and sounds are shared, not copied. The installer brings that copy up to date every time it runs.

## Good to know

- **Co-op:** everyone in the game needs the same mods installed.
- **Other mods:** script mods like B2OP work fine alongside.
- **After a Zombies Declassified update or install:** open the shortcut and press **Repair**. **Zombies Declassified + MaliceDevelops Mods** gets the update then too.
- **Install by hand:** `README.txt` in the download has the steps.
- **Bugs:** open an issue on that mod's page.

## Credits

The mods are made by **MaliceDevelops** - see each mod's page for its own credits. Built with [OpenAssetTools](https://github.com/Laupetin/OpenAssetTools) and [Plutonium](https://plutonium.pw).

Free fan mods, not affiliated with or endorsed by Activision. Don't sell them.
