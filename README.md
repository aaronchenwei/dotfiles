# dotfiles

Aaron's default configuration for Linux development environments

## How to use

```sh
# go back to HOME directory
$ cd ~

# clone dotfile repo to local 
$ git clone https://github.com/aaronchenwei/dotfiles.git .dotfiles

# backup the original local dotfile
$ mv .vimrc .vimrc.local

# create Symlink to dotfiles
$ ln -s ~/.dotfiles/.vimrc  ~/.vimrc

# merge back if there is any local configuration
```
