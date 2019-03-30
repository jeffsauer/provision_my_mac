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
6. Install ansible
```
brew install ansible
```

to be continued...


