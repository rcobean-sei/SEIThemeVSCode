# SEI Theme Preview

This file demonstrates the SEI theme colors and syntax highlighting.

## Features

- **Bold text** looks great
- *Italic text* is easy to read
- [Links are highlighted](https://example.com) 
- `Inline code` stands out

## Code Examples

### JavaScript/TypeScript

```javascript
// This is a comment
import { Component } from 'react';

class ThemePreview extends Component {
  constructor(props) {
    super(props);
    this.state = {
      count: 0,
      message: "SEI Theme looks amazing!",
      isActive: true
    };
  }

  incrementCount() {
    this.setState({ count: this.state.count + 1 });
  }

  render() {
    const { count, message } = this.state;
    return (
      <div className="preview">
        <h1>{message}</h1>
        <p>Count: {count}</p>
        <button onClick={() => this.incrementCount()}>
          Increment
        </button>
      </div>
    );
  }
}

export default ThemePreview;
```

### Python

```python
# Python example
class SEITheme:
    """A beautiful theme for VS Code"""
    
    def __init__(self, name: str, colors: dict):
        self.name = name
        self.colors = colors
        self.is_active = False
    
    def activate(self) -> bool:
        """Activate the theme"""
        if not self.is_active:
            self.is_active = True
            print(f"Activated {self.name} theme!")
            return True
        return False
    
    @property
    def primary_color(self) -> str:
        return self.colors.get('primary', '#F01840')

# Create and activate theme
theme = SEITheme('SEI Dark', {
    'primary': '#F01840',
    'cream': '#FFFFF8',
    'black': '#141018'
})
theme.activate()
```

### JSON

```json
{
  "name": "sei-theme",
  "displayName": "SEI Theme",
  "version": "1.0.0",
  "colors": {
    "primary": "#F01840",
    "secondary": ["#C01830", "#901226"],
    "purple": {
      "light": "#D0C8C8",
      "dark": "#2A1C30"
    },
    "count": 123,
    "enabled": true
  }
}
```

### CSS

```css
/* CSS Example */
.sei-theme {
  background-color: #141018;
  color: #FFFFF8;
  font-family: 'Arial', sans-serif;
  padding: 20px;
  border: 2px solid #F01840;
}

.sei-theme .highlight {
  background: rgba(240, 24, 64, 0.3);
  border-radius: 4px;
}

#primary-button:hover {
  background-color: #C01830;
  transform: scale(1.05);
}
```

## Brand Colors Reference

| Color Name | Hex Code | Usage |
|------------|----------|-------|
| RED 1 | `#F01840` | Primary accent, keywords |
| RED 2 | `#C01830` | Functions, secondary |
| RED 3 | `#901226` | Types, deeper accents |
| PURPLE 1 | `#D0C8C8` | Strings (dark), UI elements |
| PURPLE 2 | `#A0949E` | Comments, subtle text |
| PURPLE 3 | `#705E74` | Comments, properties |
| PURPLE 4 | `#402848` | Classes, deep purple |
| PURPLE 5 | `#2A1C30` | Backgrounds (dark) |
| CREAM | `#FFFFF8` | Light background / dark text |
| BLACK | `#141018` | Dark background / light text |

---

**Reload your editor** to see the themes take effect!
Use `Cmd+K Cmd+T` to quickly switch between themes.





