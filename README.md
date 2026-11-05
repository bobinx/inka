# Inka

```
╦ ╔╗╔ ╦╔═ ╔═╗
║ ║║║ ╠╩╗ ╠═╣
╩ ╝╚╝ ╩ ╩ ╩ ╩
```

[https://bobinx.github.io/inka/](https://bobinx.github.io/inka/)

A quiet page that remembers. A browser notepad with no signups and no downloads.

Inspired by a browser tweak used as a scratchpad:

```html
data:text/html,<body contenteditable style="font:2rem monospace;padding:2rem">
```

## How to Use

Drag this link to your bookmarks bar for quick access: [**Inka**](https://bobinx.github.io/inka/)

Or open the page and press <kbd>Cmd</kbd> + <kbd>D</kbd> (Mac) or <kbd>Ctrl</kbd> + <kbd>D</kbd> (Windows/Linux).

## Privacy & Storage

- **Local storage:** Notes save to browser `localStorage` as you type. Nothing leaves your machine.
- **No tracking:** Zero cookies, analytics, external scripts, or remote servers.
- **Works offline:** Fully functional without an internet connection. Makes zero network calls once loaded.
- **Cross-tab sync:** Notes sync across open tabs and windows in real time.
- **Plain text export:** Download your note anytime as a `.txt` file with <kbd>Cmd</kbd> / <kbd>Ctrl</kbd> + <kbd>S</kbd>.

If browser storage is blocked or full, Inka shows a warning and keeps editing and download available. Download a backup before closing; unsaved changes are only in the open page. If existing notes cannot be read, Inka won't overwrite them during that visit. Reload to retry reading them.

## Shortcuts

- **Save / Download:** <kbd>Cmd</kbd> / <kbd>Ctrl</kbd> + <kbd>S</kbd>
- **Indent:** <kbd>Tab</kbd> inserts 4 spaces
- **Settings:** Click **Settings ⚙** in the bottom bar to adjust theme, font size, and margins

## Run Locally

Inka is a single self-contained HTML file with no build steps or dependencies:

```bash
git clone https://github.com/bobinx/inka.git
open inka/index.html
```

## License

[MIT](LICENSE)
