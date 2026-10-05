# Changelog

All notable changes to this theme are documented here. The format is based on
[Keep a Changelog](https://keepachangelog.com/).

## [3.0.0] - 2026-10-05

**The editor has a new look.** The workbench keeps the Solitude palette on true black; the
editor now follows [ashen](https://github.com/ficcdaf/ashen.nvim), the same colours as the
Kultist Neovim theme. **Kultist Classic** is unchanged.

### Changed

- Syntax: grey structure (text `#b4b4b4`, functions `#e5e5e5`, types and properties
  `#d5d5d5`, comments and brackets `#737373`), dark red keywords and decorators, salmon
  strings, orange operators, constants and modules, amber delimiters, teal numbers, booleans,
  builtin types and `this` / `self`. Python docstrings are strings. Keywords are no longer bold.
- Markdown: italics and quotes are italic again; headings dark red, links salmon, lists orange.
- Editor area and gutter: dimmer line numbers, grey current line and selection, orange
  current find match, neutral grey indent guides, and ashen colours for git changes in the
  gutter (grey added, amber modified, red deleted) and for errors (`#c53030`) and warnings
  (`#e5a72a`).
- Integrated terminal: cursor `#a5aeb4`, selection `#a5aeb4` on `#343d41`, ANSI white
  `#cacccc`, matching Omarchy's Solitude terminal.

## [2.0.0] - 2026-10-04

**Kultist has a new look.** The previous theme is still included, unchanged, as
**Kultist Classic**: pick it in **Preferences: Color Theme**, or set
`"workbench.colorTheme": "Kultist Classic"`.

### Changed

- **Kultist** now uses the Solitude palette on true black: monochrome greys for the
  structure of the code, shades of a red accent (`#de6145`) for keywords, literals and
  operators, and no italics.
- Workbench: flat true black surfaces with few, dark borders; black menus, command palette,
  suggestions and hovers; the integrated terminal uses the 16 Kultist ANSI colours.
- Readable highlights: dark selection, outlined find matches, and tuned contrast for
  comments, operators, inlay hints and placeholders.
- Licence is now CC0-1.0.
- Requires VS Code 1.85 or later.

### Added

- **Kultist Classic**: the 1.1.0 theme.
- Published on [Open VSX](https://open-vsx.org/extension/codekult/kultist-color-theme) too,
  for VSCodium, Code - OSS, Cursor and other compatible editors.

## [1.1.0] - 2023-01-09

### Changed

- Improved contrast and colours.
- Fixed highlighting on wrapped lines, border on the active tab, translucent scrollbar
  (thanks [@Coachonko](https://github.com/Coachonko), #4).

## [1.0.3] - 2022-02-17

- Improved editor selection colours.

## [1.0.1] and [1.0.2] - 2021-11-19

- Updated the active line and selection backgrounds.

## [1.0.0] - 2021-11-17

- Initial release.
