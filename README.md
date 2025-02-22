ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (master)
$ git branch lab_02_Akitha

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (master)
$ git checkout lab2_Akitha
error: pathspec 'lab2_Akitha' did not match any file(s) known to git

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (master)
$ git checkout lab_02_Akitha
Switched to branch 'lab_02_Akitha'

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (lab_02_Akitha)
$ git status
On branch lab_02_Akitha
nothing to commit, working tree clean

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (lab_02_Akitha)
$ git checkout -b test
Switched to a new branch 'test'

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (test)
$ git status
On branch test
nothing to commit, working tree clean

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (test)
$ git checkut lab_02_Akitha
git: 'checkut' is not a git command. See 'git --help'.

The most similar command is
        checkout

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (test)
$ git checkout lab_02_Akitha
Switched to branch 'lab_02_Akitha'

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (lab_02_Akitha)
$ git add .

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (lab_02_Akitha)
$ git commit -m "add new file"
On branch lab_02_Akitha
nothing to commit, working tree clean

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (lab_02_Akitha)
$ git push -u origin lab_02_Akitha
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'lab_02_Akitha' on GitHub by visiting:
remote:      https://github.com/Akitha-Kaween/Paf/pull/new/lab_02_Akitha
remote:
To https://github.com/Akitha-Kaween/Paf.git
 * [new branch]      lab_02_Akitha -> lab_02_Akitha
branch 'lab_02_Akitha' set up to track 'origin/lab_02_Akitha'.

ak@LAPTOP-A9V5FKV4 MINGW64 ~/Desktop/Sliit/Y3S2/PAF/Lab02/git/Paf (lab_02_Akitha)
$
