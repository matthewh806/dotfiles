# Matthew's dotfiles

## Introduction

A simple, personal dotfiles repository for OSX

[This](https://dotfiles.github.io) is an excellent overview and introduction to the benefits of putting dotfiles under source control. 

[This](https://github.com/mathiasbynens/dotfiles) is a great repository for an OSX dotfiles setup. 

## Installation

I'd highly recommend viewing, understanding and then creating your own personalised dotfiles repository. 

However, if you'd like to use my setup, follow these simple steps:

Clone the repository into your filesystem (e.g. `~/.dotfiles`) and run the bootsrap.sh script. This script pulls the latest version and rsync's the files to your home folder `~`. 

```bash
git clone https://github.com/matthewh806/dotfiles.git && cd dotfiles && source bootstrap.sh
```

To update your local `dotfiles` repository:

```bash
cd ~/.dotfiles
source bootstrap.sh
```
