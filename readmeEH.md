## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Show changes between working directory and the index (commit folder)

#### Repo History
`$ git log` - Show log of the commit history

`$ git log --oneline --decorate --color --graph --all` - Show log of the commit history with each commit on a single line and print out ref name prefixes. Show colored diff and text based graphical representation.

$ git log -p [filename] - Shows commit logs and generates patches of filename

Stage files to commit

$ git add <filename> - Adds file contents to the index


`$ git add -A` - Commit a snapshot of all changes in the working directory

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Record changes to the repository

#### Branching
`$ git branch <branch name>` - List, create, or delete branches

`$ git branch` - List, create, or delete branches

`$ git checkout <branch name>` -  Switch branches or restore working tree files

#### Merging

`$ git merge <branch name>` - Join two or more development histories together

Git Aliases
Before we finish this chapter on basic Git, there’s just one little tip that can make your Git experience simpler, easier, and more familiar: aliases. We won’t refer to them or assume you’ve used them later in the book, but you should probably know how to use them.

Git doesn’t automatically infer your command if you type it in partially. If you don’t want to type the entire text of each of the Git commands, you can easily set up an alias for each command using git config. Here are a couple of examples you may want to set up:

$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
This means that, for example, instead of typing git commit, you just need to type git ci. As you go on using Git, you’ll probably use other commands frequently as well; don’t hesitate to create new aliases.