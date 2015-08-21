#Dot Files

+ Bash
+ vim
+ Terminator

These dotfiles were extended from [Swarrop CH dotbash](https://github.com/swaroopch/dotbash).

##Features:

+ Bash aliases for daily usage commands with bash, git, django, vagrant and service management like postgres, mysql, nginx.
+ Print help for bash aliases.
+ Vim themes and some basic plugins using Bundle.
+ A colorful bash prompt with info about git branch and virtualenv. From [this gist](https://gist.github.com/insin/1425703)

##Usage:

+ Clone this repo in home directory
+ Add a symbolic link to `./vim/vimrc` at `.vimrc`
+ Vimrc will install vim wakatime plugin. If you are not using it then it from .vim/vimrc file.
+ Vimrc also try to get `Source Code Pro` font. Download it and install it in your system.
+ Bash paths file assumes you are using `virtualenvwrapper`. Remove it if you are not.
+ OSx branch also assumes you have `bash-completion` installed via brew. If not remove from `.profile`

##Note:

The master branch is suitable for bash in Ubuntu/Debian based systems. If you are working on OSx then checkout the osx branch.

##License
See LICENSE.txt file in the repo
