# Cool Command Line
A cool command prompt/terminal experience using iTerm2 and a new Vim. iTerm2 is a modular and open-source version of Terminal that has a ton of features. In order to download iTerm 2, run the following depending on your shell:

Bash: curl -L https://iterm2.com/shell_integration/bash -o ~/.iterm2_shell_integration.bash

Zsh: curl -L https://iterm2.com/shell_integration/zsh -o ~/.iterm2_shell_integration.zsh

It is also available to be downloaded from the iTerm2 website at https://www.iterm2.com/downloads.html.

Currently, the files have only been able to work for the ZSH shell, but it may or may not work for other shells.
Copy and paste the zshrc.txt file's contents into your .zshrc file by running:

vim ~/.zshrc

You'll need to install Oh-My-ZSH, which can be installed from https://ohmyz.sh/ and several Github Repo's. You also may need to manually enter the contents of the z.sh file if it throws an error that says that the file couldn't be found in the ~/.vim directory. Simply call "vim z.sh" inside of the ~/.vim directory and copy the contents of the repo by ohmyzsh by running:

git clone https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/z/z.sh

You may also need to install Vundle because it is the package manager I am using. It can be cloned by running:

git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

To download the packages you want, run the following:

:PlugInstall (with the colon)

You can change the colors of iTerm2 by going to Preferences -> Profiles -> Colors -> Color Presets and changing it to some popular presets that are also available in VS Code such as Solarized. In order to change the Vim settings, you will need to call:

vim ~/.vimrc

Copy the contents of vimrc.txt into your .vimrc file.

