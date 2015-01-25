# vim
vim settings

## setup

1. clone this repository into your ~/.vim directory
2. git submodule init && git submodule update
3. mv ~/.vimrc ~/.vimrc.backup
4. create the following shim and save it as ~/.vimrc:

```vim
source ~/.vim/vimrc
```

startup vim and neobundle will detect and ask you install any missing plugins. you can also manually initiate this with :NeoBundleInstall
