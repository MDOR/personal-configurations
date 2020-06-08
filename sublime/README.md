# Sublime Text

To start, try the following steps:

- If not installed, download [Sublime Text](https://www.sublimetext.com/)
- Open the command palette
  - Windows/Linux `ctrl + shift + p`
  - Mac `cmd + shift + p`
- Type `Install Package Control` and press `enter`

You can look for packages in the next link [https://packagecontrol.io/](https://packagecontrol.io/)

### Preferences

- Click `Preferences`
- Click `Settings`.

It will allow to configure the existing configuration, overwritting the default one.

```json
{
  "close_windows_when_empty": false,
  "default_encoding": "UTF-8",
  "default_line_ending": "unix",
  "detect_indentation": false,
  "draw_indent_guides": true,
  "draw_minimap_border": true,
  "draw_white_space": "all",
  "enable_tab_scrolling": false,
  "ensure_newline_at_eof_on_save": false,
  "file_exclude_patterns": [
    ".DS_Store",
    "Desktop.ini",
    "*.pyc",
    "._*",
    "*.log",
    "Thumbs.db",
    ".Spotlight-V100",
    ".Trashes"
  ],
  "find_selected_text": true,
  "folder_exclude_patterns": [".git", "node_modules", ".yarn", ".next"],
  "font_size": 11,
  "highlight_modified_tabs": true,
  "hot_exit": false,
  "ignored_packages": ["Rust", "Vintage"],
  "indent_guide_options": ["draw_active"],
  "line_padding_bottom": 4,
  "match_brackets": true,
  "match_brackets_angle": true,
  "open_files_in_new_window": false,
  "overlay_scroll_bars": "enabled",
  "remember_open_files": false,
  "show_encoding": true,
  "show_line_endings": true,
  "sidebar_default": true,
  "tab_size": 2,
  "tabs_small": true,
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "word_separators": "./\\()\"':,.;<>~!@#$%^&*|+=[]{}`~?",
  "word_wrap": true
}
```

## Text Editor Tools

### [TrailingSpaces](https://github.com/SublimeText/TrailingSpace)

Highlight trailing spaces and remove them, this helps to avoid unnecessary characters and false-positive changes when using version control systems.

### [Sidebar Enhancements](https://github.com/titoBouzout/SideBarEnhancements)

Provides different enhancements to the text editor such as:

- Move to Trash
- Open with
- New file
- etc

### [File Navigator](https://github.com/csch0/SublimeText-File-Navigator)

It helps you to navigate easily and faster within the project.

### [Origami](https://github.com/SublimeText/Origami)

It helps you to customize the distribution of your current environment.

### [Colorsublime](https://packagecontrol.io/packages/Colorsublime)

It helps you to change themes quickly and easily.

### [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter)

It helps to identify tags and brackets by highlight them.

### [Terminal](https://packagecontrol.io/packages/Terminal)

It launches terminals from the current file or the root project folder.

### [File Icon](https://packagecontrol.io/packages/A%20File%20Icon)

Collection of File Icons, to identify better file types.

## Programming Tools

### [Git Gutter](https://github.com/jisaacks/GitGutter)

It shows information about files in GIT repository

- Inserted, Modified and Deleted files
- Diff popup

### [Emmet](https://packagecontrol.io/packages/Emmet)

[https://emmet.io/](https://emmet.io/) extension that allows you to write an abbreviated form of HTML.
Cheatsheet:

- (https://docs.emmet.io/cheat-sheet/)[https://docs.emmet.io/cheat-sheet/]
- (https://devhints.io/emmet)[https://devhints.io/emmet]

### [Editor Config](https://github.com/sindresorhus/editorconfig-sublime)

[Editor Config](https://editorconfig.org/) extension that helps you to keep consistent coding styles between different editors.
Do not recommend to use while using [Prettier](https://prettier.io/).

### [JS Prettier](https://github.com/sindresorhus/editorconfig-sublime)

[Prettier](https://prettier.io/) extension that helps you to keep consistent coding styles between different editors.
Do not recommend to use while using [Prettier](https://prettier.io/)[Editor Config](https://editorconfig.org/).

- Click `Preferences`
- Click `Package Settings`
- In the sub menu click `JS Prettier`
- Click `Settings User`
  It will allow to configure the existing configuration, overwritting the default one.

```json
{
  "prettier_cli_path": "<Prettier Path>",
  "prettier_options": {
    "arrowParens": "avoid",
    "bracketSpacing": true,
    "htmlWhitespaceSensitivity": "css",
    "insertPragma": false,
    "jsxBracketSameLine": false,
    "jsxSingleQuote": true,
    "printWidth": 80,
    "proseWrap": "preserve",
    "quoteProps": "as-needed",
    "requirePragma": false,
    "semi": true,
    "singleQuote": true,
    "useTabs": false,
    "tabWidth": 2,
    "trailingComma": "none",
    "useTabs": false,
    "vueIndentScriptAndStyle": false
  }
}

```

### [SCSS](https://packagecontrol.io/packages/Sass)

Sass and SCSS syntax highlighting for Sublime Text.

### [LESS](https://packagecontrol.io/packages/LESS)

LESS syntax highlighting for Sublime Text.

### [Babel](https://packagecontrol.io/packages/Babel)

Language definitions for ES6+ JavaScript with React JSX syntax extensions.

### [Rust](https://github.com/rust-lang/rust-enhanced)

The official Sublime Text 3 package for the Rust Programming Language.

### [Node JS](https://packagecontrol.io/packages/Nodejs)

The Nodejs Sublime Text 3 Package provides a set of code completion, scripts and tools to work with nodejs.

### [GraphQL](https://github.com/dncrews/GraphQL-SublimeText3)

GraphQL language definition for SublimeText. Finally support syntax highlighting for your GraphQL IDL files!

### [Docker](https://packagecontrol.io/packages/Dockerfile%20Syntax%20Highlighting)

Dockerfile syntax

## Themes

- [Solarized](https://ethanschoonover.com/solarized/)

### Fonts

- [Fire Mono](https://fonts.google.com/specimen/Fira+Mono)
