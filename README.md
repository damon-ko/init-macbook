# Macbook Initialize

## Homebrew
---
### Installation
[LINK](https://brew.sh/index_ko)
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Programs
* Formulae
    * language : go, python3, pipenv
    * packaging : nvm, jenv
    * cli : gh
* Casks
    * browser : google-chrome, firefox, brave-browser
    * dev-tool : visual-studio-code, jetbrains-toolbox, iterm2, postman, fork, slack
    * language : adoptopenjdk8
    * utilities : itsycal, stats, hiddenbar, appcleaner, rectangle, cheatsheet

```
# cask
brew install --cask google-chrome firefox brave-browser visual-studio-code jetbrains-toolbox iterm2 postman fork slack adoptopenjdk8 itsycal stats hiddenbar appcleaner rectangle cheatsheet

# not cask
brew install go python3 pipenv nvm jenv gh
```

### To be continued
How to set oh-my-zsh.