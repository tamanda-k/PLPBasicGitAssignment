mkdir PLPBasicGitAssignment

HP@DESKTOP-TAMANDA-MW MINGW64 ~
$ cd PLPBasicGitAssignment

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment
$ git init
Initialized empty Git repository in C:/Users/HP/PLPBasicGitAssignment/.git/

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/tamanda-k/PLPBasicGitAssignment.git

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ touch hello.txt

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ ls
hello.txt

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ vi hello.txt

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ git add hello.txt

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ git commit -m  "Add hello.txt with a greeting"
[master (root-commit) 9e6fc66] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/tamanda-k/PLPBasicGitAssignment.git'

HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


HP@DESKTOP-TAMANDA-MW MINGW64 ~/PLPBasicGitAssignment (master)
$ git push --set-upstream origin master
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 238 bytes | 238.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/tamanda-k/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/tamanda-k/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.


