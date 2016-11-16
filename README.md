# vimrc

# Setup

## Powerline Install
`sudo pip install git+git://github.com/Lokaltog/powerline`

`wget https://github.com/Lokaltog/powerline/raw/develop/font/PowerlineSymbols.otf https://github.com/Lokaltog/powerline/raw/develop/font/10-powerline-symbols.conf`    
`sudo mv PowerlineSymbols.otf /usr/share/fonts/`    
`sudo fc-cache -vf`    
`sudo mv 10-powerline-symbols.conf /etc/fonts/conf.d/`    

## Tagbar install
`sudo apt-get install exuberant-ctags`

## Install Vundle
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

## NeoVim Plugin Support
`sudo pip install -U neovim`    
`sudo pip3 install -U neovim`

## Install Plugins
`vim`

`:BundleList`    
`:BundleInstall`
