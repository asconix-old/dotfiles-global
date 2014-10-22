# dotfiles

Dotfiles are a general approach how to customize a Unix, Linux or Mac OS X system. The dotfiles in this repository are my custom configurations for Vim, zsh, Tmux, Git, wget etc.

## Installation

First of all clone this repository in your Home-Directory:

    $~ cd ~
    $~ git clone https://github.com/asconix/dotfiles
    $~ mv dotfiles .dotfiles

... and symlink the configuration files for the services/applications you're running:

__Vim:__

    $~ ln -sf .dotfiles/.vimrc
    $~ ln -sf .dotfiles/.vim

Additionally run `git submodule init && git submodule update` before starting Vim.

__zsh:__

    $~ ln -sf .dotfiles/.zshrc
    $~ ln -sf .dotfiles/.zsh
    $~ ln -sf .dotfiles/.zlogin

__wget:__

    $~ ln -sf .dotfiles/.wgetrc

__Git:__

    $~ ln -sf .dotfiles/.gitconfig

__Tmux:__

    $~ ln -sf .dotfiles/.tmuxrc
