# solarized-terminal-fixed
Readable Solarized Light/Dark theme for use in Windows Terminal or VS Code

This is a version of the popular [Solarized theme by Ethan Schoonover](https://ethanschoonover.com/solarized/) that fixes some problems of unreadable colors on terminal emulators.

Due to legacy, some colors of the [ANSI escape code standard](https://en.wikipedia.org/wiki/ANSI_escape_code#Colors) are considered hardcoded: this is a frequent problem with `Bright Black`, as it's assumed to be always rendered as a shade of gray. In the default Solarized theme it can be hard to read text in this color, as it's very similar to the background; this is quite apparent when reading compile errors from GCC using the Light variant.

This fixes some of the issues by taking some clues from VS Code's built-in theme, such as, setting `Bright Black` to the same color as `Bright Green`.

The final result looks and feels like the original Solarized theme, but only more compatible. I hope you like it!
