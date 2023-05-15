# My Neovim Config (Mine's might not be the best for you. Because the best config is the one configured by yourself)
 
## Screenshots

### Dashboard (Alpha Nvim)
![Dashboard](https://github.com/BIBJAW/myneovim/blob/main/myneovimSS/dashboard.png?raw=true)
### Coding UI
![CodeUI](https://github.com/BIBJAW/myneovim/blob/main/myneovimSS/codex.png?raw=true)
### With Tmux
![Coding](https://github.com/BIBJAW/myneovim/blob/main/myneovimSS/Coding.png)
### LSP Manager (Mason)
![Mason As Language Server](https://github.com/BIBJAW/myneovim/blob/main/myneovimSS/mason.png?raw=true)
### Package Manager (Lazy Nvim)
![Lazy nvim as Packager Manager](https://github.com/BIBJAW/myneovim/blob/main/myneovimSS/pkgm.png?raw=true)

### Aditional Packages:

- ripgrep
- lazygit
- npm
- tmux
## Installation
```
git clone https://github.com/BIBJAW/myneovim && cp -r ~/myneovim/nvim .config/
```
## File Tree
```
nvim
.
├── init.lua
├── lazy-lock.json
└── lua
    ├── core
    │   ├── init.lua
    │   ├── keymaps.lua
    │   ├── lazy.lua
    │   └── options.lua
    └── plugins
        ├── alpha-nvim.lua
        ├── autopairs.lua
        ├── bufferline.lua
        ├── cmp.lua
        ├── colorizer.lua
        ├── comments.lua
        ├── diagonistic-signs.lua
        ├── indent-blankline.lua
        ├── init.lua
        ├── lorem-nvim.lua
        ├── lsp.lua
        ├── lsp-saga.lua
        ├── lualine.lua
        ├── notify.lua
        ├── null-ls.lua
        ├── nvim-tree.lua
        ├── telescope.lua
        ├── toggleterm.lua
        ├── transparent-nvim.lua
        ├── treesitter.lua
        └── whichkey.lua
```
