# dotvim
sync dotvim

## [Synchronizing plugins with git submodules and pathogen](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/)

```bash
cd ~
git clone https://github.com/baylin87/dotvim.git ~/.vim
ln -s ~/.vim/vimrc ~/.vimrc
ln -s ~/.vim/gvimrc ~/.gvimrc
cd ~/.vim
git submodule init
git submodule update
```

## Included Plugins

- [vimrc](https://github.com/amix/vimrc)


