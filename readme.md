st login: Mon Apr  2 23:07:45 on ttys000
Access-2:~ Jason$ cd desktop
Access-2:desktop Jason$ cd gittest
Access-2:gittest Jason$ vi aboutMe.txt
Access-2:gittest Jason$ git commit -m "updated aboutMe"
On branch master

Initial commit

Untracked files:
	.swp
	aboutMe.txt
	index.html
	styles.css

nothing added to commit but untracked files present
Access-2:gittest Jason$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.swp
	aboutMe.txt
	index.html
	styles.css

nothing added to commit but untracked files present (use "git add" to track)
Access-2:gittest Jason$ git add aboutMe.txt
Access-2:gittest Jason$ git commit -m "updated aboutMe"
[master (root-commit) ad2d350] updated aboutMe
 1 file changed, 2 insertions(+)
 create mode 100644 aboutMe.txt
Access-2:gittest Jason$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.swp
	index.html
	styles.css

nothing added to commit but untracked files present (use "git add" to track)
Access-2:gittest Jason$ vi aboutMe.txt
Access-2:gittest Jason$ git add .
Access-2:gittest Jason$ git commit -m "added favorite movie to aboutMe"
[master dc48244] added favorite movie to aboutMe
 4 files changed, 1 insertion(+)
 create mode 100644 .swp
 create mode 100644 index.html
 create mode 100644 styles.css
Access-2:gittest Jason$ git log
commit dc482448ebc646c88a4ca8a89566a78bc0c2d5b7 (HEAD -> master)
Author: Jason Oh <jasonoh35@gmail.com>
Date:   Mon Apr 2 23:17:03 2018 -0500

    added favorite movie to aboutMe

commit ad2d3502862928d7a4dab01491429e4eb1f0d72d
Author: Jason Oh <jasonoh35@gmail.com>
Date:   Mon Apr 2 23:15:00 2018 -0500

    updated aboutMe
Access-2:gittest Jason$ git revert dc482448ebc646c88a4ca8a89566a78bc0c2d5b7
[master 20d1112] Revert "added favorite movie to aboutMe"
 4 files changed, 1 deletion(-)
 delete mode 100644 .swp
 delete mode 100644 index.html
 delete mode 100644 styles.css
Access-2:gittest Jason$ vi aboutMe.txt
Access-2:gittest Jason$ commit -m "added favorite book"
-bash: commit: command not found
Access-2:gittest Jason$ git commit -m "added favorite book"
On branch master
Changes not staged for commit:
	modified:   aboutMe.txt

no changes added to commit
Access-2:gittest Jason$ git add .
Access-2:gittest Jason$ git commit -m "added favorite book"
[master 32a580a] added favorite book
 1 file changed, 1 insertion(+)
Access-2:gittest Jason$ git log
commit 32a580af2f8958985687a0bfacde6cdd77384cbe (HEAD -> master)
Author: Jason Oh <jasonoh35@gmail.com>
Date:   Mon Apr 2 23:21:11 2018 -0500

    added favorite book

commit 20d1112bb6a646992c798957ef3dc191ad4d784e
Author: Jason Oh <jasonoh35@gmail.com>
Date:   Mon Apr 2 23:18:47 2018 -0500

    Revert "added favorite movie to aboutMe"
    
    This reverts commit dc482448ebc646c88a4ca8a89566a78bc0c2d5b7.

commit dc482448ebc646c88a4ca8a89566a78bc0c2d5b7
Author: Jason Oh <jasonoh35@gmail.com>
Date:   Mon Apr 2 23:17:03 2018 -0500

    added favorite movie to aboutMe

commit ad2d3502862928d7a4dab01491429e4eb1f0d72d
Author: Jason Oh <jasonoh35@gmail.com>
Date:   Mon Apr 2 23:15:00 2018 -0500

    updated aboutMe
Access-2:gittest Jason$ 
Access-2:gittest Jason$ cd ..
Access-2:desktop Jason$ touch about.txt
Access-2:desktop Jason$ 
Access-2:desktop Jason$ clear

Access-2:desktop Jason$ ls
Bed.png
DojoAssignments
IMG_9042.JPG
Screen Shot 2018-04-02 at 9.41.23 PM.png
Selling
Simple Comic.app
Visual Studio Code.app
Wedding Speech.docx
about.txt
btak.jpg
gittest
new_project
test
wutang wallpaper.jpg
~$AM 3 STUDY GUIDE.docx
~$AS notes.docx
~$Chpt_18_Brown_Pt_2_SP2016.pptx
~$apter 18 (1).docx
Access-2:desktop Jason$ mkdir GitHubRepoAssignment
Access-2:desktop Jason$ cd GitHubRepoAssignment
Access-2:GitHubRepoAssignment Jason$ git init
Initialized empty Git repository in /Users/Jason/Desktop/GitHubRepoAssignment/.git/
Access-2:GitHubRepoAssignment Jason$ touch readme.md
Access-2:GitHubRepoAssignment Jason$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	readme.md

nothing added to commit but untracked files present (use "git add" to track)
Access-2:GitHubRepoAssignment Jason$ git add .
Access-2:GitHubRepoAssignment Jason$ git commit -m "Adding readme.md file"
[master (root-commit) ce75226] Adding readme.md file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md
Access-2:GitHubRepoAssignment Jason$ git status
On branch master
nothing to commit, working tree clean
Access-2:GitHubRepoAssignment Jason$ git remote add origin https://github.com/jasonoh35/GitHubRepoAssignment.git
Access-2:GitHubRepoAssignment Jason$ git push -u origin master
Username for 'https://github.com': jasonoh35
Password for 'https://jasonoh35@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 219 bytes | 219.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/jasonoh35/GitHubRepoAssignment.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
Access-2:GitHubRepoAssignment Jason$ vi readme.md
Access-2:GitHubRepoAssignment Jason$ 

