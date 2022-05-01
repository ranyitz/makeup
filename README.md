# 💄 Makeup

> My opinionated installation guide for developers that use macOS

## Why?

Every time that I install a new mac, I want the same workflow and tooling, it's nice that I can go over this file and always get the same setup.

Another cool thing, is that this repo can be shared with other developers.

## What's inside?

A curated list of applications and installations that can boost your workflow and productivity as a developer.

## Install

```sh
# xcode - https://mac.install.guide/commandlinetools/index.html
xcode-select --install

# brew - https://brew.sh/
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# iterm2 - https://iterm2.com/
brew install iterm2 --cask

# zsh - https://www.zsh.org/
brew install zsh

# oh-my-zsh - https://ohmyz.sh/
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# vscode - https://code.visualstudio.com/
brew install visual-studio-code --cask

# nerd font - https://www.nerdfonts.com/
brew tap homebrew/cask-fonts && brew install font-Fira-Code-nerd-font

# starship shell - https://starship.rs/
brew install starship

# fnm - https://github.com/Schniz/fnm
curl -fsSL https://fnm.vercel.app/install | bash

# watchman - https://facebook.github.io/watchman/
brew install watchman

# latest git - https://git-scm.com/
brew install git

# git configuration - https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
git config --global user.name "Your Name"
git config --global user.email "yourmail@gmail.com"

# rectangle - https://rectangleapp.com/
brew install --cask rectangle

# tldr - https://tldr.sh/
brew install tldr

# fzf - https://github.com/junegunn/fzf
brew install fzf
$(brew --prefix)/opt/fzf/install

# rg - https://github.com/BurntSushi/ripgrep
brew install ripgrep

# z - https://github.com/agkozak/zsh-z
git clone https://github.com/agkozak/zsh-z $ZSH_CUSTOM/plugins/zsh-z

# zsh-autosuggestions - https://github.com/zsh-users/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# meetingbar - https://github.com/leits/MeetingBar
brew install meetingbar

# bat - https://github.com/sharkdp/bat
brew install bat
alias cat="bat"

# git delta - https://github.com/dandavison/delta
brew install git-delta
git config --global core.pager "delta"
git config --global interactive.diffFilter "delta --color-only"
git config --global merge.conflitstyle "diff3"
git config --global diff.colorMoved "default"
git config --global delta.navigate true
git config --global delta.line-numbers true
git config --global delta.side-by-side true

# htop - https://htop.dev/
brew install htop

# tig - https://github.com/jonas/tig
brew install tig

# spotify - https://www.spotify.com/
brew install --cask spotify

# yarn - https://yarnpkg.com/
brew install yarn

# kap - https://getkap.co/
brew install --cask kap

# fx - https://github.com/antonmedv/fx
brew install fx

# exa - https://the.exa.website/
brew install exa
alias ls="exa"
```
