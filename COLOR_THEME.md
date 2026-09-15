# FinoraAI - Design System & Color Theme

FinoraAI uses a bespoke **Warm Ledger Design System**, crafted to feel like a modern, inviting financial notebook rather than a cold corporate bank dashboard.

---

## 🎨 Core Color Palette

### 1. Primary & Brand Colors
| Swatch | Name | Hex Code | Usage |
| :--- | :--- | :--- | :--- |
| `#573a46` | **Plum Dark** | `#573a46` | Main brand color, active nav items, hero cards, primary buttons |
| `#422c36` | **Plum Deep** | `#422c36` | Hover state for primary plum elements |
| `#c8753d` | **Saffron / Terracotta** | `#c8753d` | Brand logo mark, expense badges, call-to-action buttons, key highlights |
| `#f2d6b7` | **Soft Saffron / Peach** | `#f2d6b7` | Alert cards, money-out badge background, entry detail callouts |

---

### 2. Surfaces & Backgrounds
| Swatch | Name | Hex Code | Usage |
| :--- | :--- | :--- | :--- |
| `#f7f2e8` | **Warm Paper** | `#f7f2e8` | Main app background with subtle warm ledger grid overlay |
| `#eee6d7` | **Deep Paper** | `#eee6d7` | Sidebar background, card headers, container fills |
| `#faf5ec` | **Cream** | `#faf5ec` | Card container surface, input fields, search boxes |

---

### 3. Income & Status Colors
| Swatch | Name | Hex Code | Usage |
| :--- | :--- | :--- | :--- |
| `#b8d1bf` | **Mint Soft** | `#b8d1bf` | Money-in badge background, safe status pill fills |
| `#3e6e59` | **Deep Mint** | `#3e6e59` | Money-in text color, positive income metrics |
| `#27563d` | **Forest Green** | `#27563d` | Status indicators and positive financial text |

---

### 4. Typography & Ink Tokens
| Swatch | Name | Hex Code | Usage |
| :--- | :--- | :--- | :--- |
| `#30282b` | **Primary Ink** | `#30282b` | Headings, main title typography |
| `#4a3541` | **Plum Ink** | `#4a3541` | Subheaders, drawer text |
| `#6d6260` | **Soft Ink** | `#6d6260` | Subtitles, helper text, nav inactive icons |
| `#7c6e6e` | **Muted Gray** | `#7c6e6e` | Date labels, border sub-lines, category subtitles |
| `#faf3ec` | **Light Text** | `#faf3ec` | High-contrast text rendered over dark plum cards |

---

### 5. Status & Interactive Accents
| Swatch | Name | Hex Code | Usage |
| :--- | :--- | :--- | :--- |
| `#e53e3e` | **Recording Red** | `#e53e3e` | Active mic recording pulse, equalizer bars, live status |
| `#9c4f45` | **Flagged Red** | `#9c4f45` | Warning text ("look closer" anomaly badge) |

---

## 💻 CSS Custom Properties (`index.css`)

```css
.vyaparai-root {
  --va-paper: #f7f2e8;
  --va-paper-deep: #eee6d7;
  --va-ink: #30282b;
  --va-ink-soft: #6d6260;
  --va-plum: #573a46;
  --va-plum-deep: #422c36;
  --va-saffron: #c8753d;
  --va-saffron-soft: #f2d6b7;
  --va-mint: #b8d1bf;
  --va-mint-deep: #3e6e59;
  --va-red: #9c4f45;
}
```

---

## ✒️ Typography Pairing

- **Display Header Font**: `Bricolage Grotesque` (`.va-display`)
- **Body Sans-Serif Font**: `Plus Jakarta Sans`
- **Monospace Financial Numbers**: `Space Mono` (`.va-mono`)
