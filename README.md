# Practice101

Last login: Sun Dec 15 16:16:53 on ttys000
imac2021@iMaC2021s-MacBook-Pro ~ % cd Desktop
imac2021@iMaC2021s-MacBook-Pro Desktop % cd git_software
imac2021@iMaC2021s-MacBook-Pro git_software % git clone https://github.com/ZahraAhmadi2020/Practice101.git
Cloning into 'Practice101'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
imac2021@iMaC2021s-MacBook-Pro git_software % git config --global user.name "ZahraAhmadi2020"
imac2021@iMaC2021s-MacBook-Pro git_software % git config --global user.email "Ahmadi.work3094@gmail.com"
imac2021@iMaC2021s-MacBook-Pro git_software % git init
Initialized empty Git repository in /Users/imac2021/Desktop/git_software/.git/
imac2021@iMaC2021s-MacBook-Pro git_software % cd Practice101                                            
imac2021@iMaC2021s-MacBook-Pro Practice101 % echo РИМ-140970 Захра Ахмади > ЗахраАхмади.txt
imac2021@iMaC2021s-MacBook-Pro Practice101 % git add -A
imac2021@iMaC2021s-MacBook-Pro Practice101 % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   "\320\227\320\260\321\205\321\200\320\260\320\220\321\205\320\274\320\260\320\264\320\270.txt"

imac2021@iMaC2021s-MacBook-Pro Practice101 % git commit -m "Мой первый коммит"
[main b50bb52] Мой первый коммит
 1 file changed, 1 insertion(+)
 create mode 100644 "\320\227\320\260\321\205\321\200\320\260\320\220\321\205\320\274\320\260\320\264\320\270.txt"
imac2021@iMaC2021s-MacBook-Pro Practice101 % git status                       
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push
git: 'credential-winstore' is not a git command. See 'git --help'.
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 373 bytes | 373.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ZahraAhmadi2020/Practice101.git
   2acc8c7..b50bb52  main -> main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git log
commit b50bb521d7f65514ed7fe577174ad7bf0380c5b6 (HEAD -> main, origin/main, origin/HEAD)
Author: ZahraAhmadi2020 <Ahmadi.work3094@gmail.com>
Date:   Sun Dec 15 16:51:29 2024 +0500

    Мой первый коммит

commit 2acc8c792b77603e561ea6ed6b027cd8ea9c0988
Author: Zahra Ahmadi <119671680+ZahraAhmadi2020@users.noreply.github.com>
Date:   Sun Dec 15 16:43:36 2024 +0500

    Initial commit
imac2021@iMaC2021s-MacBook-Pro Practice101 % git show
commit b50bb521d7f65514ed7fe577174ad7bf0380c5b6 (HEAD -> main, origin/main, origin/HEAD)
Author: ZahraAhmadi2020 <Ahmadi.work3094@gmail.com>
Date:   Sun Dec 15 16:51:29 2024 +0500

    Мой первый коммит

diff --git "a/\320\227\320\260\321\205\321\200\320\260\320\220\321\205\320\274\320\260\320\264\320\270.txt" "b/\320\227\320\260\321\205\321\200\320\260\320\220\321\205\320\274\320\260\320\264\320\270.txt"
new file mode 100644
index 0000000..f1bb5d2
--- /dev/null
+++ "b/\320\227\320\260\321\205\321\200\320\260\320\220\321\205\320\274\320\260\320\264\320\270.txt"
@@ -0,0 +1 @@
+РИМ-140970 Захра Ахмади
imac2021@iMaC2021s-MacBook-Pro Practice101 % git commit --amend
hint: Waiting for your editor to close the file... git add readme.txt
^[[A^[[B^C
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch
* main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch TEST
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push
git: 'credential-winstore' is not a git command. See 'git --help'.
Everything up-to-date
imac2021@iMaC2021s-MacBook-Pro Practice101 % git status        
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch TEST
fatal: a branch named 'TEST' already exists
imac2021@iMaC2021s-MacBook-Pro Practice101 % git commit -m "Test"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch          
  TEST
* main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch          
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch
imac2021@iMaC2021s-MacBook-Pro Practice101 % git commit -m "Test"
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout TEST
Switched to branch 'TEST'
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push                                      
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch
* TEST
  main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch PRERELEASE
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout -b PRERELEASE
fatal: a branch named 'PRERELEASE' already exists
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout PRERELEASE   
Switched to branch 'PRERELEASE'
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch                
* PRERELEASE
  TEST
  main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push
git: 'credential-winstore' is not a git command. See 'git --help'.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'PRERELEASE' on GitHub by visiting:
remote:      https://github.com/ZahraAhmadi2020/Practice101/pull/new/PRERELEASE
remote: 
To https://github.com/ZahraAhmadi2020/Practice101.git
 * [new branch]      PRERELEASE -> PRERELEASE
branch 'PRERELEASE' set up to track 'origin/PRERELEASE'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch Test           
fatal: a branch named 'Test' already exists
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push       
git: 'credential-winstore' is not a git command. See 'git --help'.
Everything up-to-date
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout Test      
Switched to branch 'Test'
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push         
git: 'credential-winstore' is not a git command. See 'git --help'.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'Test' on GitHub by visiting:
remote:      https://github.com/ZahraAhmadi2020/Practice101/pull/new/Test
remote: 
To https://github.com/ZahraAhmadi2020/Practice101.git
 * [new branch]      Test -> Test
branch 'Test' set up to track 'origin/Test'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch
  PRERELEASE
  TEST
  main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch Test
fatal: a branch named 'Test' already exists
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch     
  PRERELEASE
  TEST
  main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch checkout Test
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch              
  PRERELEASE
  TEST
  checkout
  main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout TEST
Switched to branch 'TEST'
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch       
  PRERELEASE
* TEST
  checkout
  main
imac2021@iMaC2021s-MacBook-Pro Practice101 % git add test.txt
fatal: pathspec 'test.txt' did not match any files
imac2021@iMaC2021s-MacBook-Pro Practice101 % echo test.txt > test.txt
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push
git: 'credential-winstore' is not a git command. See 'git --help'.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'TEST' on GitHub by visiting:
remote:      https://github.com/ZahraAhmadi2020/Practice101/pull/new/TEST
remote: 
To https://github.com/ZahraAhmadi2020/Practice101.git
 * [new branch]      TEST -> TEST
branch 'TEST' set up to track 'origin/TEST'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout PRERELEASE 
Switched to branch 'PRERELEASE'
Your branch is up to date with 'origin/PRERELEASE'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % echo prerelease.txt > prerelease.txt
imac2021@iMaC2021s-MacBook-Pro Practice101 % git commit -m "prerelease.txt"
On branch PRERELEASE
Your branch is up to date with 'origin/PRERELEASE'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	prerelease.txt
	test.txt

nothing added to commit but untracked files present (use "git add" to track)
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push
git: 'credential-winstore' is not a git command. See 'git --help'.
Everything up-to-date
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git merge TEST
Already up to date.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git log --all --decorate --oneline
b50bb52 (HEAD -> main, origin/main, origin/Test, origin/PRERELEASE, origin/HEAD, checkout, TEST, PRERELEASE) Мой первый коммит
2acc8c7 Initial commit
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout PRERELEASE
Switched to branch 'PRERELEASE'
Your branch is up to date with 'origin/PRERELEASE'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git rebase main

Current branch PRERELEASE is up to date.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git log --all --decorate --oneline
b50bb52 (HEAD -> PRERELEASE, origin/main, origin/Test, origin/PRERELEASE, origin/HEAD, main, checkout, TEST) Мой первый коммит
2acc8c7 Initial commit
imac2021@iMaC2021s-MacBook-Pro Practice101 % git remote add origin https://github.com/ZahraAhmadi2020/Practice101.git
error: remote origin already exists.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push origin -u --all
git: 'credential-winstore' is not a git command. See 'git --help'.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'checkout' on GitHub by visiting:
remote:      https://github.com/ZahraAhmadi2020/Practice101/pull/new/checkout
remote: 
To https://github.com/ZahraAhmadi2020/Practice101.git
 * [new branch]      checkout -> checkout
branch 'PRERELEASE' set up to track 'origin/PRERELEASE'.
branch 'TEST' set up to track 'origin/TEST'.
branch 'main' set up to track 'origin/main'.
branch 'checkout' set up to track 'origin/checkout'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git@github.com:ZahraAhmadi2020/practice101.git
zsh: no such file or directory: git@github.com:ZahraAhmadi2020/practice101.git
imac2021@iMaC2021s-MacBook-Pro Practice101 % echo Тема: Программная инженерия > ЗахраАхмади.txt
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push
git: 'credential-winstore' is not a git command. See 'git --help'.
Everything up-to-date
imac2021@iMaC2021s-MacBook-Pro Practice101 % echo Тема: Программная инженерия > ЗахраАхмади.txt
imac2021@iMaC2021s-MacBook-Pro Practice101 % git add .
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push                                          
git: 'credential-winstore' is not a git command. See 'git --help'.
Everything up-to-date
imac2021@iMaC2021s-MacBook-Pro Practice101 % git add. 
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
	add
imac2021@iMaC2021s-MacBook-Pro Practice101 % git commit -m "Тема: Программная инженерия"
[PRERELEASE 549d3f9] Тема: Программная инженерия
 3 files changed, 3 insertions(+), 1 deletion(-)
 create mode 100644 prerelease.txt
 create mode 100644 test.txt
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push                                   
git: 'credential-winstore' is not a git command. See 'git --help'.
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 505 bytes | 505.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ZahraAhmadi2020/Practice101.git
   b50bb52..549d3f9  PRERELEASE -> PRERELEASE
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout main                                                       
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git branch PRERELEASE                                    
fatal: a branch named 'PRERELEASE' already exists
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout PRERELEASE                                       
Switched to branch 'PRERELEASE'
Your branch is up to date with 'origin/PRERELEASE'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % echo prerelease.txt > prerelease.txt                          
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout main                                                       
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % echo РИМ-140970 АхмадиЗахра Тема: Программная инженерия > АхмадиЗахра.txt
imac2021@iMaC2021s-MacBook-Pro Practice101 % echo prerelease.txt > prerelease.txtgit checkout PRERELEASE              
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout PRERELEASE
Switched to branch 'PRERELEASE'
Your branch is up to date with 'origin/PRERELEASE'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git checkout main                                                        
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push origin -u --all
git: 'credential-winstore' is not a git command. See 'git --help'.
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 505 bytes | 505.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ZahraAhmadi2020/Practice101.git
 * [new branch]      PRERELEASE -> PRERELEASE
 * [new branch]      checkout -> checkout
branch 'TEST' set up to track 'origin/TEST'.
branch 'main' set up to track 'origin/main'.
branch 'PRERELEASE' set up to track 'origin/PRERELEASE'.
branch 'checkout' set up to track 'origin/checkout'.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git remote add origin https://github.com/ProgramIngeneering2024/Practice101.git
error: remote origin already exists.
imac2021@iMaC2021s-MacBook-Pro Practice101 % git push origin -u --all
git: 'credential-winstore' is not a git command. See 'git --help'.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'checkout' on GitHub by visiting:
remote:      https://github.com/ZahraAhmadi2020/Practice101/pull/new/checkout
remote: 
To https://github.com/ZahraAhmadi2020/Practice101.git
 * [new branch]      checkout -> checkout
 ! [rejected]        main -> main (fetch first)
branch 'PRERELEASE' set up to track 'origin/PRERELEASE'.
branch 'TEST' set up to track 'origin/TEST'.
branch 'checkout' set up to track 'origin/checkout'.
error: failed to push some refs to 'https://github.com/ZahraAhmadi2020/Practice101.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
imac2021@iMaC2021s-MacBook-Pro Practice101 % 
