# Python & ML Dev Setup

This is a repository to keep notes for future development environment setups on OSX specifically.

Much is adapted and taken from [this dev setup repository](https://github.com/donnemartin/dev-setup)

First, use the brew.sh, aws.sh, and pydata.sh scripts to install Homebrew, AWS tools, and python/pip tools. 

### Firefox Quantum
[Link](https://www.mozilla.org/en-US/firefox/)

Login with your credentials across machines to sync settings, personalization, bookmarks etc. 

### Install iTerm2
[iTerm2](https://www.iterm2.com/)

Go to profiles -> window -> style -> no title bar

##### Disable "find cursor" shortcut

Go to iTerm2 Preferences... --> Keys

Click on + under the grid

Press ⌘+/ with cursor in the Keyboard Shortcut field

Leave the Action field value set to Ignore


##### System-wide Hotkey

Preferences -> Keys -> Hotkey 

### Install Pycharm Professional Edition
[Pycharm Professional Edition](https://www.jetbrains.com/pycharm/)

### Install Docker for Mac
[Download](https://www.docker.com/docker-mac)

You can login to your dockerhub account to store docker images for future use.

### Customization/Misc
[speed up dock autohide](http://www.idownloadblog.com/2015/02/14/auto-hide-dock-no-delay-mac/)

terminal:
```
defaults write com.apple.dock autohide -bool true && defaults write com.apple.dock autohide-delay -float 0 && defaults write com.apple.dock autohide-time-modifier -float 0.4 && killall Dock
```
restore default:

```
defaults delete com.apple.dock autohide && defaults delete com.apple.dock autohide-delay && defaults delete com.apple.dock autohide-time-modifier && killall Dock
```
