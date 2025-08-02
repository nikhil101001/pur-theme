# 🐾 Pur Theme - VS Code Extension

## What's in the folder

- This folder contains all files for the Pur Theme collection.
- `package.json` - manifest file defining all theme variants and metadata.
- `themes/` - folder containing all theme files:
  - `pur-black.json` - Clean minimal dark theme
  - `pur-cyberpunk.json` - Neon matrix vibes theme
  - `pur-walnut.json` - Warm earthy tones theme
  - `pur-neon.json` - Electric highlights theme

## Get up and running

- Press `F5` to open a new window with your extension loaded.
- Open `File > Preferences > Theme > Color Theme` (or `Ctrl+K Ctrl+T`)
- Pick any Pur Theme variant to test
- Open code files to see syntax highlighting in action
- Use `Developer: Inspect Editor Tokens and Scopes` to examine token scopes

## Make changes

- Edit any theme file in `themes/` folder
- Changes automatically apply to the Extension Development Host window
- Test all theme variants to ensure consistency

## Development tips

- Each theme follows the same structure but with different color palettes
- All themes are based on TextMate token scopes
- Maintain consistent contrast ratios across variants
- Test with multiple programming languages

## Publishing

- Install locally: Copy to `~/.vscode/extensions` and restart VS Code
- Publish to marketplace: Use `vsce publish` after setup
- See [VS Code publishing guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) for details

---

_Made with 🐾 for developers who love beautiful code_
