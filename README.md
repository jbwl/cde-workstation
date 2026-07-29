# CDE Workstation

A color theme collection inspired by the Common Desktop Environment, Motif, Solaris workstations, early KDE, and the wonderfully square era of Unix computing.

Included themes:

- **CDE Workstation Light**: Solaris 8-inspired blue title bars, Motif silver-gray chrome, and a muted parchment terminal.
- **CDE Workstation Dark**: a modern dark concession that preserves the same restrained palette.
- **CDE Solaris Teal**: a brighter workstation-style variant with the classic teal desktop character.

## Install

In Kiro or VS Code, open the Command Palette and choose **Extensions: Install from VSIX...**, then select the packaged `.vsix` file.

Choose a theme with **Preferences: Color Theme**.

## Suggested editor settings

```json
{
  "editor.fontFamily": "'DejaVu Sans Mono', 'Liberation Mono', monospace",
  "editor.fontLigatures": false,
  "editor.fontSize": 14,
  "editor.lineHeight": 21,
  "window.commandCenter": false,
  "workbench.editor.showTabs": "multiple"
}
```

VS Code-family applications do not expose full control over widget geometry, so this theme recreates the CDE palette and visual hierarchy rather than literal Motif bevels.
