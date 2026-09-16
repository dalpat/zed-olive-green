# Forest for Zed

Two nature-inspired themes for [Zed](https://zed.dev):

- **Forest Dark** — deep green backgrounds, soft ivory text, lime keywords, warm gold strings, and pale teal variables.
- **Forest Light** — warm ivory backgrounds, forest-green text, olive keywords, ochre strings, and deep teal variables.

## Install now

Copy `themes/forest.json` into `~/.config/zed/themes/`, then restart Zed and select **Forest Dark** or **Forest Light** using `theme selector: toggle`.

Alternatively, clone this repository and run `zed: install dev extension`, selecting the repository directory.

Registry publication is pending. Once accepted, search for **Forest** in Zed Extensions.

## Follow system appearance

Merge this into your Zed settings:

```json
{
  "theme": {
    "mode": "system",
    "light": "Forest Light",
    "dark": "Forest Dark"
  }
}
```

## Optional coding font

The extension changes colors only. Install Fira Code separately if needed and merge these settings to use programming ligatures:

```json
{
  "buffer_font_family": "Fira Code",
  "buffer_font_size": 18,
  "buffer_font_weight": 400,
  "buffer_line_height": { "custom": 1.5 },
  "buffer_font_features": { "calt": true }
}
```

These settings affect the coding font, not the IDE interface font. Font size is a personal preference and depends on display scaling.

## License

[MIT](LICENSE)
