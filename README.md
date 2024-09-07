# My dotfiles

This directory contains the dotfiles for my system (copied from all over the internet)

## Requirements

Ensure you have the following installed on your system

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/shamblonaut/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```

## Credits

- These dotfiles are mostly copied from [PROxZIMA's](https://github.com/PROxZIMA/.dotfiles)
- [Using GNU Stow for managing Dotfiles - Dreams of Autonomy](https://www.youtube.com/watch?v=y6XCebnB9gs)
