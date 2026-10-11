# notes

A minimal, distraction-free note-taking web app in the spirit of [blank.page](https://blank.page): a monospace editor with real Vim keybindings on the left, a live Markdown + LaTeX preview on the right. The whole app is one static `index.html`, with no build step, no backend and no npm, so it can be hosted for free on GitHub Pages.

## Features

- **Vim editing**: normal, insert and visual modes; `:w` saves. The current mode is shown in the status bar.
- **Markdown + LaTeX**: `$inline$` and `$$display$$` math rendered with KaTeX.
- **Live preview**: split view on wide screens; on narrow screens, a button toggles between edit and preview.
- **Multiple notes**: a sidebar to create, rename, delete and switch notes.
- **Autosave**: notes are saved to your browser's `localStorage` shortly after you stop typing.
- **Export / import / share**: download a note as `.md`, import a `.md` file, or copy a link that contains the note itself.
- **Theme**: dark or light, following your system setting, with a manual toggle.
- **Shortcuts**: `Alt+N` new note, `Alt+P` toggle preview.
