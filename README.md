# YodaPop Vim Configuration
### Steps to configure Vim

1. Create the ".vim" directory in the home directory, and create a "tmp"
 directory inside the ".vim" directory.
    1. Execute the following commands from inside a terminal:

            cd ~
            mkdir .vim
            cd .vim
            mkdir tmp
2. Clone the "yodapop-vimrc" repository.
    1. Execute the following command from inside a terminal:

            git clone https://github.com/YodaPop/yodapop-vimrc.git
3. Copy files and folders from the "yodapop-vimrc" folder to your ".vim" folder.
    1. Open a terminal, and change the current directory to "yodapop-vimrc".
    2. Execute the following commands from inside a terminal:

            cp -R colors ~/.vim
            cp -R docs ~/.vim
            cp -R ftdetect ~/.vim
            cp -R ftplugin ~/.vim
            cp -R indent ~/.vim
            cp -R syntax ~/.vim
4. Copy Vim's configuration files to your profile directory.
    1. Execute the following commands from inside a terminal:

            cp .vimrc ~/
            cp .gvimrc ~/
5. Install the vundle plugins.
    1. Open a terminal.
    2. Create a folder called "bundle" in the "~/.vim" directory.
    3. Clone the Vundle plugin into the "bundle" directory you just created.

            git clone https://github.com/gmarik/Vundle.vim.git
    4. Open Gvim or Vim.
    5. Run the following command.

            :PluginInstall

All plugins should now be installed.

## See Also
1. [Vundle Plugin Manager](https://github.com/gmarik/Vundle.vim)
