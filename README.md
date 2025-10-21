## EMSC 3022 / 2025


[![https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>](https://img.shields.io/badge/EMSC3022-Course_Notes-orange)](https://ANU-RSES-Education.github.io/EMSC-3022/book)

[Alternative link](https://anu-rses-education.github.io/EMSC-3022/book/)

## Local Development

### Building the book

The book uses Quarto with interactive Python examples powered by pyodide (Python in the browser via WebAssembly).

To build the book:

```bash
quarto render
```

The built book will be in `_build/book/`.

### Previewing the book locally

Because the book uses pyodide for interactive Python examples, you need to serve it over HTTP (not just open the HTML files directly). Use the included server script:

```bash
python serve-book.py
```

This will:
- Start a local HTTP server (default port 8000)
- Automatically open your browser to view the book
- Auto-select an available port if 8000 is in use

Press `Ctrl+C` to stop the server.

### Requirements

- Quarto
- Python 3.x (for the preview server)
