# Login Page
*Author:- Aryan Pandey*
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git init
Initialized empty Git repository in C:/Users/91636/Desktop/gitDemo/Msrit Annual day Program/.git/
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        login.html
        signup.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git add .
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git commit -m "Initial Commit"
[master (root-commit) 177d770] Initial Commit
 3 files changed, 33 insertions(+)
 create mode 100644 index.html
 create mode 100644 login.html
 create mode 100644 signup.html
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git add .
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git commit -m "Added Readme.md"
[master 2ac9803] Added Readme.md
 1 file changed, 2 insertions(+)
 create mode 100644 README.md
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git branch
* master
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git branch -M main
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git branch        
* main
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git remote add origin https://github.com/4451uk/MSRIT-Annual-Day-Program.git
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git remote -V
error: unknown switch `V'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --[no-]verbose    be verbose; must be placed before a subcommand

PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git remote -v
origin  https://github.com/4451uk/MSRIT-Annual-Day-Program.git (fetch)
origin  https://github.com/4451uk/MSRIT-Annual-Day-Program.git (push)
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git push origin main
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (8/8), 766 bytes | 383.00 KiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/4451uk/MSRIT-Annual-Day-Program.git
 * [new branch]      main -> main
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   login.html
        modified:   signup.html

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git add .
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html
        modified:   login.html
        modified:   signup.html

PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git commit -m "Added logic for form"
[main c3e7fb0] Added logic for form
 3 files changed, 125 insertions(+), 11 deletions(-)
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> git push -u origin main 
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.48 KiB | 757.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/4451uk/MSRIT-Annual-Day-Program.git
   2ac9803..c3e7fb0  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\91636\Desktop\gitDemo\Msrit Annual day Program> 
