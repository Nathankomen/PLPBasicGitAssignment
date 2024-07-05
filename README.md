# PLPBasicGitAssignment
Basic Git And GitHub Workflow 


Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ git init
Reinitialized existing Git repository in F:/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment/.git/

Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/Nathankomen/PLPBasicGitAssignment.git
error: remote origin already exists.

Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/Nathankomen/PLPBasicGitAssignment.git
error: remote origin already exists.

Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ echo "Hello, Git!" > hello.txt

Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ git add hello.txt
warning: in the working copy of 'hello.txt', LF will be replaced by CRLF the next time Git touches it

Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greeting"
[master 9c027ba] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Nathankomen/PLPBasicGitAssignment.git'

Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 550 bytes | 68.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Nathankomen/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/Nathankomen/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Admin@DESKTOP-NKK MINGW64 /f/NK/PLP COHORT MAY 2024/Software Development/Week 4/PLPBasicGitAssignment (master)
$ 

