> my dotfiles and setup scripts.

Tested fully on 

* OS X 10.9.4 

and partially on 

* Ubuntu 14.04.1

First Time Install
==================

```bash
bash -c "$(curl -fsSL raw.github.com/mvhenderson/dotfiles/master/bin/dotfiles)"
```

### Alfred

* Answer prompts
* Change hotkey to -Space
* Add powerpack license
* Setup config sync
* `brew cask alfred link`

### Dash

* Make sure Dash starts at login
* Setup user to hide window on login
* Alfred integration workflow

### Sublime Text 3

* Install the package manager <https://sublime.wbond.net/installation>
* Copy the following config files (which contain API keys)
    - Evernote.sublime-settings
    - GitHub.sublime-settings

### Day-O

* Start it up, make sure it is set to launch at login

### Preferences

* Run `osx` from the terminal
* Open Sublime Text, ignore the errors while package manager installs modules

### iTerm

* Load Solorized colors into default profile
* Setup hotkey window to use ⌥-Space
* Change the selection color to base2 (alt light background)

### Encrypted Cloud

Create an encrypted directory for sync to a cloud service like Dropbox. This 
will encrypt files before uploading. See the links in `./bin/private-cloud` for
more detail.

* Create directory `~/Private`
* Add `encfs` to keychain
    - Open Keychain Access.app
    - Add item named `encfs` with account `encfs`
    - Add password for encrypted folder
* `login-add ~/.dotfiles/login/dropbox-private.app true`

### Misc

* May have to remove Bluetooth and Clock menu items manually
* Setup the dock
* Wait for spotlight to finish reindex
* Restart


Credits
=======

* Ben Alman <https://github.com/cowboy/dotfiles>
* Cătălin Mariș <https://github.com/alrra/dotfiles>
* Gianni Chiappetta <https://github.com/gf3/dotfiles>
* Jan Moesen <https://github.com/janmoesen/tilde>
* Lars Kappert <https://github.com/webpro/dotfiles>
* Mathias Bynens <https://github.com/mathiasbynens/dotfiles>
* Nicolas Gallagher <https://github.com/necolas/dotfiles>
* Ryan Tomayko <https://github.com/rtomayko/dotfiles>
* Wynn Netherland <https://github.com/pengwynn/dotfiles>
