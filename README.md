# vim

```

call pathogen#infect()
filetype plugin indent on
map <F3> :NERDTreeMirror<CR>
map <F3> :NERDTreeToggle<CR>
set cursorline
set nu
set showcmd
set showmatch
set spell spelllang=en_us 
set visualbell
set wildmenu
set hlsearch
set incsearch
set wrap
set ignorecase

map <F4> :vsplit<CR>
map <F2> :Tlist<CR>
syntax on

:inoremap ( ()<Esc>i
:inoremap [ []<Esc>i
:inoremap < <><Esc>i
:inoremap { {<CR>}<Esc>O
:inoremap " ""<Esc>i
:inoremap ' ''<Esc>i
set ts=4

```




