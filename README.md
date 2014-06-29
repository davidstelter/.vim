# [vim](http://vim.org)
My vim config. Some of the autocommand goodies and basics came from a .vimrc which was passed around cs.pdx.edu, I
can't remember who it originally came from. The submodules in the bundle dir are loaded with tpope's [vim-pathogen](https://github.com/tpope/vim-pathogen).

My current favorite colorscheme is [jellybeans](https://github.com/nanotech/jellybeans.vim), though sometimes I favor [inkpot](https://github.com/ciaranm/inkpot). Both are included.

The [vim-airline](https://github.com/bling/vim-airline) setup benefits from use of the [powerline](https://github.com/Lokaltog/powerline) font with special characters. Good luck if you're using xterm, I actually switched to terminator just for the joy of the silly arrows. I couldn't get it to work using uxterm with either the patched fonts and the docs say the standalone glyphs need fontconfig in a way that xterm doesn't handle.

There's also [nerdtree](https://github.com/scrooloose/nerdtree) for nice filetree browsing, and the excellent addon [vim-nerdtree-tabs](https://github.com/jistr/vim-nerdtree-tabs) which keeps the tree consistent across multiple tabs.

[vim-signify](https://github.com/mhinz/vim-signify) is also wonderful, one of those things you don't know you need until you have it and then can't live without. It simply inserts signs for an unobtrusive indicator of edit status.

## tpope
I've got more than just pathogen from [tpope](https://github.com/tpope), specifically:
* [vim-fugitive](https://github.com/tpope/vim-fugitive), which replaced some of my own hacky attempts at vimscript with similar functionality.
* [vim-surround](https://github.com/tpope/vim-surround) which makes text editing simply better, it should really just be part of vim's main-line codebase.
* [vim-characterize](https://github.com/tpope/vim-characterize) shows character codes, escape sequences, descriptions, etc.
* [vim-speeddating](https://github.com/tpope/vim-speeddating.git) adds date/time handling to <c-a>/<c-x>, the wonderful increment/decrement operations.
