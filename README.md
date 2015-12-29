# vimrc

# Guide from:
http://unlogic.co.uk/2013/02/08/vim-as-a-python-ide/

# Powerline Install
`sudo pip install git+git://github.com/Lokaltog/powerline`

`wget https://github.com/Lokaltog/powerline/raw/develop/font/PowerlineSymbols.otf https://github.com/Lokaltog/powerline/raw/develop/font/10-powerline-symbols.conf`    
`sudo mv PowerlineSymbols.otf /usr/share/fonts/`    
`sudo fc-cache -vf`    
`sudo mv 10-powerline-symbols.conf /etc/fonts/conf.d/`    

# Tagbar install
`sudo apt-get install exuberant-ctags`

# Install Bundles
`vim`

:BundleList
:BundleInstall
