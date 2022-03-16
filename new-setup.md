# Setup new laptop

## OH MY ZSH
### Install:
- sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

### Fix Potential problems
- sudo chown -R $(whoami) /usr/local/share/zsh /usr/local/share/zsh/site-functions

— 

## BREW
### Install 
- /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### Packages
- brew install --cask visual-studio-code
- brew install --cask rectangle
- brew install --cask docker
- brew install --cask react-native-debugger
- brew install --cask bitwarden
- brew install watchman
- brew install --cask postman

— 

## NVM
### Install
- curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

### Packages
- npm install --global yarn
