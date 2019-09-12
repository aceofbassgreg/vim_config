## Installing

```
$ cd ~/
$ git clone --recursive git@github.com:aceofbassgreg/vim_config.git
$ ln -sf $HOME/.vim/vimrc $HOME/.vimrc
$ cd $HOME/.vim
$ git submodule update --init
```

## Pathogen

[Pathogen](https://github.com/tpope/vim-pathogen) is used to install plugins and runtime files into their own private directiories. In many cases all that is required is to `git submodule add GIT_URL` a plugin into the `bundle/` directory. 

