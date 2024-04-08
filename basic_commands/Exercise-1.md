g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git branch
* main

g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git branch amala
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git branch
hi again
* main
create on branch amala
  amala
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git switch amala
A       abc.txt
Switched to branch 'amala'
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch amala
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   abc.txt

g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ vi abc.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ vi amala.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git add amala.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git commit -m "amala"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'g1ms21cs144@cs-435936759985-oics-gxlx.(none)')
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git log --oneline --graph
* 860c602 (HEAD -> amala, origin/main, origin/HEAD, main) Update Exercise-1.md
* c40889d Update README.md
* 33bf93e Update README.md
* a48aa1e Update README.md
* 84de2e7 Update Exercise-1.md
* 9726147 Update Exercise-1.md
* c873f7a Update Exercise-1.md
* f11816a Update README.md
* 327831f Create Exercise-1.md
* 4693a07 Update Exercise-1.md
* a27b770 Create Exercise-1.md
* 67f3948 Delete basic_commands/Exercise-1

[3]+  Stopped                 git log --oneline --graph
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git config --global user.email "amala678@yahoo.com"
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git config --global user.name "amala678"
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git log --oneline --graph
* 860c602 (HEAD -> amala, origin/main, origin/HEAD, main) Update Exercise-1.md
* c40889d Update README.md
* 33bf93e Update README.md
* a48aa1e Update README.md
* 84de2e7 Update Exercise-1.md
* 9726147 Update Exercise-1.md
* c873f7a Update Exercise-1.md
* f11816a Update README.md
* 327831f Create Exercise-1.md
* 4693a07 Update Exercise-1.md
* a27b770 Create Exercise-1.md
* 67f3948 Delete basic_commands/Exercise-1

[4]+  Stopped                 git log --oneline --graph
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch amala
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   abc.txt
        new file:   amala.txt

g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git log --oneline --graph
* 860c602 (HEAD -> tavishi, origin/main, origin/HEAD, main) Update Exercise-1.md
* c40889d Update README.md
* 33bf93e Update README.md
* a48aa1e Update README.md
* 84de2e7 Update Exercise-1.md
* 9726147 Update Exercise-1.md
* c873f7a Update Exercise-1.md
* f11816a Update README.md
* 327831f Create Exercise-1.md
* 4693a07 Update Exercise-1.md
* a27b770 Create Exercise-1.md
* 67f3948 Delete basic_commands/Exercise-1

[5]+  Stopped                 git log --oneline --graph
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git switch main
A       abc.txt
A       amala.txt
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git log --oneline --graph
* 860c602 (HEAD -> main, origin/main, origin/HEAD, tavishi) Update Exercise-1.md
* c40889d Update README.md
* 33bf93e Update README.md
* a48aa1e Update README.md
* 84de2e7 Update Exercise-1.md
* 9726147 Update Exercise-1.md
* c873f7a Update Exercise-1.md
* f11816a Update README.md
* 327831f Create Exercise-1.md
* 4693a07 Update Exercise-1.md
* a27b770 Create Exercise-1.md
* 67f3948 Delete basic_commands/Exercise-1
byeeee

[6]+  Stopped                 git log --oneline --graph
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   abc.txt
        new file:   amala.txt

g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ vi new.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git add new.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git commit -m "bye"
[main 2bd85cc] bye
 3 files changed, 3 insertions(+)
 create mode 100644 abc.txt
 create mode 100644 new.txt
 create mode 100644 amala.txt
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git log --oneline --graph --all
* 2bd85cc (HEAD -> main) bye
* 860c602 (origin/main, origin/HEAD, tavishi) Update Exercise-1.md
* c40889d Update README.md
* 33bf93e Update README.md
* a48aa1e Update README.md
* 84de2e7 Update Exercise-1.md
* 9726147 Update Exercise-1.md
* c873f7a Update Exercise-1.md
* f11816a Update README.md
* 327831f Create Exercise-1.md
* 4693a07 Update Exercise-1.md
* a27b770 Create Exercise-1.md

[7]+  Stopped                 git log --oneline --graph --all
g1ms21cs144@cloudshell:~/cloudshell_open/GitMasteryDrills$ git diff amala main
diff --git a/abc.txt b/abc.txt
new file mode 100644
index 0000000..edde936
--- /dev/null
+++ b/abc.txt
@@ -0,0 +1 @@
+hi again 
diff --git a/new.txt b/new.txt
new file mode 100644
index 0000000..bb24ee3
--- /dev/null
+++ b/new.txt

[8]+  Stopped                 git diff amala main

