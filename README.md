## My Dotfiles

A collection of my basic dotfiles and scripts for setting up a new computer.

### Installation

```
$ git clone https://github.com/nguyenallen42/dotfiles.git
$ cd ~/dotfiles
$ chmod +x setup.sh
$ ./setup.sh
```

### setup.sh

This script does a few things
- backup current dotfiles into `/dotfiles_old`
- creates symlinks in the home directory to dotfiles in this repo
- helps setup zsh

### Sublime

The `/sublime` folder contains my preferences for Sublime 3. For now, they're manual
(e.g. copying in User Settings).
