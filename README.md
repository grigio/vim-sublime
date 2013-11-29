# Vim sublime

A ready to use minimal Vim (Sublime Text -like) .vimrc configuration

![](vim-sublime.gif)

<p align="center">
 ( <a href="https://github.com/grigio/vim-sublime/raw/master/vim-sublime.gif">Play Video</a> )
</p>

## Features included and Shortcuts

*vim-sublime* includes [Vundle](https://github.com/gmarik/vundle) package manager and some external plugins.

The shortcuts should work in vim (terminal with 256 colors) on Linux, Mac OS X and Windows (I'm joking, I don't know).

*Everywhere*

- `ctrl` + `p` - Open other files in the folder
- `ctrl` + `f` - Find text in the document
- `ctrl` + `z` - Cancel
- `ctrl` + `y` - Redo

*Selection* - after (`esc` + `v`) or (`⇧`+ `v`)

- `ctrl` + `c` - Copy
- `ctrl` + `x` - Cut
- `ctrl` + `p` - Paste
- `ctrl` + `m` - Comment / Decomment
- `ctrl` + `w` + `<tag>` - <tag>Wrap text `</tag>`
- `⇥ Tab` - Comment text
- `⇥ Tab` + `⇧` - Decomment text

*Tabs*

- `ctrl` + `t` - New tab
- `ctrl` + `k` - Close tab
- `ctrl` + `b` - Previous tab
- `ctrl` + `n` - Next tab


## Installation

Install Vundle

`git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle`

Install *vim-sublime* `.vimrc`

`touch .vim/{packages.vim,shortcuts.vim}`

`curl https://raw.github.com/grigio/vim-sublime/master/vimrc > $HOME/.vimrc`

Then open `vim` and run

`:BundleInstall`

(Don't worry about the 'Monokai' error), quit and enter in `vim` again to apply the changes

## Author

Luigi Maselli - http://grigio.org
Some configs are from [subvim](https://github.com/fatih/subvim) another Sublime Text for VIM project

