# Vim sublime

A ready to use minimal Vim (Sublime Text -like) .vimrc configuration

![](vim-sublime.gif)

<p align="center">
	(<a href="https://github.com/grigio/vim-sublime/raw/master/vim-sublime.gif">Play Video</a>)
</p>

## Installation

*vim-sublime* includes [Vundle](https://github.com/VundleVim/Vundle.vim) package manager and some external plugins.

Install Vundle

`$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

Install *vim-sublime* `.vimrc`

`$ curl https://raw.githubusercontent.com/grigio/vim-sublime/master/vimrc > $HOME/.vimrc`

Then open `vim` and run

`:PluginInstall`

(Don't worry about the 'Monokai' error), quit and enter in `vim` again to apply the changes

You can also add machine specific config to `~/.local.vim`

For best results make sure your $TERM env variable is 256 colours; `export TERM=xterm-256color`

**Note**: to have the correct font in the bottom bar you need a [Powerline](https://github.com/Lokaltog/powerline-fonts) font installed and selected in the terminal.

## Features included and Shortcuts

The shortcuts should work in vim (terminal with 256 colors) on Linux, Mac OS X and Windows (I'm joking, I don't know).

*Everywhere*

- <kbd>Ctrl</kbd> + <kbd>p</kbd> - Open other files in the folder
- <kbd>Ctrl</kbd> + <kbd>f</kbd> - Find text in the document
- <kbd>Ctrl</kbd> + <kbd>z</kbd> - Cancel
- <kbd>Ctrl</kbd> + <kbd>y</kbd> - Redo
- <kbd>F1</kbd>					 - Snippets

*Selection* - after (<kbd>Esc</kbd> + <kbd>v</kbd>) or (<kbd>Shift</kbd>+ <kbd>v</kbd>)

- <kbd>Ctrl</kbd> + <kbd>c</kbd> 		   - Copy
- <kbd>Ctrl</kbd> + <kbd>x</kbd> 		   - Cut
- <kbd>Ctrl</kbd> + <kbd>v</kbd> 		   - Paste
- <kbd>Ctrl</kbd> + <kbd>m</kbd> 		   - Comment / Decomment
- <kbd>Ctrl</kbd> + <kbd>w</kbd> + `<tag>` - `<tag>`Wrap text`</tag>`
- <kbd>Tab</kbd> 						   - Indent text
- <kbd>Tab</kbd> + <kbd>Shift</kbd> 	   - Reindent text

An alternative way to comment is <kbd>Ctrl</kbd> + <kbd>v</kbd> (Visual-block mode)
then <kbd>Shift+i</kbd> add the commenting characters (es. //) and press <kbd>Esc</kbd>.

To decomment, <kbd>Ctrl</kbd> + <kbd>v</kbd>, select the part you want to delete at the beginning
of the line and press <kbd>d</kbd>.

*Tabs*

- <kbd>Ctrl</kbd> + <kbd>t</kbd> - New tab
- <kbd>Ctrl</kbd> + <kbd>k</kbd> - Close tab
- <kbd>Ctrl</kbd> + <kbd>b</kbd> - Previous tab
- <kbd>Ctrl</kbd> + <kbd>n</kbd> - Next tab

## Author

Luigi Maselli - http://grigio.org

If You use Macvim see also [subvim](https://github.com/fatih/subvim), another Sublime Text for VIM project

