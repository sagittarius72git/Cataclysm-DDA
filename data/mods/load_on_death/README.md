# Load on Death (CDDA 0.I)

A mod for Cataclysm: DDA stable 0.I-1 (Ito-1). When you die, you can go back to your last save instead. It runs on JSON (EOCs) only.

## How it works

- After the death screen, you are asked "Undo this death and return to your last save?"
- Yes: your death is put on hold. Open the debug menu and choose Game… → Quickload to load your last save.
- No: you die as usual.

## Setup

The debug menu has no default key. Set one once: Esc menu → Keybindings → "Debug menu".
Release builds of CDDA have no Quickload key, and a JSON mod can't start a load, so loading goes through the debug menu. Quickload in the debug menu does not turn off achievements.

## Notes

- You can only go back to a save that exists. A character that has never been saved can't load.
- If 5 seconds pass while your death is on hold, you die again and get the same question.
- A save made while your death is on hold (save and quit, or an autosave that happens right then) ends in death when loaded.
- Revivals from other mods (PREVENT_DEATH) are tried first. If you have followers, the game's "Continue as one of your followers?" comes first.
- You can add it to an existing world.

## Credits

- Author: sagittarius72
- This mod (including its documentation) was made largely with the help of Claude Opus.

Assisted-by: Claude:claude-opus-5-5
