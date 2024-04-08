g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git log
commit 860c6022c054282a7c38c13d8b9afb0e07e479aa (HEAD -> main, origin/main, origin/HEAD)
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Tue Mar 12 10:53:53 2024 +0530

    Update Exercise-1.md

commit c40889da777fd20e56f43a6001fe1f11d638f537
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Tue Mar 12 10:11:00 2024 +0530

    Update README.md

commit 33bf93e06ab341e6f7c1a40002a38993762cb195
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Tue Mar 12 10:08:56 2024 +0530

    Update README.md

commit a48aa1e705522915e6f3d15ec4d105c54b09d5b3
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Mon Mar 11 12:30:12 2024 +0530

    Update README.md

commit 84de2e7f443af7f59cecf3e4ba762da66a573ea0
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Mon Mar 11 11:54:30 2024 +0530

    Update Exercise-1.md

commit 97261470054f714f9fca480a785a903a5efa4d23
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Mon Mar 11 11:52:23 2024 +0530

    Update Exercise-1.md

commit c873f7a388cdd85cf1935cdffecbbb091cef61de
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Mon Mar 11 11:45:43 2024 +0530

    Update Exercise-1.md

commit f11816ac4259cbac201c332283592b5df934549d
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Mon Mar 11 11:43:53 2024 +0530

    Update README.md

commit 327831f6369e957afc50be4b4be90f00443242f3
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Mon Mar 11 11:41:21 2024 +0530
hi

    Create Exercise-1.md

commit 4693a07a9fe8c208b2c9a36d7efc1bf15454f647
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Mon Mar 11 09:47:38 2024 +0530

    Update Exercise-1.md


[1]+  Stopped                 git log
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ vi abc.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        abc.txt

nothing added to commit but untracked files present (use "git add" to track)
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ add abc.txt
-bash: add: command not found
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ ^C
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git add abc.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   abc.txt

g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git commit -m "hello"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
hi again
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'g1ms21cs144@cs-435936759985-oics-gxlx.(none)')
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   abc.txt

g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ vi abc.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   abc.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   abc.txt

g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git add abc.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git commit -m "hello again"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'g1ms21cs144@cs-435936759985-oics-gxlx.(none)')
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   abc.txt

g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git log
commit 860c6022c054282a7c38c13d8b9afb0e07e479aa (HEAD -> main, origin/main, origin/HEAD)
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Tue Mar 12 10:53:53 2024 +0530

    Update Exercise-1.md

commit c40889da777fd20e56f43a6001fe1f11d638f537
Author: ritcsecourses <86289052+ritcsecourses@users.noreply.github.com>
Date:   Tue Mar 12 10:11:00 2024 +0530

    Update README.md

:
[2]+  Stopped                 git log

