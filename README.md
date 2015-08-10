# Dotfiles

## Requirements

1. Download [iTerm2](https://www.iterm2.com)
1. Download zsh: `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
1. Download iterm theme: `git clone git@github.com:venetucci/base16-shell.git ~/.config/base16-shell`

## Install

Clone onto your laptop:

    git clone git://github.com/jtescher/dotfiles.git ~/.dotfiles

Install [rcm](https://github.com/thoughtbot/rcm):

    brew tap thoughtbot/formulae
    brew install rcm

Install the dotfiles:

    env RCRC=$HOME/.dotfiles/rcrc rcup

You can safely run `rcup` multiple times to update:

    rcup
