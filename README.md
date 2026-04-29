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

```
