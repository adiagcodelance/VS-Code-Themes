# Custom VS Code Themes

Two custom dark color themes for Visual Studio Code.

## Themes

### Purple Surface Dark
- Based on your custom color palette (#5f34c8 primary, #121212 surface)
- Deep black backgrounds with purple accents
- Modern, sleek design perfect for night coding

### Ubuntu Dark
- Inspired by Ubuntu's iconic orange and dark gray palette
- Uses Ubuntu's signature orange (#e95420) as accent color
- Warm, familiar colors based on Ubuntu terminal

## Installation

### Local Development

1. Copy this folder to your VS Code extensions directory:
   - Windows: `%USERPROFILE%\.vscode\extensions`
   - macOS/Linux: `~/.vscode/extensions`

2. Reload VS Code
3. Go to File > Preferences > Color Theme (or press `Ctrl+K Ctrl+T`)
4. Select either:
   - **Purple Surface Dark**
   - **Ubuntu Dark**

### Publishing to Marketplace

To publish this theme to the VS Code marketplace:

```bash
npm install -g @vscode/vsce
vsce package
vsce publish
```

## Customization

Edit theme files to customize colors:
- `themes/purple-surface-dark.json` - Purple theme
- `themes/ubuntu-dark.json` - Ubuntu theme

Each theme has two main sections:
- `colors`: UI elements (sidebar, editor background, status bar, etc.)
- `tokenColors`: Syntax highlighting for code elements

### Color Reference

**Purple Surface Dark:**
- Primary: `#5f34c8`
- Surface: `#121212`
- Alpha variants available (33, 1a, 66, 4d for transparency)

**Ubuntu Dark:**
- Orange accent: `#e95420`
- Background: `#2c2c2c`
- Based on Ubuntu terminal colors

Refer to the [VS Code Theme Color Reference](https://code.visualstudio.com/api/references/theme-color) for available color keys.

## License

MIT
