# Vim 8 package for Javascript development 

A minimal set of packages to start developing javascript using vim.

* Linter **eslint** [syntastic](https://github.com/scrooloose/syntastic)
* Autocomplete **ternjs** [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
* Git diff tool [vim-gitgutter](https://github.com/airblade/vim-gitgutter)


## Installation

```shell
# install vim8-jspack
mkdir -p  ~/.vim/pack
git clone --recursive --depth 1 git@github.com:stan-kondrat/vim8-jspack.git ~/.vim/pack/jspack

# configure ternjs autocomplete 
cd ~/.vim/pack/jspack/start/YouCompleteMe
./install.py --tern-completer
```

## License

The vim8-jspack is open-sourced software licensed under the [MIT](https://github.com/stan-kondrat/vim8-jspack/blob/master/LICENSE).
