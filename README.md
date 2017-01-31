# Introduction to Vim for Developers

## Intro
- Why Vim?
    - speed
    - accuracy
    - ubiquity
    - DRY
- Learning
    - vimtutor
    - online help: `:help`

## Basics
- Normal mode commands: `i`, `a` etc.
    - copy: `y`ank
    - paste: `p`ut
    - cut: `d`elete
- Insert mode
- Motion
- Text objects

## Intermediate
- Repetition (count, `.`)
- Buffers, Windows
- Registers, Marks
- Undo/redo
- Split

## Vimrc, Plugins
- [Vundle](https://github.com/gmarik/Vundle.vim): Plugin manager
- Programming language support (go to definition, autocomplete etc.):
    - [tagbar](https://github.com/majutsushi/tagbar): Display and browse classes, functions etc.
    - [jedi-vim](https://github.com/jedi-vim): Integration for Python
    - [vim-go](https://github.com/fatih/vim-go): Integration for Go
    - [nerdcommenter](https://github.com/scrooloose/nerdcommenter): Easily comment code
    - [syntastic](https://github.com/vim-syntastic/syntastic): Syntax checking for many languages
- General:
    - [supertab](https://github.com/ervandew/supertab): Smart tab completion
    - [fugitive](https://github.com/tpope/vim-fugitive): Git integration
    - [Ctrl-P](https://github.com/ctrlpvim/ctrlp.vim): Fuzzy file finder and opener
    - [nerdtree](https://github.com/scrooloose/nerdtree): File browser
    - [gundo](https://github.com/sjl/gundo.vim): Git-like undo history for Vim buffers
    - [abolish](https://github.com/tpope/vim-abolish) camel case, underscores conversion

## Advanced
- Diff
- Git integration
- Client/server

## Resources
- [My `vimrc` file](https://github.com/gavrie/vim/blob/master/vimrc)
- http://vimawesome.com/
