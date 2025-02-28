# Visual-Studio-Like-Helix
Configuration file for the Helix text editor to be closer to Visual Studio with Visual Assist

## Why?
I just really liked Helix, but I don't want to learn all the motions, so...

## It's Visual Studio-like not VsCode-Like
If you're coming from VS Code, this might still feel familiar, however, do keep in mind that my objective is to mimic VS x VA functionality, not VS Code.

## About Visual Assist
I use VA as my main development plugin when working in C++ and C# projects, so I wanted to extend the ease of use that it provides me and combined with the lighting-fast performance of Helix, it feels just like the real thing

## Supported Bindings
### General
- Alt + Shift + O: Open the fuzzy search panel.
- Alt + Shift + Q:
  - A: Trigger code actions for quick fixes.
  - R: Rename a symbol to improve readability or refactor code.
  - E: Open the diagnostics picker for reviewing issues in the code.
- Alt + M: Open the symbol picker.
- F12: Go to the definition of a symbol.

### Navigation and Selection
- Ctrl + Left / Ctrl + Right: Move to the start/end of words.
- Shift + Arrow Keys: Extend selections by characters or lines.
- Ctrl + Shift + Left / Ctrl + Shift + Right: Extend selections by words.
- Ctrl + A: Select the entire file.

### Editing
- Ctrl + S: Save the current buffer.
- Ctrl + Z / Ctrl + Y: Undo and redo changes.
- Ctrl + Backspace / Ctrl + Del: Delete words backward or forward.
- Alt + Shift + Up / Alt + Shift + Down: Duplicate the current selection to adjacent lines.
- Alt + Down / Alt + Up: Delete and reinsert the current line above/below.

## Maintenance
This repo is truly for personal purposes (AKA, I do not want to lose my config if my PC dies), but I thought it might be useful for someone else like me that likes a lighting fast editor, but doesn't have the time to learn all the complicated motions.

That being said, I don't know how much I'll be able to keep this config up to date, but as Helix becomes one of my main editing tools I might continue adding on features to mimic Visual Studio x VA.

## Additional languages
- GDScript (you must first download the [NCat / NMap](https://nmap.org/download#windows) command line utility if not on Linux)
- GLSL (requires [GLSL Analyzer](https://github.com/nolanderc/glsl_analyzer) to be installed)
