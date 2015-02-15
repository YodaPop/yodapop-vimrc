# YodaPop Vim Configuration
### Steps to configure Vim

1\. Create a folder named ".vim" in you user profile

2\. Clone the yodapop-vimrc repository

    a\. Open a terminal

    b\. Execute the following command

```
git clone https://github.com/YodaPop/yodapop-vimrc.git
```

3\. Copy files and folders from the "yodapop-vimrc" folder to your ".vim" folder

    a\. Open a terminal
    b\. Execute the following commands from inside the "yodapop-vimrc" directory

```
cp -R colors ~/.vim
cp -R docs ~/.vim
cp -R ftdetect ~/.vim
cp -R ftplugin ~/.vim
cp -R indent ~/.vim
cp -R syntax ~/.vim
```

4\. Copy Vim's configuration files to your profile directory

    a\. Open a terminal

    b\. Execute the following commands from inside the "yodapop-vimrc" directory

```
cp .vimrc ~/
cp .gvimrc ~/
```

5\. Install vundle plugins

    a\. Open a terminal

    b\. Create a folder called "bundle" in the "~/.vim" directory

    c\. Clone the Vundle plugin into the "bundle" directory you just created

```
git clone https://github.com/gmarik/Vundle.vim.git
```

    e\. Open Gvim or Vim
    f\. Run the following command in Vim

```
:PluginInstall
```

All plugins should now be installed.

## See Also
1. [Vundle Plugin Manager](https://github.com/gmarik/Vundle.vim)
