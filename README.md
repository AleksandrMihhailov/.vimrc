[![](http://img.shields.io/badge/status-stable-brightgreen.svg)](https://twitter.com/jet4fire)
[![](http://img.shields.io/badge/aleksandr-approved-orange.svg)](https://twitter.com/jet4fire)

# Config Installation

    git clone http://github.com/jet4fire/vim.git ~/.vim
    cd ~/.vim
    ./install.sh

# Plugin Installation

    :PluginInstall

# For NeoVIM

    mkdir -p ${XDG_CONFIG_HOME:=$HOME/.config}
    ln -s ~/.vim $XDG_CONFIG_HOME/nvim
    ln -s ~/.vimrc $XDG_CONFIG_HOME/nvim/init.vim
