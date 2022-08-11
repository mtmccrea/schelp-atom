# schelp-syntax package

For loading manually in lieu of properly published atom package:

```
ln -s ~/src/dev/schelp-atom ~/.atom/packages
```
To reload the window with the updated style sheet: `Ctrl+Opt+Cmd+L`

Style definitions for syntax highlighting can be found in:
`/Applications/Atom.app/Contents/Resources/app/apm/templates/theme/styles/base.less`

#### Some links

- [Guide](https://gist.github.com/Aerijo/b8c82d647db783187804e86fa0a604a1)
- [Creating a Theme](https://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#creating-a-theme)
- [Available UI variables](https://github.com/atom/atom-dark-ui/blob/master/styles/ui-variables.less)

This is an Atom Syntax Highlighter for Supercollider Help files.

![General screenshot](https://raw.githubusercontent.com/llloret/schelp-atom/screenshots/screenshots/screenshot1.png?raw=true "Screenshot")

It can detect basic errors in the file, like mismatched end tags, wrong tag names, etc.

![Error detection screenshot](https://raw.githubusercontent.com/llloret/schelp-atom/screenshots/screenshots/screenshot-error-detection.png?raw=true "Screenshot")
