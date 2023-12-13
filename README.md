PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task
$ git init
Initialized empty Git repository in C:/Users/PAVAN SAI/Desktop/JFS/Task/.git/

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (master)
$ touch task.hyml

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (master)
$ touch task.html

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (master)
$ touch task.css

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (master)
$ touch task.js

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (master)
$ git add .

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (master)
$ git commit -m "first commit"
  git branch -M main
  git remote add origin https://github.com/pavansaipuranam/Task.git
  git push -u origin main
[master (root-commit) 31bdc10] first commit
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 task.css
 create mode 100644 task.html
 create mode 100644 task.js
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 363 bytes | 363.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/pavansaipuranam/Task.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git branch
* main

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git branch login

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git checkoutb login
git: 'checkoutb' is not a git command. See 'git --help'.

The most similar command is
        checkout

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git checkout login
Switched to branch 'login'

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ touch login.html

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ touch login.css

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ touch login.js

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ git init
Reinitialized existing Git repository in C:/Users/PAVAN SAI/Desktop/JFS/Task/.git/

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ git add .

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ git commit -m "create branch"
[login 82a180c] create branch
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 login.css
 create mode 100644 login.html
 create mode 100644 login.js

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$   git remote add origin https://github.com/pavansaipuranam/Task.git
error: remote origin already exists.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$   git push -u origin login
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 511 bytes | 511.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'login' on GitHub by visiting:
remote:      https://github.com/pavansaipuranam/Task/pull/new/login
remote:
To https://github.com/pavansaipuranam/Task.git
 * [new branch]      login -> login
branch 'login' set up to track 'origin/login'.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ git checkoutb login
git: 'checkoutb' is not a git command. See 'git --help'.

The most similar command is
        checkout

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ git checkout login
Already on 'login'
Your branch is up to date with 'origin/login'.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (login)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git branch
  login
* main

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git branch register

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git checkout register
Switched to branch 'register'

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$ touch register.html

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$ touch register.css

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$ touch register.js

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$ git add .

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$ ^C

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$ git commit -m "create branch 2"
[register 933939b] create branch 2
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 register.css
 create mode 100644 register.html
 create mode 100644 register.js

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$   git remote add origin https://github.com/pavansaipuranam/Task.git
error: remote origin already exists.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$   git push -u origin register
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 522 bytes | 522.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'register' on GitHub by visiting:
remote:      https://github.com/pavansaipuranam/Task/pull/new/register
remote:
To https://github.com/pavansaipuranam/Task.git
 * [new branch]      register -> register
branch 'register' set up to track 'origin/register'.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$ git branch
  login
  main
* register

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (register)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git merge login register
Fast-forwarding to: login
Trying simple merge with register
Merge made by the 'octopus' strategy.
 login.css     | 0
 login.html    | 0
 login.js      | 0
 register.css  | 0
 register.html | 0
 register.js   | 0
 6 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 login.css
 create mode 100644 login.html
 create mode 100644 login.js
 create mode 100644 register.css
 create mode 100644 register.html
 create mode 100644 register.js

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git commit -m "merging"
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$  git push -u origin register
Everything up-to-date
branch 'register' set up to track 'origin/register'.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$  git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 434 bytes | 434.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/pavansaipuranam/Task.git
   31bdc10..dfc1d4c  main -> main
branch 'main' set up to track 'origin/main'.

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git branch -d login
Deleted branch login (was 82a180c).

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git commit -m "login deleted"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$   git push origin --delete login
To https://github.com/pavansaipuranam/Task.git
 - [deleted]         login

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git branch -d register
Deleted branch register (was 933939b).

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$ git commit -m "register deleted"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$   git push origin --delete register
To https://github.com/pavansaipuranam/Task.git
 - [deleted]         register

PAVAN SAI@DESKTOP-6156JGC MINGW64 ~/Desktop/JFS/Task (main)
$
