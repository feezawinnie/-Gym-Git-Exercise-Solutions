##BUNDLE 1

##EXRECISE 1

```bash
HP@DESKTOP-2LSM5OO MINGW64 /
$ mkdir git-work
mkdir: cannot create directory ‘git-work’: Permission denied

HP@DESKTOP-2LSM5OO MINGW64 /
$ mk dir git-work
bash: mk: command not found

HP@DESKTOP-2LSM5OO MINGW64 /
$ mkdir git-work
mkdir: cannot create directory ‘git-work’: Permission denied

HP@DESKTOP-2LSM5OO MINGW64 /
$ mkdir git-work
mkdir: cannot create directory ‘git-work’: Permission denied

HP@DESKTOP-2LSM5OO MINGW64 /
$ ^C

HP@DESKTOP-2LSM5OO MINGW64 /
$ cd ~

HP@DESKTOP-2LSM5OO MINGW64 ~ (main)
$ ^C

HP@DESKTOP-2LSM5OO MINGW64 ~ (main)
$ mkdir git-work

HP@DESKTOP-2LSM5OO MINGW64 ~ (main)
$ cd git-work

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git init
Initialized empty Git repository in C:/Users/HP/git-work/.git/

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (master)
$ git branch -m master main

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git branch -m main master

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (master)
$ git add .

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (master)
$ git commit -m "initial commit"
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (master)
$ git branch -m master main

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git remote add origin https://github.com/feezawinnie/-Gym-Git-Exercise-Solutions.git

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git branch -M main

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/feezawinnie/-Gym-Git-Exercise-Solutions.git'

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ ^C

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ ^C

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git add .

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git commit -m "initial commit"
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ touch readme

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git add .

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git commit -m "initial commit"
[main (root-commit) fad4ca9] initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 206 bytes | 103.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/feezawinnie/-Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (main)
$ git checkout -b dev
Switched to a new branch 'dev'

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (dev)
$ git chechout -b test
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (dev)
$ git checkout -b test
Switched to a new branch 'test'

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (test)
$ git checkout branch
error: pathspec 'branch' did not match any file(s) known to git

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (test)
$ git checkout dev
Switched to branch 'dev'

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work (dev)
$ git checkout -d test
HEAD is now at fad4ca9 initial commit

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work ((fad4ca9...))
$ git branch dev
fatal: a branch named 'dev' already exists

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work ((fad4ca9...))
$ git branch -d test
Deleted branch test (was fad4ca9).

HP@DESKTOP-2LSM5OO MINGW64 ~/git-work ((fad4ca9...))
$


```

#EXERCISE 2

```bash

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ code .

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ stash save "home html"
bash: stash: command not found

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash save "home html"
You do not have the initial commit yet

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ ^C

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        home.html

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git add README.md

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git commit -m"readme added"
[master (root-commit) dba3b5e] readme added
 1 file changed, 175 insertions(+)
 create mode 100644 README.md

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git add .

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash save "home html adjusted"
Saved working directory and index state On master: home html adjusted

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ touch about.html

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git add .

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash save "about stashed"
Saved working directory and index state On master: about stashed

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ touch team.html

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git add .

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash save "team file for stash"
Saved working directory and index state On master: team file for stash

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash pop
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (dc4417aa1200ee7cc8614b07a9bba7972cb9e66d)

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash pop@{2}
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'pop@{2}'

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash pop@{1}
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'pop@{1}'

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ stash@{2}
bash: stash@{2}: command not found

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash list
stash@{0}: On master: about stashed
stash@{1}: On master: home html adjusted

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git stash pop stash@{1}
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html
        new file:   team.html

Dropped stash@{1} (d3112a87d34cad97038a2ac945bb4a6c35a890a0)

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git commit -m "stashed files"
[master 551e6ca] stashed files
 2 files changed, 22 insertions(+)
 create mode 100644 home.html
 create mode 100644 team.html

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git remote add https://github.com/feezawinnie/-Gym-Git-Exercise-Solutions.git
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git branch branch master main
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --[no-]verbose    show hash and subject, give twice for upstream branch
    -q, --[no-]quiet      suppress informational messages
    -t, --[no-]track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --[no-]set-upstream-to <upstream>
                          change the upstream info
    --[no-]unset-upstream unset the upstream info
    --[no-]color[=<when>] use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --[no-]abbrev[=<n>]   use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --[no-]delete     delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --[no-]move       move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    --[no-]omit-empty     do not output a newline after empty formatted refs
    -c, --[no-]copy       copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --[no-]list       list branch names
    --[no-]show-current   show current branch name
    --[no-]create-reflog  create the branch's reflog
    --[no-]edit-description
                          edit the description for the branch
    -f, --[no-]force      force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --[no-]column[=<style>]
                          list branches in columns
    --[no-]sort <key>     field name to sort on
    --[no-]points-at <object>
                          print only branches of the object
    -i, --[no-]ignore-case
                          sorting and filtering are case insensitive
    --[no-]recurse-submodules
                          recurse through submodules
    --[no-]format <format>
                          format to use for the output


HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (master)
$ git branch -M master main

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git remote add origin https://github.com/feezawinnie/-Gym-Git-Exercise-Solutions.git

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git push --set-upstream origin main
To https://github.com/feezawinnie/-Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/feezawinnie/-Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
















remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 186 bytes | 4.00 KiB/s, done.
From https://github.com/feezawinnie/-Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Merge made by the 'ort' strategy.
 readme | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git status
On branch main
nothing to commit, working tree clean

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git stash list
stash@{0}: On master: about stashed

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git stash pop stash@{0}
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{0} (3d07b7e0370438b6181765786a2fcaf017015eb5)

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git stash pop stash@{1}
error: stash@{1} is not a valid reference

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git reset --hard HEAD
HEAD is now at ba08575 Please enter a commit message to explain why this merge is necessary,

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ Merge local and GitHub changes
bash: Merge: command not found

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$ git commit -m 'Merge local and GitHub changes'
On branch main
nothing to commit, working tree clean

HP@DESKTOP-2LSM5OO MINGW64 ~/OneDrive/Feezaz work/thegym/git-exercise/git-work (main)
$

```
