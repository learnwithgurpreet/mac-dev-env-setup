# My MAC Environment Files 🚀

**IMPORTANT** Use these files at your own risk, they work pretty well for me :)

# Terminal Setup

First install brew on your MAC, The Missing Package Manager for macOS (or Linux) - I like this tag like 😎

> Installation steps can be found here: https://brew.sh/

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

Install [https://ohmyz.sh/](oh-my-zsh)

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Setup [https://github.com/romkatv/powerlevel10k#oh-my-zsh](Powerlevel10k) theme

1. Clone the repository

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

2. Set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`.

### Relevant Files

- [.zshrc](.zshrc) - Zsh Shell Configuration
- [nightking.itermcolors](nightking.itermcolors) - iTerm2 Color Scheme
