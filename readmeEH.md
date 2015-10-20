## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - __Fill Me Out__

#### Repo Status
`$ git status` - __Fill Me Out__

`$ git diff` - Show changes between working directory and the index (commit folder)

#### Repo History
`$ git log` - Show log of the commit history

`$ git log --oneline --decorate --color --graph --all` - Show log of the commit history with each commit on a single line and print out ref name prefixes. Show colored diff and text based graphical representation.
`$ git log -p [filename]` __Fill Me Out__

#### Stage files to commit
`$ git add <filename>` - __Fill Me Out__


`$ git add -A` - Commit a snapshot of all changes in the working directory

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Record changes to the repository

#### Branching
`$ git branch <branch name>` - List, create, or delete branches

`$ git branch` - List, create, or delete branches

`$ git checkout <branch name>` -  Switch branches or restore working tree files

#### Merging

`$ git merge <branch name>` - Join two or more development histories together