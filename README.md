# SEI Theme for VS Code

<div align="center">

![SEI Theme](https://img.shields.io/badge/SEI-Theme-F01840?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-C01830?style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS%20Code-Compatible-402848?style=for-the-badge)

**A professional VS Code theme crafted from the official SEI Brand Guidelines**

[Installation](#installation) • [Features](#features) • [Screenshots](#screenshots) • [Color Palette](#color-palette) • [Contributing](#contributing)

</div>

---

## 🎨 Overview

SEI Theme brings the official SEI brand identity to your development environment with two carefully designed variants:

- **SEI Dark** - Rich black background with warm cream text and vibrant red accents
- **SEI Light** - Soft cream background with deep black text and consistent branding

Both themes follow **WCAG AA accessibility standards** and are built directly from the SEI Brand Guidelines Version 1.1 (pages 43-47).

## ✨ Features

- 🎯 **100% Brand Accurate** - All colors sourced directly from official SEI Brand Guidelines
- ♿️ **Accessible** - Meets WCAG AA standards for text contrast
- 👁️ **Comfortable** - Carefully balanced colors reduce eye strain during long coding sessions
- 🎨 **Semantic Highlighting** - Intelligent syntax coloring for better code comprehension
- 📝 **Markdown Optimized** - Beautiful, readable markdown with toned-down colors
- 🔧 **Comprehensive** - Covers all UI elements, from editor to status bar

## 📦 Installation

### From VS Code Marketplace (Coming Soon)

1. Open VS Code
2. Press `Cmd+Shift+X` (Mac) or `Ctrl+Shift+X` (Windows/Linux)
3. Search for "SEI Theme"
4. Click Install

### Manual Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/rydercobean/SEIThemeVSCode.git
   ```

2. Create a symlink to your VS Code extensions folder:
   ```bash
   ln -s "$(pwd)/SEIThemeVSCode" "$HOME/.vscode/extensions/sei-theme"
   # For Cursor IDE:
   ln -s "$(pwd)/SEIThemeVSCode" "$HOME/.cursor/extensions/sei-theme"
   ```

3. Reload VS Code/Cursor

4. Activate the theme:
   - Press `Cmd+K Cmd+T` (Mac) or `Ctrl+K Ctrl+T` (Windows/Linux)
   - Select "SEI Dark" or "SEI Light"

## 🖼️ Screenshots

### SEI Dark Theme

The dark variant features:
- Rich black background (#141018) with subtle purple undertones
- Warm cream text (#FFFFF8) for excellent readability
- Vibrant RED 1 (#F01840) accents for brand presence
- Layered purple tones creating depth without distraction

### SEI Light Theme

The light variant features:
- Soft cream background (#FFFFF8) for comfortable all-day viewing
- Deep black text (#141018) with high contrast
- Consistent RED 1 (#F01840) branding across UI
- Elegant gray-purple tones for sophistication

### Syntax Highlighting Examples

Open [THEME_PREVIEW.md](THEME_PREVIEW.md) in this repository to see comprehensive syntax highlighting examples for:
- JavaScript/TypeScript
- Python
- JSON
- CSS
- Markdown

## 🎨 Color Palette

### Primary Colors (Reds)

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **RED 1** | `#F01840` | 240, 24, 64 | Primary accents, keywords, status bar, links |
| **RED 2** | `#C01830` | 192, 24, 48 | Types, numbers, headings, secondary accents |
| **RED 3** | `#901226` | 144, 18, 38 | Deep red for types and emphasis |
| **RED 4** | `#600C1C` | 96, 12, 28 | Dark red for strings (light theme) |
| **RED 5** | `#300810` | 48, 8, 16 | Deepest red |

### Secondary Colors (Purples)

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **PURPLE 1** | `#D0C8C8` | 208, 200, 200 | Light gray-purple for UI elements, strings |
| **PURPLE 2** | `#A0949E` | 160, 148, 158 | Medium purple for comments, operators, lists |
| **PURPLE 3** | `#705E74` | 112, 94, 116 | Dark purple for comments, constants |
| **PURPLE 4** | `#402848` | 64, 40, 72 | Deep purple for classes, UI backgrounds |
| **PURPLE 5** | `#2A1C30` | 42, 28, 48 | Deepest purple for dark theme UI |

### Neutrals

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **CREAM** | `#FFFFF8` | 255, 255, 248 | Light theme background, dark theme text |
| **BLACK** | `#141018` | 20, 16, 24 | Dark theme background, light theme text |

## 🎯 Design Principles

1. **Brand Adherence** - Every color is pulled directly from SEI Brand Guidelines pages 43-47
2. **Accessibility First** - All text combinations meet or exceed WCAG AA standards
3. **Visual Hierarchy** - RED 1 (#F01840) used strategically for important elements
4. **Comfortable Reading** - Purple tones provide depth without causing eye strain
5. **Consistent Identity** - Both themes maintain strong SEI brand presence

## 📋 Syntax Highlighting Guide

### Dark Theme

- **Keywords** (`if`, `const`, `class`) - RED 1 (#F01840)
- **Strings** - PURPLE 1 (#D0C8C8)
- **Functions** - PURPLE 1 (#D0C8C8) for definitions, PURPLE 2 (#A0949E) for calls
- **Classes** - CREAM (#FFFFF8)
- **Comments** - Italic PURPLE 3 (#705E74)
- **Numbers & Booleans** - RED 2 (#C01830)
- **Types** - RED 2 (#C01830)

### Light Theme

- **Keywords** (`if`, `const`, `class`) - RED 1 (#F01840)
- **Strings** - RED 4 (#600C1C)
- **Functions** - RED 4 (#600C1C) for definitions, PURPLE 3 (#705E74) for calls
- **Classes** - PURPLE 4 (#402848)
- **Comments** - Italic PURPLE 2 (#A0949E)
- **Numbers & Booleans** - RED 2 (#C01830)
- **Types** - RED 3 (#901226)

## 🔧 Customization

Want to tweak the theme? You can customize it via VS Code settings:

```json
{
  "workbench.colorCustomizations": {
    "[SEI Dark]": {
      "editor.background": "#141018"
    },
    "[SEI Light]": {
      "editor.background": "#FFFFF8"
    }
  },
  "editor.tokenColorCustomizations": {
    "[SEI Dark]": {
      "keywords": "#F01840"
    }
  }
}
```

## 🤝 Contributing

Contributions are welcome! Please ensure any changes:

1. Maintain compliance with SEI Brand Guidelines
2. Meet WCAG AA accessibility standards
3. Are tested in both light and dark themes
4. Include updated documentation

### Development Setup

```bash
# Clone the repository
git clone https://github.com/rydercobean/SEIThemeVSCode.git
cd SEIThemeVSCode

# Make your changes to themes/sei-dark.json or themes/sei-light.json

# Test by symlinking to your extensions folder
ln -s "$(pwd)" "$HOME/.vscode/extensions/sei-theme"

# Reload VS Code to see changes
```

## 📝 Changelog

See [CHANGELOG.md](CHANGELOG.md) for a list of changes in each version.

## 🙏 Acknowledgments

- Colors and design principles from **SEI Brand Guidelines Version 1.1** (Pages 43-47)
- Built with attention to accessibility and developer experience
- Tested extensively with JavaScript, TypeScript, Python, JSON, CSS, Markdown, and more

## 📬 Support

Found a bug or have a suggestion?

- 🐛 [Open an issue](https://github.com/rydercobean/SEIThemeVSCode/issues)
- 💬 [Start a discussion](https://github.com/rydercobean/SEIThemeVSCode/discussions)

---

<div align="center">

**Made with ❤️ for the SEI development team**

[![GitHub](https://img.shields.io/badge/GitHub-SEIThemeVSCode-F01840?style=flat-square&logo=github)](https://github.com/rydercobean/SEIThemeVSCode)

</div>
