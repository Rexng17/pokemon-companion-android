# TypeDex · 弱点图鉴

**Keep your opponent’s type weaknesses beside the game.**

TypeDex is an unofficial Android companion for Pokémon Champions, now available for early testing. Wait for the game screen to settle, tap **Scan** in the overlay, and check the opponent’s base type weaknesses. In a doubles battle, you can also see the four most popular moves for each active opponent.

[Download the 0.7.1 trial APK](https://github.com/Rexng17/pokemon-companion-android/releases/download/v0.7.1/pokemon-companion-0.7.1.apk) · [Release notes](https://github.com/Rexng17/pokemon-companion-android/releases/tag/v0.7.1) · [Send feedback](https://github.com/Rexng17/pokemon-companion-android/issues/new/choose) · [简体中文](README.md)

**Android 8.0+ · About 3.7 MB · Free to try · No account or API key required**

## What it does

| When you use it | What you see |
| --- | --- |
| Team selection or the status/ability screen | Six opponents in two columns, with 4× weaknesses first |
| A doubles battle | Two active opponents, their weaknesses, and popular moves with usage percentages |
| Looking up a Pokémon | Offline search by name, number or type; forms, resistances, immunities and favorites |
| A scan needs correcting | Tap a card to choose the correct Pokémon, or select one or two types manually |

Recognition and type lookups run on your phone. Captured frames are processed in memory without being saved or uploaded. Drag the title to move the overlay and pinch with two fingers to resize it. The interface supports English and Simplified Chinese.

**Current scan calibration is for three Chinese landscape game layouts. English UI support does not mean English game screenshots have been validated.** Manual lookups work in either UI language.

## Install

1. Open the APK download link on your Android phone, or choose `pokemon-companion-0.7.1.apk` under **Assets** on the release page.
2. Open the file. If Android asks, allow installation from the browser or file manager you are using, then follow the system prompts.
3. Open TypeDex and complete the welcome screen. Offline lookups are available immediately. Enable the overlay separately when you want to scan a game screen.

GitHub’s automatic `Source code (zip)` and `Source code (tar.gz)` downloads contain this distribution repository’s documents. They are **not Android installers**. Choose the `.apk` file. If installation fails, keep the exact system message for your report.

## Try it in a battle

1. Open the overlay assistant in TypeDex and grant **Display over other apps** when prompted.
2. Return to the landscape game and open team selection, status/abilities, or a doubles battle.
3. **Wait until the screen is still, then tap Scan.** Follow Android’s screen-capture prompt. Each scan captures one frame and ends the capture session.
4. Review the cards: the six opponents on the right in team/status screens, or the two opponents at the top right during battle. Tap a card for details or corrections.
5. **Scan again after the battle begins, a switch, or a form change.** Results describe the last frame you scanned.

Drag the title to move the window. Pinch inside it to resize. Use **−** to collapse it and **⋯** for manual lookup, image import or closing. Landscape and portrait layouts remember their size and position separately. Change language from the main screen’s **☰ → 语言 / Language** menu.

## Before you try it

- Weaknesses use base types. Abilities, held items, weather, terrain and temporary type changes are not included; this is not a full damage calculator.
- Popular moves come from [Pokémon Champions Battle Data](https://championsbattledata.com/) doubles statistics. They are not a confirmed opponent moveset. A first lookup needs internet access; valid cached results remain available offline. Expand the data details to see the actual date and aggregation scope.
- Recognition may fail on unfamiliar layouts, obscured portraits or similar forms. Correct results manually when needed.
- Version 0.7.1 has no ads and includes no advertising SDK. It keeps the first-use guide and opens the main screen directly on later launches.
- Version 0.7.1 is an early trial. Overlay permissions, gestures and capture prompts still need testing on more phones. See the [privacy notice](PRIVACY.md#english).

## Feedback

We especially want to know: **Could you install it? Did it recognize your usual opponents? Did the overlay get in the way?**

Use [Issues](https://github.com/Rexng17/pokemon-companion-android/issues/new/choose) and include your phone model, Android version, app version, screen type and steps. Screenshots are optional; remove trainer names, notifications and personal information first. Without a GitHub account, send feedback to the person who shared the app with you.

Updates will appear in [Releases](https://github.com/Rexng17/pokemon-companion-android/releases). Downloads and installation are manual. Compatible updates with the same package ID and signing certificate can install over the previous version. Report signature conflicts before uninstalling: uninstalling clears local favorites and settings.

## Credits

This independent fan tool is not affiliated with or endorsed by Pokémon, Nintendo, Creatures, GAME FREAK or The Pokémon Company. Related characters, artwork and trademarks belong to their respective rights holders.

Reference data comes from 52Poké Wiki and PokéAPI; move statistics come from Pokémon Champions Battle Data. See [CREDITS.md](CREDITS.md) for sources, licenses and adaptations. This repository distributes trial builds and documentation and collects feedback; it grants no additional rights to third-party content.
