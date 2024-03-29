Sublime Text 3 User Package
===========================

This is my user-specific configuration for Sublime Text 3. Most of the configuration is around additions to Vintage to make it more Vim-like.


Features
--------

1. `:s` invokes Replace panel
1. `Y` yanks to end of line, rather than the whole line. This annoyed me in Vim as well.
1. `:bd` closes current buffer
1. `:wq` saves current file and closes buffer
1. `:e` edits a file
1. `ZZ` saves and closes current file as a normal-mode command
1. `gd` invokes Goto Definition on the word under the cursor
1. *alt-up* and *alt-down* navigate build results instead of *F4*/*shift-F4*

Installation
------------

1. Install Sublime Text.
1. Install [Package Control](https://packagecontrol.io/installation).
1. Make a symlink from projects directory to Sublime Text user package for easy access.
    ```
    $ cd ~
    $ ln -s ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/ Sublime\ Text
    ```
1. Clone this repo into that directory.
    ```
    $ cd Sublime\ Text
    $ git clone https://github.com/BryceLohr/Sublimetext3User.git .
    ```
1. Create a link to the OS-specific settings so Sublime can find them.
    ```
    $ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
    $ ln -s User/OS OS
    ```
1. Restart Sublime.
