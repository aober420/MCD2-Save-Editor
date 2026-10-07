# MCD 2 Save Editor

Standalone, unofficial save editor for Minecraft Dungeons II.

**Windows: 1.0.2 · Linux: 1.0.1 · Target game version: v1.1.1.0**

## Downloads

- [Windows 1.0.2](https://github.com/aober420/MCD2-Save-Editor/releases/tag/v1.0.2)
- [Linux 1.0.1](https://github.com/aober420/MCD2-Save-Editor/releases/tag/v1.0.1) — native Linux x64 preview for Bazzite and SteamOS Desktop Mode; testing on a Linux device is still needed.

Extract the ZIP before running the editor.

## Windows 1.0.2

Adds support for offline saves from the Minecraft Launcher / Xbox app, alongside Steam saves. Click **Open save**, then choose **Steam** or **Minecraft Launcher**.

- **Steam:** opens `%LOCALAPPDATA%\Dungeons2\Saved\SaveGames` so you can select a character `.sav` file.
- **Minecraft Launcher:** finds the game's WGS account folder using the game identifier after the underscore, independent of your account identifier. If multiple account folders match, choose one. Select `containers.index`, then select your character. If no matching folder is found, browse to your WGS save folder manually.
- **Save:** updates the opened Steam file or Launcher WGS container. It does not create automatic `.bak` files.
- **Save as:** exports a separate `.sav` file. For Launcher characters, this is a standalone JSON export; it does not create another Launcher character container.

Edit gear, rarity, power, enchantments, effects, bonuses, currencies, level, talismans and cosmetics. Cosmetic availability in-game can still depend on unlocks or ownership.

Close the game before saving and keep a manual backup of your save folder. Launcher support passed read/write and integrity checks on a copied save; loading edited Launcher saves in-game still needs testing. Online heroes stored on the game's servers are not supported.

This release uses the existing editor UI. The redesigned UI remains under development and is not included.

Unofficial fan project; not affiliated with Mojang or Microsoft.
