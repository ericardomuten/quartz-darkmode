# @quartz-community/darkmode

Adds a dark mode toggle button that switches between light and dark themes.

## Installation

```bash
npx quartz plugin add github:quartz-community/darkmode
```

## Usage

```yaml title="quartz.config.yaml"
plugins:
  - source: github:quartz-community/darkmode
    enabled: true
    layout:
      position: left
      priority: 30
      group: toolbar
```

## Configuration

| Option           | Type      | Default | Description                                                                                                                                  |
| ---------------- | --------- | ------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| `fadeDuration`   | `number`  | `0`     | Fade the page in over this many milliseconds when the theme changes (click or operating-system change). `0` switches instantly. |
| `fillSunCenter`  | `boolean` | `false` | Fill the hollow center of the sun icon.                                                                                                      |
| `hoverHighlight` | `boolean` | `false` | Color the icon with `--tertiary` on hover (not on focus, so it does not stay colored after a click).                                         |

## Documentation

See the [Quartz documentation](https://quartz.jzhao.xyz/features/darkmode) for more information.

## License

MIT
