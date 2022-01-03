## Comands

- The space key is mapped to the leader key
- Use jk or kj to escape out of insert mode(I recommend using the caps lock key as escape)
- Leader + e is to toggle the file tree
- Leader + l is used to open lazygit
- Alt + hjkl are used to resize windows
- Ctrl + hjkl are used to navigate around windows
- Tab and Shift-Tab are used to cycle through buffers
- K and J are used to move the selected text up or down in visual mode
- Leader + / is used to comment or uncomment the current line in normal mode and selected lines in visual mode
- Leader + r is used to grep text using telescope
- Leader + f is used to find files using telescope
- Leader + b is used to search buffers using telescope
- s is used to hop two characters using hop.nvim
- S is used to hop words using hop.nvim
- Ctrl + jk is used to navigate through the completion menu
- You can use both Leader + t or Ctrl + \ to open toggleterm
- Shift + k is used for lspsaga hover doc
- gd is for go to definition
- gD is for go to declaration
- gr is for references
- gi is for implementation
- ca is for code actions
- Leader + z is for zen mode. If you have zen-mode, then Twilight is activated automatically.

## Installation

```
git clone https://github.com/PrinceP/nvim ~/.config/nvim
nvim +PackerSync
```

## Requirements

- [Neovim Version > 0.5](https://github.com/neovim/neovim/releases/tag/v0.5.0) - Required - For lua configuration
- [NodeJS](https://nodejs.org) - For LSP
- [Lazygit](https://github.com/jesseduffield/lazygit) - For git integration
- [RipGrep](https://github.com/BurntSushi/ripgrep) - For telescope live grep
- [black, codespell, prettier](https://github.com/jose-elias-alvarez/null-ls.nvim/blob/main/doc/BUILTINS.md) - For null-ls
