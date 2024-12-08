# vsc--de.init
Vscode... dotfiles?! Bootstrap your vscode, if you want.

Keybindings in an attempt to make vscode interface in a way similar to [my neovim dotfiles](https://github.com/pbootly/init.nvim)

# Setup:

## Install required dependencies
- `vscode`
- `ripgrep`
- `fzf`
- `bat`

## Install extensions
`xargs -n 1 code --install-extension < extensions.txt`

## Copy settings.json to vscode dir
According to [online documentation](https://code.visualstudio.com/docs/getstarted/settings) that'll be:

> Windows %APPDATA%\Code\User\settings.json
> 
> macOS $HOME/Library/Application\ Support/Code/User/settings.json
> 
> Linux $HOME/.config/Code/User/settings.json

Alternatively open settings with `Preferences: Open User Settings (JSON)` command palette and pasting the contents from this repo there.

Now when you open vscode, go to zen mode and navigate with motions that should let you cope
