# Editor info

I have been using bunch of editors and stick to these.

## Sublime

Good for small programs, nice theme & simplicity.
I use it for small C++ codes.
On linux I had problems with diacritics, so it wasn't possible to write markdown
here.

1. Go to `Preferences -> Settings`, I have this configuration
```json
{
   	"color_scheme": "Packages/Boxy Theme/schemes/Boxy Monokai.tmTheme",
   	"folder_exclude_patterns":
   	[
   		".svn",
   		".git",
   		".hg",
   		"CVS",
   		"node_modules"
   	],
   	"font_size": 12,
   	"ignored_packages":
   	[
   		"Vintage"
   	],
   	"tab_size": 2,
   	"theme": "Boxy Monokai.sublime-theme",
   	"translate_tabs_to_spaces": true
   }
```
2. Useful packages:
* A file icon *(nicer icons)*
* All autocomplete *(completion suggestions from other open files)*
* Boxy theme *(nice dark theme)*
* BracketHighlighter *(highlight corresponding bracket)*
* C++11
* Color Highlighter
* Markdown Preview *(ctrl+shift+p -> Markdown Preview: Preview in browser)*
* Package Control *(Package manager, simplifies adding/removing packages)*
* PackageResourceViewer


## Atom

Similar to Sublime but with easier package installation. Little bit slower though.
With correct packages installed, you can code javascript/React here. I also use it
for SQL and markdown.

1. When writing markdown disable remove trailing spaces (as double space is new line in md).
`Settings` -> `Packages` -> type `whitespace` -> uncheck `Remove traling spaces`

2. Packages
* color-picker
* emmet
* language-babel
* language-prolog *(for syntax)*
* lines *(sort, permute, shuffle...)*
* linter
* linter-eslint
* linter-flow
* markdown-preview-plus *(ctrl+shift+p -> Markdown preview: Toggle)*
* multi-cursor
* tree-ignore

## JetBrain products

Most advanced IDE. I use it for all big projects (C++, Java, Android, Obj-C/Swift).
Using Dracula theme.

## Vi/Vim

Used in terminal for really quick operations. Used as default for git.

## Vs-code

Lightweight editor with great plugin support and performance. Probably the best
editor for coding React now.

