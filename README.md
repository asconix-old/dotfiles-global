# dotfiles

Dotfiles are a general approach how to customize a Unix, Linux or Mac OS X system. The dotfiles in this repository are my custom configurations for Vim, `zsh`, `tmux`, Git, `wget` etc.

## Vim

run ```git submodule init && git submodule update``` before starting vim

## Installation

First of all clone this repository in your Home-Directory:

    $~ git clone https://github.com/asconix/dotfiles .

... and symlink the configuration files for the services/applications you're running:

__Vim:__

    $~ ln -sf dotfiles/.vimrc ~
    $~ ln -sf dotfiles/.vim ~

__`zsh`:__

    $~ ln -sf dotfiles/.zshrc ~
    $~ ln -sf dotfiles/.zsh ~
    $~ ln -sf dotfiles/.zlogin ~

__`wget`:__

    $~ ln -sf dotfiles/.wgetrc ~

__Git:__

    $~ ln -sf dotfiles/.gitconfig ~

__Tmux:__

    $~ ln -sf dotfiles/.tmuxrc ~

 