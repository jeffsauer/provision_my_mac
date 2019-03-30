# provision_my_mac

These are the steps used to provision a new Mac.

1. Install macOS.
2. Install latest combo updater from Apple Support page.
3. Install from Mac App Store Xcode
4. Install Xcode command line utilities
```
xcode-select --install
```
5. Install homebrew 
  ```
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  brew update
  brew doctor
  ```
6. Install some apps that might require a password during installation
```
brew cask install little-snitch
brew install ansible
brew cask install osxfuse
brew cask install enpass
brew cask install virtualbox
brew cask install virtualbox-extension-pack
```
7. Install commonly used apps as casks
```
brew cask install google-chrome
brew cask install visual-studio-code

brew cask install iterm2
brew cask install balenaetcher
brew cask install the-unarchiver
brew cask install dropbox
brew cask install libreoffice
brew cask install nomachine
brew cask install caffeine
brew cask install gitkraken
brew cask install tigervnc-viewer
brew cask install quicken
```


to be continued...


