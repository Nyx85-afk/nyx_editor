# Nyx Editor ✦

👉 [**Try the Live Demo on Neocities**](https://your-neocities-url-here.neocities.org)

A clean, distraction-free markdown editor that lives in a single HTML file. No install, no server, no dependencies. Just open it and write.

---

## Features

- **Live preview** — renders as you type, editor left, preview right
- **Autosave** — your work saves automatically to browser localStorage
- **Open & save** — load `.md` files, save them back with their original filename
- **Export to HTML** — one click produces a styled, self-contained HTML page ready to publish
- **Emoji picker** — searchable emoji panel built into the toolbar
- **Markdown cheat sheet** — quick reference always one click away
- **Welcome screen** — new users get a guided introduction
- **Beautiful typography** — Fraunces serif for reading, JetBrains Mono for writing
- **Dark theme** — easy on the eyes, built for long writing sessions

---

## Usage

No installation required. Just download `nyx_editor.html` and open it in any modern browser.

```
1. Download nyx_editor.html
2. Open it in Chrome, Firefox, or any modern browser
3. Write
```

That's it.

---

## Toolbar reference

| Button   | Action                         |
| -------- | ------------------------------ |
| B I S    | Bold, italic, strikethrough    |
| ` `      | Inline code                    |
| H1 H2 H3 | Headings                       |
| ❝        | Blockquote                     |
| • list   | Bullet list                    |
| 1. list  | Numbered list                  |
| —        | Horizontal divider             |
| [ link ] | Insert link                    |
| ☺ emoji  | Emoji picker                   |
| ✦ new    | New document                   |
| ↑ open   | Open a `.md` or `.txt` file    |
| ⎘ copy   | Copy raw markdown to clipboard |
| ↓ save   | Download as `.md`              |
| ⇥ html   | Export as styled HTML          |
| ? help   | Markdown cheat sheet           |

---

## A note on saving

Because Nyx Editor runs as a local HTML file, it uses browser localStorage for autosave. This means:

- Your work persists between sessions automatically
- If you move `nyx_editor.html` to a different folder, localStorage resets — pick a permanent home for it
- **↓ save** downloads a proper `.md` file you can back up anywhere
- To update an existing file, let the browser replace it when prompted on download

Full native file system access is planned for the Tauri desktop app release.

---

## Roadmap

- [ ] Syntax highlighting in the editor pane
- [ ] Tauri desktop app (Linux, Windows, macOS)
- [ ] Native file open/save dialogs
- [ ] Word count goals

---

## Tech

Built with vanilla HTML, CSS and JavaScript. Zero build steps, zero frameworks, zero dependencies except:

- [marked.js](https://marked.js.org/) — markdown parsing
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — editor font
- [Fraunces](https://fonts.google.com/specimen/Fraunces) — preview font

---

## License

MIT — do whatever you like with it. A credit is always appreciated but never required.

---

_Built with ❤️ and Claude_
