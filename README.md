# [vim](http://vim.org)
My vim config. Some of the autocommand goodies and basics came from a .vimrc which was passed around cs.pdx.edu, I
can't remember who it originally came from. The submodules in the bundle dir are loaded with tpope's [vim-pathogen](https://github.com/tpope/vim-pathogen).

If your vim is new enough it will use the .vim/vimrc file, but if it's a little older you'll need to help it out with a symlink which can be created like so:

```bash
ln -s ~/.vim/vimrc ~/.vimrc
```

My current favorite colorscheme is [jellybeans](https://github.com/nanotech/jellybeans.vim), though sometimes I favor [inkpot](https://github.com/ciaranm/inkpot). Both are included.

The [vim-airline](https://github.com/bling/vim-airline) setup benefits from use of the [powerline](https://github.com/Lokaltog/powerline) font with special characters.
I found a short writeup that got the cute arrow symbols working in urxvt here: http://makandracards.com/jan0sch/18283-enable-powerline-fonts-with-rxvt-unicode-and-vim-airline
The docs say the standalone glyphs need fontconfig in a way that xterm doesn't handle.

For urxvt to use the Terminess Powerline font, the following is needed in your `~/.Xresources` or other xrdb sourced file:

````
URxvt*font: xft:Terminess Powerline:size=9
```

## tpope
I've got more than just pathogen from [tpope](https://github.com/tpope), specifically:
* [vim-fugitive](https://github.com/tpope/vim-fugitive), which replaced some of my own hacky attempts at vimscript with similar functionality.
* [vim-surround](https://github.com/tpope/vim-surround) which makes text editing simply better, it should really just be part of vim's main-line codebase.
* [vim-characterize](https://github.com/tpope/vim-characterize) shows character codes, escape sequences, descriptions, etc.
* [vim-speeddating](https://github.com/tpope/vim-speeddating.git) adds date/time handling to `<c-a>/<c-x>`, the wonderful increment/decrement operations.

## assorted plugins
* [nerdtree](https://github.com/scrooloose/nerdtree) for nice filetree browsing, and the excellent addon [vim-nerdtree-tabs](https://github.com/jistr/vim-nerdtree-tabs) which keeps the tree consistent across multiple tabs.
* [vim-signify](https://github.com/mhinz/vim-signify) is also wonderful, one of those things you don't know you need until you have it and then can't live without. It simply inserts signs for an unobtrusive indicator of edit status.
* [phpcomplete.vim](https://github.com/shawncplus/phpcomplete.vim) adds wonderful function completion and other niceties.
