# Changelog

## 1.1.0

- Explicit semantic token colors. Python colors no longer change once Pylance finishes loading: `self`/`cls` stay red (they used to turn orange), brackets stay cyan (they used to turn white).
- Python: decorators, f-string placeholders and format specs, string escapes (`\n`, `{{`) and keyword arguments now have their own colors. `self`/`cls` in signatures match their uses in method bodies.
- Integrated terminal: all 16 ANSI colors follow the theme palette.
- Editor: selection, word highlight, cursor, bracket pair colorization, bracket match, indent guides, whitespace, and error/warning/info colors.
- Explorer: Git decoration colors.
- Jupyter notebooks: editor background, focused cell/editor borders, output container.
- Better contrast: inactive title bar text, editor ruler, remote status bar item, LaTeX comments.
- TikZ: highlighting now also works in `tikzcd` diagrams (`\arrow`, `"labels"`, `&`), inline `\tikz`, and pgfplots (`\addplot`, `\addlegendentry`, `\pgfplotsset`).

## 1.0.20

- TikZ syntax highlighting inside `tikzpicture`: drawing commands, option keys, numbers with units, path operators and keywords.

## 1.0.19

- Leftover default colors (notifications, peek view, checkboxes, settings dropdowns, debug toolbar) now match the theme palette.
- String quotes use the string color instead of the comment color.
- Removed nonexistent notebook color keys; inactive list selection is visible again.
- The `.vsix` package no longer bundles `node_modules` (3.7 MB → 470 KB).

## 1.0.18

- Syntax highlighting updates for LaTeX.

For older versions, see the [commit history](https://github.com/sergiokapone/psm-theme/commits/master).
