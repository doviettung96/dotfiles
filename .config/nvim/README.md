# Installation

```bash
git clone https://github.com/doviettung96/dotfiles
cp .config/nvim ~/.config/nvim
```

## Install on MacOS

### Install neovim
```bash
brew install neovim
```

### Install Python related packages
```bash
pip install  pynvim
pip install jedi
```

### Install fuzzy search packages
```bash
brew install fd
brew install ripgrep
brew install fzf
```

### Install color packages
```bash
brew install bat
```
Note: fzf preview need check bat theme

## Install on Linux
### Install neovim
```bash
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
```

### Install Python related packages
```bash
pip install  pynvim
pip install jedi
```

### Install fuzzy search packages
```bash
apt-get install fd-find
apt-get install ripgrep
apt-get install fzf
```

### Install color packages
```bash
apt-get install bat
```

## file .bashrc or .zshrc

```bash
alias vim='nvim.appimage'
```

## In Vim

Run command `:PlugInstall`
