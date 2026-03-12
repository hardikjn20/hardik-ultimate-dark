# Hardik Ultimate Dark

> A bold, vibrant VS Code theme — **pure black background**, 45+ carefully chosen colors, zero clashing combos. Built from scratch, not based on any existing theme.

---

## 🎨 Color Design Philosophy

Every color was hand-picked and mathematically verified. Any two colors that appear together in code are **at least 15° hue apart OR 18% lightness apart** — meaning your eye never confuses them.

### The Color Language

| Token | Color | Hex | Why |
|---|---|---|---|
| Keywords `if for while` | 🔴 Crimson-Pink | `#FF2D6B` | Most important — pops out |
| `import export from` | 🔴 Deep Crimson | `#D91A55` | Same family, distinct shade |
| `let const var function` | 🩷 Soft Pink | `#FF80AA` | Storage — lighter than keywords |
| Operators `= + - && ===` | 🟡 Gold | `#FFD700` | Clean gold, never confused |
| Function names | 🔵 Electric Blue | `#3399FF` | Key semantic meaning |
| Variables | ⚪ Near White | `#E8DFF5` | Most common — neutral |
| Parameters | 🟢 Electric Lime | `#C8FF00` | Pops out from gold operators |
| `this self super` | 🟣 Indigo | `#7777FF` | Language-level vars — special |
| Strings | 🟠 Orange | `#FF8C00` | Warm, readable |
| Template literals | 🟠 Deep Orange | `#FF6600` | Same family, deeper |
| Numbers `42 3.14` | 🩵 Sky Blue | `#66DDFF` | Distinct from string orange |
| `true false null` | 🩵 Teal | `#00AABB` | Language constants |
| Class names | 🟣 Lavender | `#CC77FF` | Types feel "structural" |
| Type/Interface | 🟣 Medium Purple | `#AA44EE` | Same family as classes |
| Decorators `@decorator` | 🌿 Mint | `#00FFAA` | Special meta — stands out |
| HTML tags | 🟣 Hot Magenta | `#FF00CC` | Markup — distinct from code |
| HTML attributes | 🟢 Seafoam | `#00EEA0` | Complement to magenta tags |
| CSS properties | 🟢 Medium Green | `#66BB6A` | Structural CSS |
| Comments | 🔵 Muted Blue-Gray | `#5C6A7A` italic | Recedes, never distracts |
| Errors | 🔴 Pure Red | `#FF3B3B` | Immediate alert |

---

## ✅ Full Language Coverage

**Web:** JavaScript · TypeScript · React/JSX · Angular · Node.js · HTML · CSS · SCSS · LESS · Tailwind CSS

**Data/ML:** Python · NumPy · Pandas · TensorFlow · PyTorch · Scikit-learn

**Backend/Systems:** Java · C++ · SQL

**Config/Docs:** JSON · YAML · Markdown

---

## ✨ Features

- **Pure black** `#0A0A0A` background — true dark, not dark gray
- **45+ token colors** — all distinct, all verified clash-free
- **194 UI color keys** — editor, sidebar, tabs, terminal, git, panels, all styled
- **Rainbow bracket highlighting** — 6 distinct colors  
- **Full 16-color ANSI terminal palette**
- **Git decorations** — add/modify/delete/untracked/conflict all distinct
- **IntelliSense widget theming** — suggest, hover, errors all styled

---

## 📦 Installation

**From Marketplace:**
1. Open Extensions `Ctrl+Shift+X`
2. Search **Hardik Ultimate Dark**
3. Install → `Ctrl+K Ctrl+T` → select theme

**From VSIX:**
```
vsce package
code --install-extension hardik-ultimate-dark-2.0.0.vsix
```

---

## 🔤 Recommended Settings

```json
{
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.fontLigatures": true,
  "editor.lineHeight": 1.6,
  "editor.letterSpacing": 0.3
}
```

**Font:** [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — free, ligatures, designed for code

---

## 📄 License

MIT — use freely, modify, distribute.
