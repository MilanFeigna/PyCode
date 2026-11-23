# PyCode (Python editor by Milan Feigna) v.6.95

**PyCode** is a lightweight desktop Python IDE built with Python and Tkinter. It combines a responsive code editor, a visual step-by-step debugger, a live variable inspector, and integrated consoles in a clean, high-DPI interface.

---

## Features

### Editor
- **Syntax Highlighting:** Full tokenization for Python syntax, docstrings, f-strings, `.format()` strings, regular expressions, and hex color literals (`#RRGGBB`).
- **Inline Autocomplete:** Context-aware ghost-text suggestions for variables, functions, classes, imported modules, and keyword arguments (`Tab` to cycle, `Enter` to accept).
- **Editing Helpers:** Auto-closing brackets and quotes, line commenting (`Ctrl+/`), quick colon + newline (`Ctrl+:`), symbol occurrence highlighting, and matching bracket indicators.
- **Navigation & Search:** Live search bar with match counter (`Ctrl+F`), breadcrumbs (`File → Class → Function → Line`), and go-to-line (`Ctrl+L`).
- **Large File Support:** Background tokenization and viewport-based rendering to keep large scripts smooth.

### Debugger
- **Breakpoints:** Toggle breakpoints directly from the editor gutter or with `Ctrl+Alt+B`.
- **Execution Controls:** Step Over, Step Into, Step Out, Continue, and Restart.
- **Inline Evaluation:** Live preview of expression values, loop iterations, and branch outcomes during debugging.
- **Interactive Tracebacks:** Click any file path or line number in an error traceback to jump straight to that line in the editor.

### Consoles & Tools
- **Console:** Run the current script (`Ctrl+R`), selected code (`Ctrl+Shift+Enter`), or the current line (`Ctrl+Enter`) in an isolated worker process with ANSI color support.
- **Root Console:** Dedicated execution window with size presets (`x1`, `x2`, `x3`, Fullscreen).
- **Variables Tool (`Ctrl+Shift+V`):** Real-time table of variables, types, container lengths, and values during execution, with search, type filtering, and export to `.pdf`, `.xlsx`, or `.txt`.
- **Integrated Terminal (`Ctrl+T`):** Built-in system shell with command history and syntax coloring.
- **Color Tool (`Ctrl+K`):** Live HEX and RGB color converter.

### Interface
- **Themes:** Dark (`#0`), Light (`#F`), and System (`#S`) modes.
- **Typography & Scaling:** Embedded *Cascadia Mono* font and *Material Symbols* icons with automatic DPI scaling.

---

## Getting Started

### Requirements
- **Python 3.10+** (Tkinter included)
- Optional dependencies for icon rasterization and PDF export:
  
```bash
pip install pillow reportlab
```

### Run from Source
```bash
git clone https://github.com
cd PyCode
python PyCode.py
```

---

## Current Update

PyCode Version: `v.6.95`

## Code Signing

Free code signing provided by [SignPath.io](https://signpath.io), certificate by [SignPath Foundation](https://signpath.org).

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

## Author

Developed by **Milan Feigna**, with AI assistance.
