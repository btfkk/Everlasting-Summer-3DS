# Everlasting Summer — Nintendo 3DS port

Unofficial fan port of the visual novel **Everlasting Summer** (Soviet Games) for **Nintendo 3DS**.

**Version:** beta 0.01 · **Port by:** btfkk

## Features

- The full story: prologue, 7 days, all endings, epilogue and Zhenya's route.
- Backgrounds, sprites, CGs, transitions, music and sound effects.
- Camp map, mine and card game, just like the original.
- 3 pages of save slots, quick save, autosave and "Continue".
- Text log, auto mode, skip, light and dark themes.
- Button and touch screen controls.

## Not yet

- Intro video.
- Rollback (use saves instead).

## Tested on

- **PC:** Azahar emulator.
- **Anbernic RG DS:** ROCKNIX firmware, Azahar emulator.

## Requirements

- **3DS / 2DS / New 3DS / New 2DS** with **Luma3DS** custom firmware. Don't have it yet? See [3ds.hacks.guide](https://3ds.hacks.guide/).
- **FBI** (usually installed by the guide).
- An SD card with about 1 GB free.
- **`es3ds.cia`** from the release.

Sound works out of the box, nothing else to install.

## Installation

1. Turn off the console and put the SD card into your computer.
2. Create a `cia` folder on the card if it doesn't exist and copy `es3ds.cia` into it.
3. Put the card back into the console and turn it on.
4. Open **FBI** → **SD** → **cia** → **es3ds.cia**.
5. Choose **Install and delete CIA** and press **A**. The file is big, so it takes a few minutes.
6. Press **HOME**. **Everlasting Summer** will appear on the HOME menu.

Don't want to remove the card? Send the file over Wi-Fi with **ftpd** or **FBI → Remote Install**.

## Controls

| Button | Action |
|---|---|
| A / tap | next |
| B / ↑ | text log |
| X / START | menu |
| Y | quick save |
| L / hold R | auto / skip |
| Card game: ←→ / A / X / B | select / take or swap / "Enough" / cancel |

## Update and removal

- **Update:** install the new `es3ds.cia` over the old one with FBI. Your saves are kept.
- **Remove:** FBI → **Titles** → **Everlasting Summer** → **Delete Title**.

Saves: `sdmc:/3ds/es3ds/save/es3ds/` · Log: `sdmc:/es3ds_log.txt`

## Troubleshooting

| Problem | Fix |
|---|---|
| FBI doesn't see the file | Make sure it's in the `cia` folder on the SD card and ends with `.cia`. |
| Install error | Free up space on the card and copy the file again, it may have been corrupted. |
| Game crashes | Open an [Issue](../../issues) and attach `sdmc:/es3ds_log.txt`. |

## Credits

Everlasting Summer © Soviet Games. All game assets belong to their owners.
This is a non-commercial fan project, not affiliated with Soviet Games.
Port code: btfkk. LÖVE Potion engine — MIT license, fonts — SIL OFL 1.1.
