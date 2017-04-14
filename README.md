# git-pfv
*Search through previous versions of a file in git*

`git pfv` lets you search through previous versions of a file from the
history of git.

## INSTALL
1. make a ~/bin directory if it doesn't already exist

  `mkdir ~/bin`
  
2. add ~/bin to your PATH in your .bashrc / .zshrc / ... if it's not
   already there

  `export PATH=~/bin:$PATH`
  
3. copy git-pfv to your ~/bin directory

  `cp git-pfv ~/bin`

## usage
`git pfv filename`

This command will open up less so you can page through the previous
versions.  They start out with most recent changes to oldest.
