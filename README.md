# pyfunclist vim plugin

Quickly view and jump to functions in a Python module.

Acknowledgment: this is slightly tweaked version of Sandeep C.R.'s Functionlist plugin for JavaScript: https://github.com/vim-scripts/functionlist.vim

## configuration

Suggested: map to leader+z like so in your .vimrc:

    :nnoremap <Leader>z :Flisttoggle<CR>

To show functions in alphabetical order (rather than in physical order), uncomment `call s:reindex()` inside the function `function! s:oninsertchange()`.

