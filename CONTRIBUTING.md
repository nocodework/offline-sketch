# Contributing

Thanks for considering a contribution. This project is deliberately tiny and dependency-free, and the goal is to keep it that way.

## Ground rules

- **One file.** The whole app lives in `index.html` — HTML, CSS, and vanilla JS. No build step, no bundler, no npm, no framework.
- **Zero runtime dependencies.** No CDN links, no web fonts, no analytics. The page must make **0 network requests** so it keeps working fully offline. PRs that add a network call will be declined.

## Running it

There's nothing to install. Open `index.html` in a browser, edit the file, refresh. A stylus (Apple Pencil, Wacom) is the best way to test pressure.

## Before opening a PR

- Test by hand with a mouse and, if you can, a stylus: draw, erase, change colour and size, undo/redo, clear, export PNG, export and re-import `.json`, reload (autosave).
- Confirm there are still **0 network requests** (DevTools → Network → reload).
- Keep the diff focused and describe what changed and why.

## Ideas that fit

- Smoother strokes, more brushes, fill/shapes
- Pan and zoom, layers
- Better touch / palm rejection
- Accessibility improvements

## Ideas that don't fit

- Anything requiring a server, account, or network call
- Heavy libraries or a build pipeline

By contributing you agree your work is licensed under the project's [MIT License](LICENSE).
