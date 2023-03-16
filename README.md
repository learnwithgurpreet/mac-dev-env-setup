# My MAC Environment Files 🚀

**IMPORTANT** Use these files at your own risk, they work pretty well for me :)

# Terminal Setup

First install brew on your MAC, The Missing Package Manager for macOS (or Linux) - I like this tag like 😎

> Installation steps can be found here: [Brew.sh](https://brew.sh/)

```bash
brew install --cask iterm2
```

```bash
brew install nvm
```

For XCode Command Line Tools do:

```bash
xcode-select --install
```

Install [oh-my-zsh](https://ohmyz.sh/)

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Setup [Powerlevel10k](https://github.com/romkatv/powerlevel10k#oh-my-zsh) theme

1. Clone the repository

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

2. Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`.

### Update VSCode Terminal Font (Optional)
Open `settings.json` of your vscode and add `"terminal.integrated.fontFamily": "MesloLGS NF"`

### Relevant Files

- [.zshrc](.zshrc) - Zsh Shell Configuration
- [nightking.itermcolors](nightking.itermcolors) - iTerm2 Color Scheme

## Plugins

- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)
