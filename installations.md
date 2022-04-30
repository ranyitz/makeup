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
git config --global user.name "Ran Yitzhaki"
git config --global user.email "ranyitz@gmail.com"

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

# diff-so-fancy
brew install diff-so-fancy
git config --global core.pager "diff-so-fancy | less --tabs=4 -RFX"
git config --global interactive.diffFilter "diff-so-fancy --patch"
git config --global color.ui true
git config --global color.diff-highlight.oldNormal    "red bold"
git config --global color.diff-highlight.oldHighlight "red bold 52"
git config --global color.diff-highlight.newNormal    "green bold"
git config --global color.diff-highlight.newHighlight "green bold 22"
git config --global color.diff.meta       "11"
git config --global color.diff.frag       "magenta bold"
git config --global color.diff.func       "146 bold"
git config --global color.diff.commit     "yellow bold"
git config --global color.diff.old        "red bold"
git config --global color.diff.new        "green bold"
git config --global color.diff.whitespace "red reverse"

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
```
