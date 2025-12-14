# Contributing to SEI Theme

First off, thank you for considering contributing to SEI Theme! 🎉

## 🎯 Guidelines

### Brand Compliance
All contributions must adhere to the **SEI Brand Guidelines Version 1.1**. This means:
- Colors must come from the approved palette (pages 44-45)
- Text/background combinations must follow accessibility guidelines (page 47)
- RED 1 (#F01840) should be used as the primary accent color

### Accessibility
- All text must meet **WCAG AA standards** for contrast
- Test changes in both light and dark themes
- Consider users with color blindness and other visual impairments

## 🐛 Reporting Bugs

Before creating bug reports, please check existing issues. When creating a bug report, include:

- **Description**: Clear description of the issue
- **Theme Variant**: SEI Dark or SEI Light
- **VS Code Version**: Your VS Code/Cursor version
- **Language**: What language/file type shows the issue
- **Screenshots**: If applicable
- **Expected Behavior**: What you expected to see
- **Actual Behavior**: What actually happened

## 💡 Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:

- **Clear title**: Descriptive title
- **Detailed description**: Step-by-step description of the enhancement
- **Rationale**: Why this enhancement would be useful
- **Brand compliance**: How it fits with SEI brand guidelines

## 🔨 Pull Requests

1. **Fork** the repository
2. **Create a branch** from `main`:
   ```bash
   git checkout -b feature/my-enhancement
   ```
3. **Make your changes**:
   - Edit `themes/sei-dark.json` or `themes/sei-light.json`
   - Update documentation if needed
4. **Test thoroughly**:
   - Symlink to your extensions folder
   - Test with multiple languages
   - Check both light and dark themes
5. **Commit** with clear messages:
   ```bash
   git commit -m "feat: improve Python syntax highlighting"
   ```
6. **Push** to your fork:
   ```bash
   git push origin feature/my-enhancement
   ```
7. **Open a Pull Request** with:
   - Clear description of changes
   - Screenshots showing before/after
   - Reference to any related issues

### Commit Message Format

Follow conventional commits:
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Color/styling changes
- `refactor:` Code restructuring
- `test:` Adding tests
- `chore:` Maintenance tasks

Examples:
```
feat: add support for Rust syntax highlighting
fix: improve markdown heading contrast in dark theme
docs: update installation instructions
style: soften comment colors in light theme
```

## 🎨 Theme Development

### File Structure
```
SEIThemeVSCode/
├── themes/
│   ├── sei-dark.json    # Dark theme colors
│   └── sei-light.json   # Light theme colors
├── package.json         # Extension metadata
├── README.md           # Main documentation
└── THEME_PREVIEW.md    # Syntax examples
```

### Color Guidelines

**Dark Theme:**
- Background: #141018 (BLACK)
- Foreground: #FFFFF8 (CREAM)
- Primary accent: #F01840 (RED 1)
- UI backgrounds: PURPLE 4-5
- Comments: PURPLE 3

**Light Theme:**
- Background: #FFFFF8 (CREAM)
- Foreground: #141018 (BLACK)
- Primary accent: #F01840 (RED 1)
- UI backgrounds: PURPLE 1-2
- Comments: PURPLE 2

### Testing Your Changes

1. **Symlink the extension**:
   ```bash
   ln -s "$(pwd)" "$HOME/.vscode/extensions/sei-theme"
   ```

2. **Reload VS Code/Cursor**:
   - Press `Cmd+Shift+P` → "Developer: Reload Window"

3. **Activate theme**:
   - Press `Cmd+K Cmd+T` → Select "SEI Dark" or "SEI Light"

4. **Test with multiple files**:
   - Open THEME_PREVIEW.md
   - Create test files in different languages
   - Check syntax highlighting accuracy

5. **Verify accessibility**:
   - Check contrast ratios
   - Test with color blindness simulators
   - Ensure readability in different lighting conditions

### Scope Reference

Common TextMate scopes for syntax highlighting:
- `keyword` - Language keywords
- `string` - String literals
- `comment` - Comments
- `entity.name.function` - Function definitions
- `entity.name.class` - Class definitions
- `variable` - Variables
- `constant` - Constants
- `support.type` - Built-in types
- `punctuation` - Punctuation marks

See [TextMate Language Grammars](https://macromates.com/manual/en/language_grammars) for more details.

## 📚 Resources

- [SEI Brand Guidelines](https://example.com/brand-guidelines) (Internal)
- [VS Code Theme Guide](https://code.visualstudio.com/api/extension-guides/color-theme)
- [WCAG Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [TextMate Scopes](https://www.sublimetext.com/docs/scope_naming.html)

## 🤔 Questions?

Feel free to open a [Discussion](https://github.com/rydercobean/SEIThemeVSCode/discussions) if you have questions about:
- Brand guidelines interpretation
- Color choices
- Theme design decisions
- Implementation details

## 📜 Code of Conduct

- Be respectful and professional
- Provide constructive feedback
- Focus on the theme and user experience
- Maintain brand integrity

---

Thank you for contributing to making SEI Theme better! 🎨✨


