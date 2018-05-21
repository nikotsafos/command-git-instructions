# Navigation Terminal
**cd** -> Change directory
- cd ~ -> change directory to Home
**ls** -> display what is in current directory with short list
**l** -> displau complete file information in directory
**pwd** -> print working directory. the where am i command
**open** -> command will open a file in default program or directory in finder

# File Manipulation
**man** -> will pull up manual for commands - q to exit
-`man [command here]` -- will display tons of information about the command
**|** -> pipe will execute command on left first then execute command on right
-`[comamnd here] | [second command here]` - does not work for every command
**>** -> redirects output to a file
-`echo 'text to add' > [file name]` - output directed into file !!!Will overwrite whats in there.
-`echo 'text to add' >> [file name]` - output appended into file
**mkdir** -> create new directory from current position
**touch** -> create new file from current directory
**mv** -> move files
-`mv [current file name] [new file name]` -- will rename the file
-`mv [current file name] ./newdirectory/[new file name]` -- will move the file and rename, directory must exist. period in directory indicates current directory
**rm** -> removes files or directories -- !!! scary cannot undo
-`rm [file name]` -- removes file from system
-`rm -r [directory name]` -- removes directory and all subsequent files
**grep** -> will search through document for strings
-`cat [file name] | grep 'string to search'` -- will search contents of file and return if grep string found
-`-n` -- will display line number of found string
-`-A [number here]` -- will display trailing number of lines specified
-`-B [number here]` -- will display preceding number of lines specified
**cat** -> reads a file(s) and outputs to terminal
-`cat [file name]` - will display file contents
-`cat [file name] [file name] ....` will display file contents of all files selected in order

# Git commands
**git init** -> this will add a local git repository to a directory
**git status** -> this will show files that are untracked or tracked for next commit
**git add** -> will add files to staging for next commit
-`git add [file name]` - will add individual file to staging
-`git add -A` - will add all files to staging
-`git add .` - will add all files to staging
**git commit** -> takes staged files and creates save point / commit number
-`git commit -m 'enter in MEANINGFUL commit message'`
**git log** -> shows full log of all commits to branch master
**git checkout** -> creates a new branch
-`git checkout -b [branch name]` - creates a new branch and switches to that branch
-`git checkout [branch name]` - switches to that branch
