# Vim Config

## Installation

```bash
# install vim via homebrew
brew install vim

# install nerd font and set it as a default font for iTerm2
brew tap homebrew/cask-fonts
brew install --cask font-hack-nerd-font

# say goodbye to your old .vim
mv ~/.vim ~/.vim.bak
mv ~/.vimrc ~/.vimrc.bak

git clone git://github.com/AlexeyKrasnoperov/vim_config.git ~/.vim
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

ln -s ~/.vim/vimrc ~/.vimrc

# install plugins
vim +PluginInstall +qall

```
