# nvm
install homebrew first : https://brew.sh/index_th
brew install nvm
nvm install 16
nvm install 14
nvm install 12
nvm uninstall 12
nvm ls
nvm use 16
node --version
nvm alias default 14


# Additinal
$ nvm ls-remote                 # lists all of the available versions of NodeJs & iojs
$ nvm ls                        # list locally installed version
$ nvm install 0.12.3            # install the version 0.12.3 (see ls-remote for available options)
$ nvm use 0.12.3                # switch to and use the installed 0.12.3 version
$ nvm which 0.12.2              # the path to the installed node version
$ nvm current                   # what is the current installed nvm version
$ nvm alias default 0.10.32     # set the default node to the installed 0.10.32 version
$ nvm --help                    # the help documents