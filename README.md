# 🧮 Notion Dark Theme Calculator

A minimal dark-theme calculator designed to embed seamlessly inside Notion pages via the `/embed` block. Matches Notion's dark background with zero visual gap.

---

## ✨ Features

- Clean Notion dark color scheme (`#191919` background)
- Background `#191919` — matches Notion's exact dark theme color, no black border visible
- Basic operations: `+` `−` `×` `÷` `%`
- Expression history line above the display
- Backspace (⌫) and clear (AC)
- Keyboard support

---

## 📋 How to embed in Notion

1. Open your Notion page
2. Type `/embed` and press **Enter**
3. Paste this URL:

```
https://yhommy741.github.io/Notion-Dark-Theme-Calculator/
```

4. Press **Enter** — the calculator appears inline

> **Tip:** Resize the embed block by dragging the bottom edge to fit the calculator (around 320 × 420 px works well).

---

## ⌨️ Keyboard shortcuts

| Key | Action |
|-----|--------|
| `0–9` | Enter digits |
| `+ - * /` | Operators |
| `.` | Decimal point |
| `Enter` or `=` | Calculate |
| `Backspace` | Delete last character |
| `Escape` | Clear all |

---

## 🛠 How to customize

1. Go to the repo on GitHub
2. Click `index.html` → click the **pencil icon ✏️** to edit
3. Make your changes
4. Click **Commit changes**
5. Wait ~1 minute — the live embed updates automatically

### Change the accent color

Find this line in `index.html` and replace `#e1b024` with any color you like:

```css
.op  { background: #2d2d2d; color: #e1b024; }  /* operator text color */
.eq  { background: #e1b024; color: #191919; }  /* equals button */
```

### Change the button size

Find `.grid` and adjust the `gap`, and find `button` to adjust `height`:

```css
.grid  { gap: 6px; }
button { height: 56px; }
```

---

## 🚀 Deploy your own copy

1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch → `/root`
4. Save — your URL will be: `https://YOUR_USERNAME.github.io/Notion-Dark-Theme-Calculator/`
5. Use that URL in Notion's `/embed`

---

## 📄 License

MIT — free to use and modify.
