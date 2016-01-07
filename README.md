chuck.vim
=========

A vim plugin for [ChucK](http://chuck.stanford.edu/), a programming language for
real-time sound synthesis and music creation. Currently supports syntax highlighting,
and controling the Chuck VM(e.g. starting/stopping shreds).



installation
------------

This plugin depends on [vimproc](https://github.com/Shougo/vimproc.vim) for controlling the Chuck VM.

This plugin is [vundle](https://github.com/gmarik/vundle) and
[pathogen](https://github.com/tpope/vim-pathogen/) compatible. The simplest way
to get it installed is to use one of those.

For vundle, install by adding the repo to your list of plugins in your .vimrc

    " vundle up
    filetype off
    set rtp+=~/.vim/bundle/Vundle.vim
    call vundle#begin()

    " let vundle manage itself
    Plugin 'gmarik/Vundle.vim'
    Plugin 'Shougo/vimproc.vim'
    Plugin 'highwaynoise/chuck.vim'

    call vundle#end()
    filetype plugin indent on

Then install using vundle inside vim.

    :PluginInstall

Or you can also copy the files manually to their corresponding directories in
your `~/.vim/` directory if you're into the taste of awfulness.


