# learn_git

Microsoft Windows [Version 10.0.19045.5131]
(c) Microsoft Corporation. All rights reserved.

C:\Users\micji>cd desktop

C:\Users\micji\Desktop>mkdir learn_git

C:\Users\micji\Desktop>cd learn_git

C:\Users\micji\Desktop\learn_git>type nul>third.txt

C:\Users\micji\Desktop\learn_git>git init
Initialized empty Git repository in C:/Users/micji/Desktop/learn_git/.git/

C:\Users\micji\Desktop\learn_git>git add third.txt

C:\Users\micji\Desktop\learn_git>it commit -m "adding third.txt"
'it' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\micji\Desktop\learn_git>git log
fatal: your current branch 'main' does not have any commits yet

C:\Users\micji\Desktop\learn_git>git commit -m "adding third.txt"
[main (root-commit) cb1cb46] adding third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

C:\Users\micji\Desktop\learn_git>type nul>fourth.txt

C:\Users\micji\Desktop\learn_git>git rm third.txt
rm 'third.txt'

C:\Users\micji\Desktop\learn_git>git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

C:\Users\micji\Desktop\learn_git>git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"

C:\Users\micji\Desktop\learn_git>git add .

C:\Users\micji\Desktop\learn_git>git commit -m "removing third.txt"
[main ab9acf1] removing third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename third.txt => fourth.txt (100%)

C:\Users\micji\Desktop\learn_git>git log
commit ab9acf1fb9849ca857a3981d11c2990eb954dec9 (HEAD -> main)
Author: Michael Adetayo <micjik50@gmail.com>
Date:   Thu Nov 14 14:59:42 2024 +0100

    removing third.txt

commit cb1cb465ec02f1858a3ee9541ec222e1b610aee0
Author: Michael Adetayo <micjik50@gmail.com>
Date:   Thu Nov 14 14:53:55 2024 +0100

    adding third.txt

C:\Users\micji\Desktop\learn_git>git config global core.pager=cat -
error: key does not contain a section: global

C:\Users\micji\Desktop\learn_git>git config core.pager=cat -
error: invalid key: core.pager=cat

C:\Users\micji\Desktop\learn_git>git config --global core.pager

C:\Users\micji\Desktop\learn_git>git config --global core.pager "cat"

C:\Users\micji\Desktop\learn_git>git help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\Users\micji\Desktop\learn_git>
