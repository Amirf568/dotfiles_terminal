# My Dotfiles 

This directory contains the dotfiles for my system

## Requirements 

Ensure you have the following installed on your system 

### Git 

```
yay -S git
```

### Stow 

```
yay -S stow
```

## Installation

Git clone 

```
$ git clone --recursive https://github.com/Amirf568/dotfiles_arch.git
$ cd dotfiles
```

If the submodule (alacritty-theme repo) is not initialized, run:

```
git submodule update --init --recursive
```

then use GNU Stow for symlinks

```
$ Stow .
```
