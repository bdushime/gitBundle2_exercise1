PS D:\The GYM git Exercises\BUNDLE 2> git branch ft/bundle-2
fatal: not a git repository (or any of the parent directories
PS D:\The GYM git Exercises\BUNDLE 2> git branch ft/bundle-2
fatal: not a valid object name: 'master'
PS D:\The GYM git Exercises\BUNDLE 2> git status

nothing to commit (create/copy files and use "git add" to tra
PS D:\The GYM git Exercises\BUNDLE 2> echo "Initial content" 
PS D:\The GYM git Exercises\BUNDLE 2> git add README.md
PS D:\The GYM git Exercises\BUNDLE 2> git commit -m "Initial 
[master (root-commit) 038458a] Initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
PS D:\The GYM git Exercises\BUNDLE 2> git commit -m "Changes 
On branch master
Untracked files:
        services.html

nothing added to commit but untracked files present (use "gitck)
PS D:\The GYM git Exercises\BUNDLE 2> git add .
PS D:\The GYM git Exercises\BUNDLE 2> git add .
PS D:\The GYM git Exercises\BUNDLE 2> git commit -m "Changes 
[master a31c6ef] Changes added
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 services.html
PS D:\The GYM git Exercises\BUNDLE 2> git pull
Please specify which branch you want to merge with.

h:

    git branch --set-upstream-to=<remote>/<branch> master
PS D:\The GYM git Exercises\BUNDLE 2> git checkout ft/bundle1
error: pathspec 'ft/bundle1' did not match any file(s) known 
PS D:\The GYM git Exercises\BUNDLE 2> git checkout ft/bundle-
Switched to branch 'ft/bundle-2'
PS D:\The GYM git Exercises\BUNDLE 2> echo "new page" > servi
PS D:\The GYM git Exercises\BUNDLE 2> git add .
PS D:\The GYM git Exercises\BUNDLE 2> git commit -m "Changes 
[ft/bundle-2 d60c312] Changes added
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 services.html
PS D:\The GYM git Exercises\BUNDLE 2> git pull 
There is no tracking information for the current branch.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you ch:

    git branch --set-upstream-to=<remote>/<branch> ft/bundle-

PS D:\The GYM git Exercises\BUNDLE 2> git remote add https://dushime/gitBundle2_exercise1.git
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated obje    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push trom

PS D:\The GYM git Exercises\BUNDLE 2> git remote add origin hPS D:\The GYM git Exercises\BUNDLE 2> git push -u origin mast
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Writing objects: 100% (6/6), 712 bytes | 178.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
git: 'branches' is not a git command. See 'git --help'.
PS D:\The GYM git Exercises\BUNDLE 2> git branch  
* ft/bundle-2
  master
* ft/bundle-2
  master
PS D:\The GYM git Exercises\BUNDLE 2> git checkout master    * ft/bundle-2
  master
PS D:\The GYM git Exercises\BUNDLE 2> git checkout master    Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS D:\The GYM git Exercises\BUNDLE 2> git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date
PS D:\The GYM git Exercises\BUNDLE 2> git branch
  ft/bundle-2
* master
PS D:\The GYM git Exercises\BUNDLE 2> git push -u origin maste
                                                
PS D:\The GYM git Exercises\BUNDLE 2> git push -u origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 499 bytes | 249.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/bdushime/gitBundle2_exercise1/pull/new/ft/bundle-2
remote:
To https://github.com/bdushime/gitBundle2_exercise1.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.