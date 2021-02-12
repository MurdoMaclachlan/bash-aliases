# Bash Aliases

This repository is a list of bash aliases I use on my system. To use these aliases, you must have bash as your default shell. Each folder contains a set of aliases specific to a certain category (miscellaneous, pip, slackpkg, etc.), as well as a `location` file that tells you where to put the aliases.

Most aliases are placed in `~/.bash_aliases`, however some commands (e.g. slackpkg) require root, and thus must be speficially placed in your *root user's* version of that file. If you plan on using root for generic purposes, you can simply include all the aliases in the root file, but I wouldn't recommend executing commands as root unless they require it.

If you have a `~/.bashrc` file with the following skeleton,
```
# Alias definitions.
# You may want to put all your additions into a separate file like
# ~/.bash_aliases, instead of adding them here directly.

if [ -f ~/.bash_aliases ]; then
    source ~/.bash_aliases
fi
```
these aliases should be automatically applied when you load a new console. Else, you can create the file (root aliases will require a version of the file in your root directory, as with `~/.bash_aliases`.
