# VimConfig
Some custom vim configurations collected from various sources


### `pathogen` for easy plugin management
- Project source: https://github.com/tpope/vim-pathogen
- Installation: 
  ```bash
  mkdir -p ~/.vim/autoload ~/.vim/bundle && 
  curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
  ```
  then activate by adding the following lines to `~/.vimrc`
  ```
  execute pathogen#infect()
  syntax on
  filetype plugin indent on
  ```
### `vimplus` automated solution for configuring vim
https://github.com/chxuan/vimplus
Help doc for shortcuts is here: https://github.com/chxuan/vimplus/blob/master/help.md
