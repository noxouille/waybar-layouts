# Waybar Layouts

A collection of custom Waybar themes inspired by the Trails (Kiseki) JRPG series.

## Themes

### Kiseki

Workspaces display kanji representing each Trails series entry. The media player module appears only when media is playing.

![Kiseki](kiseki/preview.png)

### Quartz

A refined version of the Sepith layout with all core modules centered. Minimal floating island design with a single center island. Workspaces use the seven Sepith element colors (Earth, Water, Fire, Wind, Time, Space, Mirage) with glowing text shadows on the active workspace.

![Quartz](quartz/preview.png)

### Sepith

Three floating islands (left, center, right) with semi-transparent backgrounds. Workspaces are colored by the seven Sepith elements, each glowing when active.

![Sepith](sepith/preview.png)

### Xipha

Unified continuous bar inspired by the Xipha tactical orbment device. Features a subtle circuit-line gradient behind workspaces connecting the Quartz element dots. Active workspaces have a pronounced glow effect.

![Xipha](xipha/preview.png)

## Usage

Each theme folder contains:

- `config.jsonc` - Waybar configuration
- `style.css` - Theme styling
- `preview.png` - Theme preview

To use a theme, symlink or copy the config and style files to your waybar config directory:

```bash
ln -sf ~/.config/waybar/layouts/<theme>/config.jsonc ~/.config/waybar/config.jsonc
ln -sf ~/.config/waybar/layouts/<theme>/style.css ~/.config/waybar/style.css
```

## Sepith Elements

| Element | Color | Hex |
|---------|-------|-----|
| Earth | Ochre | `#c9a063` |
| Water | Blue | `#4a9eff` |
| Fire | Red | `#e85d4c` |
| Wind | Teal | `#2dd4bf` |
| Time | Gray | `#7a7a8e` |
| Space | Gold | `#f0c040` |
| Mirage | Silver | `#a0a0b8` |