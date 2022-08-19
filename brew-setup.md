# -- BREW --

## install
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## iTerm2
brew install iterm2 --cask

## git
brew install git

## nvm/node
brew install nvm
mkdir ~/.nvm
vim ~/.bash_profile

//then add the below lines to ~/.bash_profile
export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh

//Press ESC + :wq to save and close your file.
source ~/.bash_profile

## flux
brew install flux --cask

## time-out
brew install time-out --cask

## spectacle
brew install spectacle --cask

## vscode
brew install visual-studio-code --cask

## source tree
brew install sourcetree --cask
