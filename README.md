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


### Part2 


```bash

### exercise1


PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git init 
Reinitialized existing Git repository in C:/Users/Malaika/cloned-hirwa-exercise/Git-exercise/.git/
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch--show-current
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch --show-current
main
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git checkout -b ft/new-featuree
Switched to a new branch 'ft/new-featuree'
PS 

##exercise2,3,4,5,6,7,8,9,10
###----------------------------


C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git add feature.txt
 create mode 100644 feature.txt
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git checkout main
M       README.md
Your branch is ahead of 'origin/main' by 7 commits.
  (use "git push" to publish your local commits)
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch --show-current
main
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> echo "wellcome back to page" >readme.txt
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git add readme.txt
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git commit -m "updated project readme"
[main f3ec160] updated project readme
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.txt
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git push -u origin ft/new-feature 
error: src refspec ft/new-feature does not match any
remote: Permission to HIRWA13/Git-exercise.git denied to GODisALL-FriendOfJesus.
fatal: unable to access 'https://github.com/HIRWA13/Git-exercise/': The requested URL returned error: 403
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git remote add "https://github.com/GODisALL-FriendOfJesus/cloned-hirwa-exercise.git"
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch -m ft/new-feature
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch
  ft/branch
error: the branch 'ft/new-featuree' is not fully merged
hint: If you are sure you want to delete it, run 'git branch -D ft/new-featuree'
hint: Disable this message with "git config set advice.forceDeleteBranch false"
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git push -u origin ft/new-featuree
info: please complete authentication in your browser...
remote: Permission to HIRWA13/Git-exercise.git denied to GODisALL-FriendOfJesus.
fatal: unable to access 'https://github.com/HIRWA13/Git-exercise/': The requested URL returned error: 403
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git push -u origin ft/new-featuree
info: please complete authentication in your browser...
remote: Permission to HIRWA13/Git-exercise.git denied to GODisALL-FriendOfJesus.
fatal: unable to access 'https://github.com/HIRWA13/Git-exercise/': The requested URL returned error: 403
info: please complete authentication in your browser...
remote: Permission to HIRWA13/Git-exercise.git denied to GODisALL-FriendOfJesus.
fatal: unable to access 'https://github.com/HIRWA13/Git-exercise/': The requested URL returned error: 403rcise.git
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git push -u origin ft/new-featuree
Enumerating objects: 79, done.
Delta compression using up to 4 threads
Compressing objects: 100% (38/38), done.
Writing objects: 100% (79/79), 20.75 KiB | 518.00 KiB/s, done.
Total 79 (delta 26), reused 57 (delta 18), pack-reused 0 (from 0)
To https://github.com/GODisALL-FriendOfJesus/cloned-hirwa-exercise.git
branch 'ft/new-featuree' set up to track 'origin/ft/new-featuree'.
warning: deleting branch 'ft/new-featuree' that has been merged to
         'refs/remotes/origin/ft/new-featuree', but not yet merged to HEAD
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch
  ft/branch
* ft/new-feature
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch -d ft/new-feature
error: cannot delete branch 'ft/new-feature' used by worktree at 'C:/Users/Malaika/cloned-hirwa-exercise/Git-exercise'
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git checkout -b ft/new-branch-from-commit HEAD~2
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.
Aborting
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git stash
Saved working directory and index state WIP on ft/new-feature: f3ec160 updated project readme
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git checkout -b ft/new-branch-from-commit HEAD~2
Switched to a new branch 'ft/new-branch-from-commit'
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git checkout main
Switched to a new branch 'main'
Updating e4744a0..3c29c44
 test2.md     | 0
 test3.md     | 0
 test4.md     | 0
 test5.md     | 1 +
 6 files changed, 2 insertions(+)
 create mode 100644 test2.md
 create mode 100644 test3.md
 create mode 100644 test4.md
 create mode 100644 test5.md
 create mode 100644 unwanted.txt
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git checkout ft/new-branch-from-commit
Switched to branch 'ft/new-branch-from-commit'
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git rebase main
Current branch ft/new-branch-from-commit is up to date.
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch -m ft/new-branch-from-commit ft/improved-branch-name
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git branch
  ft/branch
* ft/improved-branch-name
  ft/new-feature
  main
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git log --online
fatal: unrecognized argument: --online
PS C:\Users\Malaika\cloned-hirwa-exercise\Git-exercise> git log --oneline
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
d3ac84f unwanted commit
b544c40 created fourth file
f7c02de created third file
fe0d9a2 chore:create another file
0650585 chore:create initial file
e4744a0 (origin/main, origin/HEAD) Update README.md
3083f66 Update README
826eba3 Update README
86ec50c refactor: update README
be0f35c Update README.md
6483bd6 Update README.md
9dbca11 Update README.md
7cd7a29 Merge pull request #1 from HIRWA13/chore/refine-exercises
bf8e72c Update README.md
e632651 refactor: clean and update exercise structure
aabb257 refactor: create branch from a commit
4f71b9f refactor: update exercises
:
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
d3ac84f unwanted commit
b544c40 created fourth file
f7c02de created third file
fe0d9a2 chore:create another file
0650585 chore:create initial file
e4744a0 (origin/main, origin/HEAD) Update README.md
3083f66 Update README
826eba3 Update README
86ec50c refactor: update README
be0f35c Update README.md
6483bd6 Update README.md
9dbca11 Update README.md
7cd7a29 Merge pull request #1 from HIRWA13/chore/refine-exercises
bf8e72c Update README.md
e632651 refactor: clean and update exercise structure
aabb257 refactor: create branch from a commit
4f71b9f refactor: update exercises
:
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
d3ac84f unwanted commit
b544c40 created fourth file
f7c02de created third file
fe0d9a2 chore:create another file
0650585 chore:create initial file
e4744a0 (origin/main, origin/HEAD) Update README.md
3083f66 Update README
826eba3 Update README
86ec50c refactor: update README
be0f35c Update README.md
6483bd6 Update README.md
9dbca11 Update README.md
:
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
d3ac84f unwanted commit
b544c40 created fourth file
f7c02de created third file
fe0d9a2 chore:create another file
0650585 chore:create initial file
e4744a0 (origin/main, origin/HEAD) Update README.md
:
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
:
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
d3ac84f unwanted commit
b544c40 created fourth file
:
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
d3ac84f unwanted commit
b544c40 created fourth file
f7c02de created third file
fe0d9a2 chore:create another file
0650585 chore:create initial file
e4744a0 (origin/main, origin/HEAD) Update README.md
3083f66 Update README
826eba3 Update README
86ec50c refactor: update README
be0f35c Update README.md
6483bd6 Update README.md
9dbca11 Update README.md
7cd7a29 Merge pull request #1 from HIRWA13/chore/refine-exercises
:...skipping...
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
d3ac84f unwanted commit
b544c40 created fourth file
f7c02de created third file
fe0d9a2 chore:create another file
0650585 chore:create initial file
e4744a0 (origin/main, origin/HEAD) Update README.md
3083f66 Update README
826eba3 Update README
86ec50c refactor: update README
be0f35c Update README.md
6483bd6 Update README.md
9dbca11 Update README.md
7cd7a29 Merge pull request #1 from HIRWA13/chore/refine-exercises
bf8e72c Update README.md
e632651 refactor: clean and update exercise structure
aabb257 refactor: create branch from a commit
4f71b9f refactor: update exercises
6448eeb refactor: update readme file
013976b refactor: update exercises
23ea742 refactor: update and remove mistakes
:...skipping...
3c29c44 (HEAD -> ft/improved-branch-name, main) content of test5 uptodate
d3ac84f unwanted commit
b544c40 created fourth file
f7c02de created third file
fe0d9a2 chore:create another file
0650585 chore:create initial file
e4744a0 (origin/main, origin/HEAD) Update README.md
3083f66 Update README
826eba3 Update README
86ec50c refactor: update README
be0f35c Update README.md
6483bd6 Update README.md
9dbca11 Update README.md
7cd7a29 Merge pull request #1 from HIRWA13/chore/refine-exercises
bf8e72c Update README.md
e632651 refactor: clean and update exercise structure
aabb257 refactor: create branch from a commit
4f71b9f refactor: update exercises
6448eeb refactor: update readme file
013976b refactor: update exercises
23ea742 refactor: update and remove mistakes
248fb71 refactor: Update Exercises
6e0e33f refactor: Update README.md
```
### PART 3
```bash 

##exercise1
 Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git branch --show-current
main

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git add test3.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git stash
Saved working directory and index state WIP on main: 6694187 Secong part is done for challenges is updated but GODisALL

##exercise2

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git stash list
stash@{0}: WIP on main: 45b697b GODisALL part3 first exercise

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git stash pop stash@{0}
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{0} (c8e77f9ddee0d26a1277e2c3f600ab6952b775bb)

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git stash list

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ 
###exercise 3


Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git checkout -b feature/new
Switched to a new branch 'feature/new'

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git checkout main
M       README.md
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git add projectG.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git commit -m "Changes are created "
[main d9aa679] Changes are created
 1 file changed, 2 insertions(+)
 create mode 100644 projectG.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git checkout  feature/new
M       README.md
Switched to branch 'feature/new'


Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git add projectG.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git commit -m "Changes are created chnges G"
[feature/new 542eb93] Changes are created chnges G
 1 file changed, 2 insertions(+)
 create mode 100644 projectG.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git checkout main
M       README.md
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git merge feature/new
Auto-merging projectG.md
CONFLICT (add/add): Merge conflict in projectG.md
Automatic merge failed; fix conflicts and then commit the result.

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main|MERGING)
$ it add projectG.md
bash: it: command not found

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main|MERGING)
$ git add projectG.md

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main|MERGING)
$ git commit -m "conflict solved GODisALL"
[main 7535613] conflict solved GODisALL

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$

###exercise4
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)$ git mergetool

This message is displayed because 'merge.tool' is not configured.
See 'git mergetool --tool-help' or 'git help config' for more details.
'git mergetool' will now attempt to use one of the following tools:
opendiff kdiff3 tkdiff xxdiff meld tortoisemerge gvimdiff diffuse diffmerge ecmerge p4merge araxis bc codecompare smerge emerge vimdiff nvimdiffNo files need merging

### exercise 5

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git checkout  feature/new
M       README.md
Switched to branch 'feature/new'

##exercise 6
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ mkdir tmp

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ 

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ touch tmp/temporary.txt
##exercise 7

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git tag v1.0

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git tag
v1.0
###exercise 8
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git tag
v1.0

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git tag -d v1.0
Deleted tag 'v1.0' (was 542eb93)

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ git tag

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (feature/new)
$ 
## exercise 9
Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ git push
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (15/15), 1.45 KiB | 296.00 KiB/s, done.
Total 15 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), done.
To https://github.com/GODisALL-FriendOfJesus/Git-ex-part1.git
   6694187..7535613  main -> main

Malaika@DESKTOP-N7DTFKE MINGW64 ~/cloned-hirwa-exercise/Git-exercise-part1 (main)
$ 
```