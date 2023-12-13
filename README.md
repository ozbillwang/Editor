# Editor

[![Editor releases](https://img.shields.io/github/release/markhillard/Editor.svg)](https://github.com/markhillard/Editor/releases)

Editor is a responsive HTML/CSS/JS code editor that renders what you type in real-time. It utilizes the following libraries:

- [jQuery](http://jquery.com/)
- [jQuery UI - Resizable](https://jqueryui.com/resizable/)
- [CodeMirror](https://codemirror.net/)
- [FileSaver.js](https://github.com/eligrey/FileSaver.js)
- [Blob.js](https://github.com/eligrey/Blob.js)
- [typeahead.js](https://twitter.github.io/typeahead.js/)

## Style

- Theme: [Dracula](https://codemirror.net/demo/theme.html#dracula)
- Font: [Fira Code](https://github.com/tonsky/FiraCode)
- Icons: [Font Awesome](https://fontawesome.com/)

## Features

- Auto-Save (Local Storage)
- Resizable Code/Preview Pane
- Preview Pane Width Indicator
- Syntax Highlighting
- Code Folding
- Code Linting
- Tag/Bracket Matching
- Auto-Close HTML Tags
- Eric Meyer's CSS Reset
- Font Resizer
- Text Wrapping Toggles
- Reset Editor Defaults
- Refresh Editor
- Clear Editor
- Run Scripts In Browser
- Save As HTML File
- Dependency Injection

### CodeMirror Keymaps

- [Sublime](https://codemirror.net/demo/sublime.html)
- [Emmet](https://github.com/emmetio/codemirror)

**Note:** If Emmet is enabled the Sublime Keymap will be disabled, and vice-versa.

## Browser Support

Editor works in all modern web browsers and IE10+.

## Test and deployment

Create a new project in [Vercel](https://vercel.com/) with below build commands

![image](https://github.com/ozbillwang/Editor/assets/8954908/474498b6-c08e-4c1f-8b2c-9b901c207a4c)

If you own domain name, you can easily set the custom domain on it.

![image](https://github.com/ozbillwang/Editor/assets/8954908/881d10c2-a10f-4c73-b0e6-d6b1139adf35)

the deployment will be auto-triggered every time, you commit the codes to this repo.
