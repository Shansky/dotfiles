"
" Powerline configuration
"
set rtp+=$HOME/.local/lib/python2.7/site-packages/powerline/bindings/vim/

" Always show statusline
set laststatus=2

" Use 256 colours (Use this setting only if your terminal supports 256 colours)
set t_Co=256

" the following line adds line number to the text.
set nu

" the following line activates the syntax highlighting.
syntax on

" change color theme for vim - check $HOME/.vim/colors/
colors sonoma

" the following line says to vim to highlight the searched words.
set hlsearch

" the following line says to vim to execute incremental search.
set incsearch

" the following line enables the use of the mouse.
set mouse=a

"
" VundleVim Plugin configuration
" more info: https://github.com/VundleVim/Vundle.vim
"
set nocompatible              " be iMproved, required
filetype off                  " required

" set the runtime path to include Vundle and initialize
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

" let Vundle manage Vundle, required
Plugin 'VundleVim/Vundle.vim'

" plugin list
Plugin 'taglist.vim'
Plugin 'snipMate'
Plugin 'closetag.vim'
Plugin 'scrooloose/nerdtree'
Plugin 'pyflakes.vim'
Plugin 'supertab'
Plugin 'tagbar'
Plugin 'AutoComplPop'
Plugin 'tpope/vim-fugitive'
Plugin 'scrooloose/syntastic'
Plugin 'junegunn/goyo.vim'
Plugin 'easymotion/vim-easymotion'
"Plugin 'terryma/vim-multiple-cursors'
" colors list
Plugin 'wombat'
Plugin 'sonoma.vim'

" All of your Plugins must be added before the following line
call vundle#end()            " required
filetype plugin indent on    " required
