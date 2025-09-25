
Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ git clone https://github.com/amilasenakumara/simple.git
Cloning into 'simple'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ pwd
/c/Users/Administrator

Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ ls
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TM.blf
 NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{a2332f18-cdbf-11ec-8680-002248483d79}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/
 anaconda3/
 myNotebook.ipynb
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini
 simple/

Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ pwd
/c/Users/Administrator

Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ cd simple

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ ls
README.md

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ cd .

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ pwd
/c/Users/Administrator/simple

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ cd ..

Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ pwd
/c/Users/Administrator

Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ cd simple/

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ pwd
/c/Users/Administrator/simple

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ cd ,,
bash: cd: ,,: No such file or directory

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ cd..
bash: cd..: command not found

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ cd ..

Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ pwd
/c/Users/Administrator

Administrator@DESKTOP-IN8UO2V MINGW64 ~
$ cd simple

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ pwd
/c/Users/Administrator/simple

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ ls
README.md  demo.md

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        demo.md

nothing added to commit but untracked files present (use "git add" to track)

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git add .

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   demo.md


Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git commit -m "My first file"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Administrator@DESKTOP-IN8UO2V.(none)')

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git config --global user.email "amilasenakumara@gmail.com"

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git config -global user.name "amilasenakumara"
error: did you mean `--global` (with two dashes)?

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git config --global user.name "amilasenakumara"

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git commit - "My first file."
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'My first file.' did not match any file(s) known to git

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git commit -m "My first file."
[main 0e0efd8] My first file.
 1 file changed, 16 insertions(+)
 create mode 100644 demo.md

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$ git push origin
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 562 bytes | 562.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/amilasenakumara/simple.git
   0932e76..0e0efd8  main -> main

Administrator@DESKTOP-IN8UO2V MINGW64 ~/simple (main)
$


THis is going to be push and remove lets see what will happen
