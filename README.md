for use in wsl: using the winyank, setup from the following link:
https://github.com/neovim/neovim/wiki/FAQ#how-to-use-the-windows-clipboard-from-wsl
this is also why in set.lua the clipboard is set with unnamedplus

required package: ripgrep
https://github.com/BurntSushi/ripgrep

Delete old nvim setups:
```bash
rm -rf nvim
rm -rf ~/.local/share/nvim
rm -rf ~/.local/state/nvim
```
