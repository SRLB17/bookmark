# bookmark
A bash script that allows one to bookmark and go to bookmarked directories

# How to use

1) First download the scripts either by clicking 'Code' > Download ZIP on the webpage or by running `git clone https://github.com/SRLB17/bookmark.git`
2) Next, move `bookmark`, `goto`, and `bookmark-config` to the same directory
3) If you moved the files to a directory already specified in the PATH variable, skip this step.<br/><br/>Either add the directory containing these files to the PATH variable by adding `export PATH="$PATH:/DIR"` where DIR is the directory to ~/.bashrc or add `alias bookmark="DIR/bookmark"` to ~/.bashrc
4) Add `alias goto=". DIR/goto` to ~/.bashrc or wherever is can be sourced whenever a shell is opened (This allows `goto` to be able to change the current shell's directory)
5) Edit `bookmark-config` so that $FILE is set to a regular text file that will be used to store bookmarks
6) Start bookmarking!

# Usage

## bookmark
