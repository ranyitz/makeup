```sh

# xcode
xcode-select --install

# brew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# iterm2
brew install iterm2 --cask

# zsh
brew install zsh

# oh-my-zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# vscode
brew install visual-studio-code --cask

# nerd font
brew tap homebrew/cask-fonts && brew install font-Fira-Code-nerd-font

# starship shell
brew install starship

# fnm
curl -fsSL https://fnm.vercel.app/install | bash

# watchman
brew install watchman

# latest git
brew install git

# git configuration
git config --global user.name "<Your Name>"
git config --global user.email "<yourname@gmail.com>"
git config --global --add --bool push.autoSetupRemote true

# rectangle
brew install --cask rectangle

# tldr
brew install tldr

# fzf
brew install fzf
$(brew --prefix)/opt/fzf/install

# rg
brew install ripgrep

# z
git clone https://github.com/agkozak/zsh-z $ZSH_CUSTOM/plugins/zsh-z

# zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# cron
brew install --cask cron

# meetingbar
brew install meetingbar

# bat
brew install bat
alias cat="bat"

# git delta
brew install git-delta
git config --global core.pager "delta"
git config --global interactive.diffFilter "delta --color-only"
git config --global merge.conflitstyle "diff3"
git config --global diff.colorMoved "default"
git config --global delta.navigate true
git config --global delta.line-numbers true
git config --global delta.side-by-side true

# htop
brew install htop

# tig
brew install tig

# spotify
brew install --cask spotify

# yarn
brew install yarn

# kap
brew install --cask kap

# fx - json viewer
brew install fx

# better ls
brew install exa
alias ls="exa"
```
