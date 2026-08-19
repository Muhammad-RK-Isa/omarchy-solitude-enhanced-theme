# Solitude Enhanced

Solitude Enhanced keeps the charcoal surfaces, steel accents, restrained
geometry, and monochrome artwork of the original Solitude theme while adding a
muted full-color palette for meaningful states, terminal tools, and code.

The palette is deliberately subdued rather than neon or pastel. Dusty coral is
used for errors and destructive actions, sage for success, aged ochre for
warnings, and slate blue for information. Teal, smoke mauve, and warm orange
complete the ANSI and syntax palette without overpowering the desktop.

![Solitude Enhanced preview](preview.png)

## Installation

Install directly with Omarchy:

```bash
omarchy theme install https://github.com/Muhammad-RK-Isa/omarchy-solitude-enhanced-theme.git
```

Select it again later with:

```bash
omarchy theme set solitude-enhanced
```

Current Omarchy releases are the supported baseline. Omarchy generates the
terminal, btop, Neovim, Helix, VS Code, Obsidian, Claude, Pi, and Chromium
integrations from this theme's `colors.toml`; `shell.toml` provides the matching
Omarchy shell surfaces and interaction states.

## Palette

| Role | Normal | Bright |
| --- | --- | --- |
| Error / destructive | `#C76C5B` | `#DE7C68` |
| Success | `#8FAF87` | `#A2C099` |
| Warning | `#C2A96D` | `#D1B97C` |
| Info / blue | `#7897AB` | `#8AA9BC` |
| Cyan | `#7FA9A4` | `#91BAB4` |
| Magenta | `#A78AA3` | `#B99AB4` |
| Orange | `#B9825F` | - |

The original Solitude neutrals remain the visual foundation:

| Role | Color |
| --- | --- |
| Background | `#101315` |
| Foreground | `#CACCCC` |
| Accent | `#798186` |
| Selection | `#343D41` |
| Muted | `#4B4E55` |

## Optional Integrations

This repository also includes GTK, Steam, Vesktop/Vencord, Cava, Walker,
SwayOSD, Waybar, and Mako files for setups using the
[Bypass theme hook](https://github.com/imbypass/omarchy-theme-hook). Their
semantic colors match the canonical Omarchy palette.

## Design Rules

- Neutral surfaces remain dominant; color is concentrated in diagnostics,
  diffs, syntax, graphs, and status feedback.
- Coral is reserved for actual errors, destructive actions, and critical
  notifications rather than ordinary pressed or active controls.
- Focus, selection, progress, window borders, and general activity retain the
  original steel accent.
- Semantic colors are designed for readable text on the primary dark surface.

## Credits

Solitude Enhanced is based on the original
[Solitude](https://github.com/HANCORE-linux/omarchy-solitude-theme) theme by
HANCORE. The original copyright and MIT license are preserved in `LICENSE`.

The original Waybar layout is available from
[HANCORE's Waybar themes](https://github.com/HANCORE-linux/waybar-themes).
