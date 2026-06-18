### CHALLENGES   OF GIT
### PART1
```bash
##exercise 1:
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise-part1> git inits/Malaika/cloned-hirwa-exercise/Git-exercise-part1/.git/
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise-part1> git add test1.md
PS C:\Users\Malaika\cloned-hirwa-exercise\Ge is created but GODisALL"
[master (root-commit) 55a30f1] first file i
 1 file changed, 1 insertion(+)
 create mode 100644 test1.md
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise-part1> git add test2.md
PS C:\Users\Malaika\cloned-hirwa-exercise\Gle is created but GODisALL" GODisALL
 1 file changed, 1 insertion(+)
 create mode 100644 test2.md
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise-part1> git add test3.md
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise-part1> git commit -m "third file is created but GODisALL"
[master 4335d4d] third file is created but GODisALL
 1 file changed, 1 insertion(+)
 create mode 100644 test3.mdit-exercise-part1> git add test4.md
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise-part1> git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   test4.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise-part1> git log
commit 4335d4d4adff6a6bf596e9a98d5f6bdf33586223 (HEAD -> master)
Author: GODisALL-FriendOfJesus <malaikajiradukunda@gmail.com>
Date:   Thu Jun 18 13:17:27 2026 +0200

    third file is created but GODisALL

commit ea3a0e54fbd31ee4681d11b5486abd9f2bb812df
Author: GODisALL-FriendOfJesus <malaikajiradukunda@gmail.com>
Date:   Thu Jun 18 13:16:27 2026 +0200

    second file is created but GODisALL
xercise/Git-exercise-part1 (master)
$ git commit --amend -m  "fourth file is created but GODisALL"
[master 6a48cd5] fourth file is created but GODisALL
 Date: Thu Jun 18 13:17:27 2026 +0200
 2 files changed, 2 insertions(+)
 create mode 100644 test3.md
 create mode 100644 test4.md


##exercise 2:
rwa-exercise/Git-exercise-part1 (master)
$ git add test4.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git commit --amend "fourth file is created but GODisALL"
error: pathspec 'fourth file is created but GODisALL' did not match any file(s) known to git
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git commit --amend -m  "fourth file is created but GODisALL"
[master 6a48cd5] fourth file is created but GODisALL
 Date: Thu Jun 18 13:17:27 2026 +0200
 2 files changed, 2 insertions(+)
 create mode 100644 test3.md
 create mode 100644 test4.md
 Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git rebase -i HEAD~2
hint: Waiting for your editor to close the file.
Successfully rebased and updated refs/heads/master.
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git rebase -i HEAD~2
hint: Waiting for your editor to close the file.
Successfully rebased and updated refs/heads/master.
##exercise 3:
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git rebase -i HEAD~2
hint: Waiting for your editor to close the file.
hint: Waiting for your editor to close the file.
[detached HEAD 02223e8] second file is created but GODisALL files are squeshed and GODisALL
 Date: Thu Jun 18 13:16:27 2026 +0200
 1 file changed, 1 insertion(+)
 create mode 100644 test2.md
hint: Waiting for your editor to close the file.
[detached HEAD 298c45a] second file is created but GODisALL files are squeshed and GODisALL
 Date: Thu Jun 18 13:16:27 2026 +0200
 3 files changed, 3 insertions(+)
 create mode 100644 test2.md
 create mode 100644 test3.md
 create mode 100644 test4.md
Successfully rebased and updated refs/heads/master.
###exercise 4,5,6,7,8,9
$ git rebase -i head~2
hint: Waiting for your editor to close the file.
hint: Waiting for your editor to close the file.
[detached HEAD 5618668] third file updated but GODisALL updated third and fourth files but
 Date: Thu Jun 18 15:18:07 2026 +0200
 2 files changed, 2 insertions(+)
 create mode 100644 test3.md
 create mode 100644 test4.md
Successfully rebased and updated refs/heads/master.



Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git add unwanted.txt

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git commit -m "Wanted commit to but GODisALL"
[master 1fd202f] Wanted commit to but GODisALL
 1 file changed, 1 insertion(+)
 create mode 100644 unwanted.txt

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git rebase -i HEAD~2
hint: Waiting for your editor to close the file.
Successfully rebased and updated refs/heads/master.


Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git rebase -i head~3
fatal: invalid upstream 'head~3'

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git rebase -i HEAD~3
fatal: invalid upstream 'HEAD~3'

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git rebase -i head~2
fatal: invalid upstream 'head~2'

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git  log --oneline
5618668 (HEAD -> master) third file updated but GODisALL updated third and fourth files but
55a30f1 first file is created but GODisALL

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git rebase -i --root
hint: Waiting for your editor to close the file.
Successfully rebased and updated refs/heads/master.

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git checkout -b ft/branch
Switched to a new branch 'ft/branch'

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (ft/branch)

xercise/Git-exercise-part1 (ft/branch)
$ git add test5.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (ft/branch)
$ git commit -m "file five already prepared and but GODisALL"
[ft/branch 277588f] file five already prepared and but GODisALL
 1 file changed, 1 insertion(+)
 create mode 100644 test5.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (ft/branch)
$ git log -1 --oneline
277588f (HEAD -> ft/branch) file five already prepared and but GODisALL

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (ft/branch)
$ git checkout main

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (ft/branch)
$ git checkout master
Switched to branch 'master'

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git cherry-pick 277588f
[master 998dfd4] file five already prepared and but GODisALL
 Date: Thu Jun 18 15:38:20 2026 +0200
 1 file changed, 1 insertion(+)
 create mode 100644 test5.md

 ###exercise10

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ git log --graph --oneline --all
* 998dfd4 (HEAD -> master) file five already prepared and but GODisALL
| * 277588f (ft/branch) file five already prepared and but GODisALL
|/  
* ba85ff8 first file is created but GODisALL
* 6c62283 third file updated but GODisALL updated third and fourth files but

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (master)
$ 


```