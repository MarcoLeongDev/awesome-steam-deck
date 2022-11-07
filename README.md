# Awesome Steam Deck

This is a curation of useful resources on Steam Deck.

*🚧 Under construction 🚧*

## Table of content
- [Awesome Steam Deck](#awesome-steam-deck)
  * [Steam Artworks](#steam-artworks)
  * [Proton](#proton)
  * [Compatibility](#compatibility)
  * [Optimisation](#optimisation)
  * [Emulators](#emulators)
  * [Install games from non-steam platforms](#install-games-from-non-steam-platforms)
  * [SteamOS](#steamos)
  * [Softwares](#softwares)
  * [Knowledge checks](#knowledge-checks)
  * [Perhaps ...](#perhaps-)

---
## Steam Artworks
Artwork is not a requirement for a game to function. Yet, Steam library allows artworks to be configured with both Steam games and Non-Steam games. This makes the library more beautiful, personalised and more user-friendly. In general, five types of artworks are configurable for a game/app in Steam Library, namely: poster (portrait), banner (landscape), logo, icon and hero (background). SteamGridDB is a common site to find and share artworks.
- [SteamGridDB](https://www.steamgriddb.com/): For sharing custom video game assets and personalize your steam library 

---

## Proton
Proton is a compatibility layer for Microsoft Windows games to run on Linux-based operating systems. SteamOS comes with a version of Proton by default. In general, the latest version tends to have a larger list of compatible games and the default Proton version may not be the latest. [ProtonUp-QT](https://davidotek.github.io/protonup-qt/) is an App to manage Proton versions. After a version is installed, it will be accessible by Steam, Lutris, Heroic game launcher, etc
- [ProtonUp-QT](https://davidotek.github.io/protonup-qt/): install from [Flatpak](https://flathub.org/apps/details/net.davidotek.pupgui2) via Discover store

---

## Compatibility 
- [ProtonDB](https://www.protondb.com/): Check if a game is compatible with Steam Deck
---

## Optimisation
- [FSR](https://en.m.wikipedia.org/wiki/GPUOpen#FidelityFX_Super_Resolution): FidelityFX Super Resolution (FSR) is used to upsample an input image into a higher resolution. This generally improves performance and results in higher FPS. Some games support FSR natively, while the Steam Deck is able to use FSR regardless if the game supports it. FSR can be activated by enabling the setting in Steam Deck and by setting the game resolution lower than the native 1280x800 ratio of 16:10. To maintain the ratio of 16:10 and avoid black bars on top and bottom, these are some of the resolutions 1152x720, 960x600, 800x500, 768x480, 640x400, etc

---

## Emulators
- [EmuDeck](https://www.emudeck.com): A collection of scripts that allows you to autoconfigure your Steam Deck.
  - [Offical installation guide](https://www.emudeck.com/#how_to_install)
  - [Video installation guide](https://m.youtube.com/watch?v=AvzSHxccmIg)

---

## Install games from non-steam platforms
The convention is to use Heroic for gaming mode with Epic game and GOG; Lutris for other game stores and those install/run with .exe or ISO
- [Heroic game launcher](https://heroicgameslauncher.com/): An Open Source GOG and Epic games launcher for SteamDeck. Suitable for Launching from Steam Deck gaming mode
  - Install from [Flatpak](https://flathub.org/apps/details/com.heroicgameslauncher.hgl) via Discover store
- [Lutris](https://lutris.net/): An Open Source Game installer, including GOG, Epic games, Humble Bundles, install from .exe or ISO. Suitable for custom installation and more advanced configuration
  - Install from [Flatpak](https://flathub.org/apps/details/net.lutris.Lutris) via Discover store

---

## SteamOS
- [SteamOS on non-steam device](https://m.youtube.com/watch?v=Xr2BO4IPqro)
- [Mount Unmount ISO](https://store.kde.org/p/1414733/): In desktop mode, add context menu (right-click) to mount ISO for the Dolphin File Manager in Desktop mode
  - Install from Discover store

---

## Softwares
Discover store is often the first go-to when searching or exploring softwares. Both Flatpak and KDE Applications are accessible via Discover store. More power users and software beyond Discover store, pacman in command-line might come in handy
- [Flathub](https://flathub.org/home): [Flatpak](https://flatpak.org/) is an apps store for SteamOS, integrated and directly searchable and installable from Discover store on Steam Deck
- [KDE Applications](https://apps.kde.org/): Apps store for [KDE](https://en.m.wikipedia.org/wiki/KDE_Plasma_5) which is what SteamOS uses, integrated and directly searchable and installable from Discover store on Steam Deck
- [pacman](https://archlinux.org/packages/): [pacman](https://archlinux.org/pacman/) is a utility which manages software packages in SteamOS (Arch Linux). Accessible via command-line.

---

## FAQ

### Q: Error "The following component(s) are required to run this program: Microsoft Visual C++ Runtime" upon custom installation
1. When you open the game, and it doesn't work and gives you the error - this will create a prefix in the system
2. Download one of the `x86` and `x64` from [Microsoft redistributables here](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)
3. Change the path from the game's properties to the `x86 Visual C++ installer .exe` and run the game, this will install Visual C++ to the game's prefix
4. Repeat the same step for `x64`
5. Change the path back to the game's `.exe` and the game should work accordingly

---

## Knowledge checks
- [ ] Install Steam game, uninstall Steam game
- [ ] Switch to Desktop mode, Switch to Gaming mode
- [ ] Install a game/app from Discover store, update and game/app from Discover store
- [ ] Install other version of Proton via ProtonUp-QT
- [ ] Configure Proton version for a game/app in Steam
- [ ] Add a non-Steam game to the Steam library
- [ ] Configure custom Artworks for non-steam game/app
- [ ] Install a game from third-party store, e.g. Epic game, GOG, etc
- [ ] Change controller settings for a game/app in Steam library
- [ ] Explore EmuDeck for retro-game preservation 
- [ ] Add and run an .exe game/app as non-Steam game
- [ ] Install a non-steam game/app via ISO
- [ ] Explore pacman + command-line and start the journey of a power-user
- [ ] Maybe, [buy me a coffee](https://github.com/MarcoLeongDev/awesome-steam-deck/blob/main/README.md#perhaps-) :)

---

## Lastly
If this guide is able to help consider [buying me a ☕️](https://www.buymeacoffee.com/marcoleong)
