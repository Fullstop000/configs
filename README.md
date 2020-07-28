# configs

All config files for setting up handly coding workspace from scratch

## Requirements
- Vim >= 8.0
- Neovim >= 0.4.3
- Nodejs >= 10.12

## Install

> tmux not included

1. Install `vim` or `neovim`
2. Install `nodejs` (>=10.12) 
3. Install [vim-plug](https://github.com/junegunn/vim-plug)
4. Copy `init.vim` to `$HOME/.config/nvim/init.vim`
5. Copy `.vimrc` to `$HOME/.vimrc` 
6. Run `:PlugInstall` in vim/neovim
7. Install coc extensions by following commands
```
:CocInstall coc-highlight
:CocInstall coc-json
:CocInstall coc-explorer
:CocInstall coc-git
:CocInstall coc-rust-analyzer //optional
```
8. Replace `coc-settings.json` in `$HOME/.config/nvim`
9. Run `:CocRestart`
10. Restart vim/neovim

### Install `fzf`, `bat` and `ripgrep`
- [fzf](https://github.com/junegunn/fzf)
- [bat](https://github.com/sharkdp/bat)
- [ripgrep](https://github.com/BurntSushi/ripgrep)

## Features
- `Go`, `Rust` support
- Awesome tunned theme based on Nord
- Modern coding experience with `coc-git`, `coc-explorer` and `vim-commentary`
- Personal Optimized Key Bindings

### .vimrc
The config for `vim` and `Neovim`

### init.vim
Scripts for initializing `neovim` env from `vim`
Replace this in `$HOME/.config/nvim`

### coc-settings.json

`coc.nvim` config file
Replace this in `$HOME/.config/nvim`

### .tmux.conf
`tmux` config file. Requires using `tmux-mem-cpu-load`

## Complete Plugin List

#### VIM

- [jiangmiao/auto-pairs](https://github.com/jiangmiao/auto-pairs)
- [sherrun/vim-polyglot](https://github.com/sheerun/vim-polyglot)
- [neclide/coc.nvim](https://github.com/neoclide/coc.nvim)
- [fatih/vim-go](https://github.com/fatih/vim-go)
- [vim-airline/vim-airline](https://github.com/vim-airline/vim-airline)
- [vim-airline/vim-airline-themes](https://github.com/vim-airline/vim-airline-themes)
- [christianchiarulli/onedark.vim](https://github.com/christianchiarulli/onedark.vim) 
- [tpope/vim-fugitive](https://github.com/tpope/vim-fugitive)
- [junegunn/fzf](https://github.com/junegunn/fzf)
- [powerman/vim-plugin-autosess](https://github.com/powerman/vim-plugin-autosess)
- [tpope/vim-commentary](https://github.com/tpope/vim-commentary)
- [arcticicestudio/nord-vim](https://github.com/arcticicestudio/nord-vim)

#### COC

> Install coc plugins manually using `CocInstall <plugin>`

- [coc-hightlight](https://github.com/neoclide/coc-highlight)
- [coc-json](https://github.com/neoclide/coc-json)
- [coc-git](https://github.com/neoclide/coc-git)
- [coc-explorer](https://github.com/weirongxu/coc-explorer)
- [coc-rust-analyzer](https://github.com/fannheyward/coc-rust-analyzer)

