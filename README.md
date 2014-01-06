# FreakyDazio - Sublime Text Setup

To install:

    $ brew tap phinze/cask
    $ brew install brew-cask
    $ brew cask install sublime-text
    $ brew install ctags
    $ git clone git@github.com:FreakyDazio/sublime-setup.git
    $ (cd sublime-setup && git submodule update)
    $ ~/Applications/Sublime\ Text\ 2.app # creates the support directories
    $ cp -r sublime-setup/packages/* ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
    $ cp sublime-setup/settings/* ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User
    $ sudo ln -fs ~/Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl
