# jsonl-viewer

> Fast, minimal JSONL file viewer that runs entirely in the browser.

**[jsonl.pakhale.com](https://jsonl.pakhale.com)**

---

## Features

- **Drag & drop** a `.jsonl` file or browse to open
- **Table view** — auto-inferred columns, sortable, lazy-loaded rows
- **JSON view** — formatted tree view per record
- **Search** — filter records in real time
- **Detail panel** — inspect any record with prev/next navigation
- Zero dependencies, zero uploads — everything runs locally in your browser

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| `↑` `↓` | Navigate rows |
| `Enter` | Open detail panel |
| `Esc` | Close panel / clear search |
| `/` | Focus search |
| `T` | Table view |
| `J` | JSON view |
| `O` | Open new file |
| `?` | Show shortcuts |

## Usage

Just go to **[jsonl.pakhale.com](https://jsonl.pakhale.com)** and drop a file.

Or self-host — it's a single `index.html`, no build step needed:

```bash
git clone https://github.com/pratikpakhale/jsonl-viewer
# open index.html in your browser, or serve it:
npx serve .
```
