[![Melpa Status](http://melpa.milkbox.net/packages/djinni-mode-badge.svg)](http://melpa.milkbox.net/#/djinni-mode)

# djinni-mode
Emacs major mode for Djinni files (https://github.com/dropbox/djinni). Djinni is an IDL used to
generate cross-platform interfaces in C++, Objective-C and Java.

## Installation

You simply need to load this package from your initialization file and it will automatically
associate with files with the `.djinni` extension.

## Features

This major mode provides support for syntax highlighting and indentation. It also configures your
compile Emacs variables automatically so that you can compile your Djinni file with `C-c C-c`
(djinni-mode has its own keymap, `djinni-mode-map`). You can customize the script to compile the
Djinni project by using the `djinni-compile-command` variable.
