ez@Kurtt MINGW64 ~/Documents/Git
$ git config --global user.name "Kurt Ivan Miciano"

ez@Kurtt MINGW64 ~/Documents/Git
$ git config --global user.email "micianokurtivan_bsit@plmun.edu.ph"

ez@Kurtt MINGW64 ~/Documents/Git
$ ssh-keygen -t rsa -b 4096 -C "micianokurtivan_bsit@plmun.edu.ph"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/ez/.ssh/id_rsa):
/c/Users/ez/.ssh/id_rsa already exists.
Overwrite (y/n)? n

ez@Kurtt MINGW64 ~/Documents/Git
$ clip < ~/.ssh/id_rsa.pub

ez@Kurtt MINGW64 ~/Documents/Git
$ ssh -T git@github.com
Hi KurtIvanMiciano2J! You've successfully authenticated, but GitHub does not provide shell access.

ez@Kurtt MINGW64 ~/Documents/Git
$ git clone https://github.com/PLMUN-CITCS/advdbms-s02-e01-KurtM.git
Cloning into 'advdbms-s02-e01-KurtM'...
info: please complete authentication in your browser...
remote: Repository not found.
fatal: repository 'https://github.com/PLMUN-CITCS/advdbms-s02-e01-KurtM.git/' not found

ez@Kurtt MINGW64 ~/Documents/Git
$ git clone https://github.com/PLMUN-CITCS/advdbms-s02-e01-KurtM.git
Cloning into 'advdbms-s02-e01-KurtM'...
remote: Repository not found.
fatal: repository 'https://github.com/PLMUN-CITCS/advdbms-s02-e01-KurtM.git/' not found

ez@Kurtt MINGW64 ~/Documents/Git
$  git clone https://github.com/PLMUN-CITCS/advdbms-s02-e01-KurtIvan.git
Cloning into 'advdbms-s02-e01-KurtIvan'...
remote: Repository not found.
fatal: repository 'https://github.com/PLMUN-CITCS/advdbms-s02-e01-KurtIvan.git/' not found

ez@Kurtt MINGW64 ~/Documents/Git
$ https://github.com/KurtIvanMiciano2J/KurtM.git
bash: https://github.com/KurtIvanMiciano2J/KurtM.git: No such file or directory

ez@Kurtt MINGW64 ~/Documents/Git
$ git clone https://github.com/PLMUN-CITCS/advdbms-s02-e01-https://github.com/KurtIvanMiciano2J/KurtM.git
fatal: destination path 'KurtM' already exists and is not an empty directory.

ez@Kurtt MINGW64 ~/Documents/Git
$ git https://github.com/KurtIvanMiciano2J/KurtM.git
git: 'https://github.com/KurtIvanMiciano2J/KurtM.git' is not a git command. See 'git --help'.

ez@Kurtt MINGW64 ~/Documents/Git
$ git clone https://github.com/KurtIvanMiciano2J/KurtM.git
fatal: destination path 'KurtM' already exists and is not an empty directory.

ez@Kurtt MINGW64 ~/Documents/Git
$  git clone https://github.com/KurtIvanMiciano2J/KurtM.git
fatal: destination path 'KurtM' already exists and is not an empty directory.

ez@Kurtt MINGW64 ~/Documents/Git
$ git clone https://github.com/PLMUN-CITCS/advdbms-s02-e01-KurtIvanMiciano2J.git
Cloning into 'advdbms-s02-e01-KurtIvanMiciano2J'...
remote: Repository not found.
fatal: repository 'https://github.com/PLMUN-CITCS/advdbms-s02-e01-KurtIvanMiciano2J.git/' not found

ez@Kurtt MINGW64 ~/Documents/Git
$ git clone https://github.com/PLMUN-CITCS/advdbms-s01-e01-KurtIvanMiciano2J.git
Cloning into 'advdbms-s01-e01-KurtIvanMiciano2J'...
remote: Enumerating objects: 17, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (13/13), done.
remote: Total 17 (delta 1), reused 4 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (17/17), 7.00 KiB | 651.00 KiB/s, done.
Resolving deltas: 100% (1/1), done.

ez@Kurtt MINGW64 ~/Documents/Git
$ cd advdbms-s01-e01-KurtIvanMiciano2J

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.java

nothing added to commit but untracked files present (use "git add" to track)

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.java

nothing added to commit but untracked files present (use "git add" to track)

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.java

nothing added to commit but untracked files present (use "git add" to track)

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.java

nothing added to commit but untracked files present (use "git add" to track)

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        KurtM/

nothing added to commit but untracked files present (use "git add" to track)

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.java

nothing added to commit but untracked files present (use "git add" to track)

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.java

nothing added to commit but untracked files present (use "git add" to track)

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git add\HelloWorld.Java
git: 'addHelloWorld.Java' is not a git command. See 'git --help'.

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git HelloWorld.java status
git: 'HelloWorld.java' is not a git command. See 'git --help'.

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git add . HelloWorld.java
fatal: pathspec 'HelloWorld.java' did not match any files

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git add . HelloWorld.java

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git commit -m "My first java program"
[main 5317f5a] My first java program
 1 file changed, 5 insertions(+)
 create mode 100644 HelloWorld.java

ez@Kurtt MINGW64 ~/Documents/Git/advdbms-s01-e01-KurtIvanMiciano2J (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 398 bytes | 199.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/PLMUN-CITCS/advdbms-s01-e01-KurtIvanMiciano2J.git
   deba7c6..5317f5a  main -> main
