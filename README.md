# Global dotfiles

This repository contains my custom configuration files for services and software that I use (e.g. Vim, Z shell, Tmux, Git, wget etc.). Instead of typical dotfiles, that resist in your home directory, these configuration files are meant to be used as global configuration. One of the reasons to define them as global configuration files is the easy integration into my [Nix setups](https://github.com/asconix/nixos-config).

## Installation

First of all clone this repository in your Home-Directory:

```bash
$ cd /usr/local
$ git clone https://github.com/asconix/dotfiles-global
```

... and symlink the configuration files for the services/applications you're running as described below.

### Vim

```bash
$ ln -sf /usr/local/dotfiles/vim/vimrc /etc/vimrc
$ ln -sf /usr/local/dotfiles/vim/vim /etc/vim
```

Additionally ensure that submodules are cloned before launching Vim:

```bash
$ git submodule update --init
```

### Z shell (Zsh)

```bash
$ ln -sf /usr/local/dotfiles/zsh/zshrc /etc/zsh/zshrc
$ ln -sf /usr/local/dotfiles/zsh/lib /etc/zsh/lib
```

### Wget

```bash
$ ln -sf /usr/local/dotfiles/wget/wgetrc /usr/local/etc/wgetrc
```

### Git

```bash
$ ln -sf /usr/local/dotfiles/git/gitconfig /etc/gitconfig
```

### Tmux 2

```bash
$ ln -sf /usr/local/dotfiles/tmux/tmux.conf /etc/tmux.conf
```

## Authors

This collection of configuration files is managed by [Christoph Pilka](https://github.com/asconix).

## License

Source code in this repository is published under MIT License, see LICENSE file for full details.

