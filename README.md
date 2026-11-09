<div align="center">

<img src="docs/icon.png" width="96" alt="study-files" />

# study-files

**A filesystem-first notes app for classwork.**

Your notes are ordinary Markdown files in ordinary folders. No database, no account,
no sync service, no subscription — open your notes in any editor, on any machine,
and everything is exactly where you left it.

### [⬇ Download the latest release](../../releases/latest)

![Windows](https://img.shields.io/badge/Windows-installer%20%7C%20portable-2d7d5a?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-AppImage%20%7C%20deb%20%7C%20rpm-2d7d5a?style=flat-square)
![Price](https://img.shields.io/badge/price-free-2d7d5a?style=flat-square)
![Offline](https://img.shields.io/badge/network%20requests-none-2d7d5a?style=flat-square)

<img src="docs/screenshots/01-light.png" width="900" alt="study-files editing a biology note" />

</div>

---

## Download

| Platform | File | Notes |
| --- | --- | --- |
| **Windows** | `study-files-Setup-<version>.exe` | Installer. Installs for your user only — no administrator prompt |
| **Windows** | `study-files-<version>-portable.exe` | Single file. Run it from anywhere, including a USB stick |
| **Linux** | `study-files-<version>-linux-x86_64.AppImage` | `chmod +x` it and run. Works on most distributions |
| **Linux** | `study-files-<version>-linux-amd64.deb` | Debian, Ubuntu, Mint |
| **Linux** | `study-files-<version>-linux-x86_64.rpm` | Fedora, RHEL, openSUSE |

All builds are 64-bit. Get them from the [releases page](../../releases/latest).

> **Windows SmartScreen** may warn you the first time, because these builds are not
> code-signed — a certificate costs several hundred dollars a year. Click **More info** →
> **Run anyway** if you trust the source.

## Light and dark

Follows your desktop theme by default, or pin it to one.

<table>
<tr>
<td width="50%"><img src="docs/screenshots/01-light.png" alt="Light theme" /></td>
<td width="50%"><img src="docs/screenshots/02-dark.png" alt="Dark theme" /></td>
</tr>
<tr>
<td align="center"><sub><b>Light</b></sub></td>
<td align="center"><sub><b>Dark</b></sub></td>
</tr>
</table>

## Search everything

<kbd>Ctrl</kbd> <kbd>K</kbd> searches titles and note bodies, with the match highlighted in
context.

<img src="docs/screenshots/03-search.png" width="900" alt="Search palette" />

## Your notes are just files

```
Documents/study-files/
  Biology 201/
    cell-membranes.md
    cell-membranes-assets/diagram-1.png
```

Every note is a Markdown file with a small YAML header. Nothing is locked in a proprietary
format, nothing lives in a cloud you don't control, and if you stop using this app your
notes are still perfectly readable.

Writes are **atomic**, so a crash mid-save cannot corrupt a note. Deletes go to your
**system trash**, not straight to oblivion. Edit a note in another app and study-files picks
up the change automatically.

## Features

- **Rich editing** — headings, bold, italics, underline, highlight, lists, callouts,
  tables, and inline images. <kbd>Tab</kbd> and <kbd>⇧</kbd> <kbd>Tab</kbd> indent a bullet
- **Drawing board** — <kbd>Ctrl</kbd> <kbd>D</kbd> opens a white board that takes the whole
  window: maximise it and you get more paper, not bigger ink. Pen pressure sets the nib
  width, and strokes are recorded as drawn — nothing is straightened or "corrected"
- **An eraser that erases** — it rubs ink out where it passes, so a line can be taken out of
  the middle of a word, or latch the button beside it to lift whole lines instead. A pen's
  eraser end and either of its barrel buttons reach it without changing tool; hold a barrel
  button while you write and it rubs, let go and it draws
- **Palm rejection** — a hand resting on a touchscreen draws nothing and cannot close the
  board mid-drawing
- **Drawings stay editable** — a drawing keeps the strokes it was made of inside its own
  PNG, so opening it brings the lines back, ready to change. The file is an ordinary PNG
  everywhere else
- **Move things around** — pick lines up on the board and slide them; drag a picture to
  another spot in the note, or move it a row at a time with <kbd>Alt</kbd> <kbd>↑</kbd> /
  <kbd>↓</kbd>. Delete one by accident and <kbd>Ctrl</kbd> <kbd>Z</kbd> brings it back
- **Find in the note** — <kbd>Ctrl</kbd> <kbd>F</kbd> searches the note you are reading,
  with match counts and <kbd>Enter</kbd> to step through
- **Charts** — a fenced `chart` block is drawn underneath itself, and stays plain text in
  the Markdown
- **Outline** — generated from your headings, with scroll tracking
- **Folders and tags** — organise by class, find things fast
- **Export** — hand a note to someone else as Markdown with its images
- **Completely offline** — no telemetry, no accounts, no network requests of any kind
- **Accessible** — full keyboard navigation and screen-reader labels

## Keyboard shortcuts

| Shortcut | Action |
| --- | --- |
| <kbd>Ctrl</kbd> <kbd>N</kbd> | New note |
| <kbd>Ctrl</kbd> <kbd>⇧</kbd> <kbd>N</kbd> | New folder |
| <kbd>Ctrl</kbd> <kbd>S</kbd> | Save now |
| <kbd>Ctrl</kbd> <kbd>E</kbd> | Export as Markdown |
| <kbd>Ctrl</kbd> <kbd>F</kbd> | Find in this note |
| <kbd>Ctrl</kbd> <kbd>K</kbd> | Search all notes |
| <kbd>Ctrl</kbd> <kbd>,</kbd> | Settings |
| <kbd>Ctrl</kbd> <kbd>/</kbd> | Shortcuts |
| <kbd>Ctrl</kbd> <kbd>⇧</kbd> <kbd>D</kbd> | Toggle dark mode |
| <kbd>Ctrl</kbd> <kbd>\</kbd> | Toggle sidebar |
| <kbd>Ctrl</kbd> <kbd>D</kbd> | Open the drawing board |
| <kbd>Tab</kbd> / <kbd>⇧</kbd> <kbd>Tab</kbd> | Indent or outdent a bullet |
| <kbd>Ctrl</kbd> <kbd>B</kbd> / <kbd>I</kbd> / <kbd>U</kbd> | Bold, italic, underline |
| <kbd>Ctrl</kbd> <kbd>Z</kbd> | Undo |
| <kbd>F2</kbd> | Rename note |
| <kbd>Esc</kbd> | Close dialog or the drawing board |

## Privacy

study-files makes **no network requests**. Fonts are bundled with the app, its Content
Security Policy forbids outbound connections entirely, and there is no analytics,
telemetry, crash reporting, or update check. Your notes never leave your disk.

## License

Free to use. Not free to sell, modify, or redistribute — see [LICENSE](LICENSE).

This repository distributes the application only; the source is not public.

The bundled DM Sans, DM Mono and Fraunces typefaces are separately licensed under the SIL
Open Font License 1.1, and Electron and its dependencies under their own terms. Their
license texts ship inside the application.

---

<div align="center">
<sub>Questions or a problem with a build? <a href="../../issues">Open an issue</a>.</sub>
</div>
