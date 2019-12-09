# Grad-Project
Graduate Project for MOLB 5485
# Documentation of code leading up to GitHub Repository creation
# Finding where I am
[inbre025@tlog2 ~]$ pwd
/home/inbre025
[inbre025@tlog2 ~]$ ls
[inbre025@tlog2 ~]$ ls -l
total 0
[inbre025@tlog2 ~]$ cd /project
[inbre025@tlog2 project]$ cd inbre-train/inbre025
[inbre025@tlog2 inbre025]$ ls -l
total 0
drwxrwsr-x 4 nblouin  inbre-train 4096 Oct 29 11:22 LearnLinux
drwxrwsr-x 2 vchhatre inbre-train 4096 Dec  2 10:04 project
[inbre025@tlog2 inbre025]$ cd project/
[inbre025@tlog2 project]$ ls -l
total 7027712
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
# First attempt at GitHub Repository creation
[inbre025@tlog2 project]$ git --version
git version 1.8.3.1
[inbre025@tlog2 project]$ mkdir Grad-Project
[inbre025@tlog2 project]$ cd Grad-Project/
[inbre025@tlog2 Grad-Project]$ pwd
/project/inbre-train/inbre025/project/Grad-Project
[inbre025@tlog2 Grad-Project]$ git status
fatal: Not a git repository (or any parent up to mount point /pfs/tsfs1)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
[inbre025@tlog2 Grad-Project]$ git init
Initialized empty Git repository in /pfs/tsfs1/project/inbre-train/inbre025/project/Grad-Project/.git/
[inbre025@tlog2 Grad-Project]$ ls -l
total 0
[inbre025@tlog2 Grad-Project]$ ls -lha
total 0
drwxrwsr-x 3 inbre025 inbre-train 4.0K Dec  9 15:33 .
drwxrwsr-x 3 vchhatre inbre-train 4.0K Dec  9 15:33 ..
drwxrwsr-x 7 inbre025 inbre-train 4.0K Dec  9 15:33 .git
[inbre025@tlog2 Grad-Project]$ touch Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ vim Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ [inbre025@tlog2 Grad-Project]$ vim Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ ls -lh
total 0
-rw-rw-r-- 1 inbre025 inbre-train 133 Dec  9 15:37 Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git status
# On branch master
#
# Initial commit
#
# Untracked files:
#   (use "git add <file>..." to include in what will be committed)
#
#       Project_Writeup.md
nothing added to commit but untracked files present (use "git add" to track)
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?
#Second attempt at creating github repository
[inbre025@tlog2 Grad-Project]$ pwd
/project/inbre-train/inbre025/project/Grad-Project
[inbre025@tlog2 Grad-Project]$ git init
Reinitialized existing Git repository in /pfs/tsfs1/project/inbre-train/inbre025/project/Grad-Project/.git/
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git commit -m "first commit"
[master (root-commit) 4bfc083] first commit
 Committer: INBRE Training Account <inbre025@tlog2.cluster>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 7 insertions(+)
 create mode 100644 Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git remote add origin https://github.com/ghummel91/Grad-Project.git
[inbre025@tlog2 Grad-Project]$ git push -u origin master

(gnome-ssh-askpass:55209): Gtk-WARNING **: 15:40:59.576: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Username for 'https://github.com': git push origin master

(gnome-ssh-askpass:55252): Gtk-WARNING **: 15:41:11.717: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Password for 'https://git push origin master@github.com':
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/ghummel91/Grad-Project.git/'
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git commit -m "first commit"
# On branch master
nothing to commit, working directory clean
[inbre025@tlog2 Grad-Project]$ git init
Reinitialized existing Git repository in /pfs/tsfs1/project/inbre-train/inbre025/project/Grad-Project/.git/
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git commit -m "first commit"
# On branch master
nothing to commit, working directory clean
# Third attempt at making GitHub Repository
[inbre025@tlog2 Grad-Project]$ rm Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ ls -l
total 0
[inbre025@tlog2 Grad-Project]$ touch Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ vim Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git commit -m "first commit"
[master 8d2ab09] first commit
 Committer: INBRE Training Account <inbre025@tlog2.cluster>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 2 insertions(+), 2 deletions(-)
[inbre025@tlog2 Grad-Project]$ git commit --amend --reset-author

[1]+  Stopped                 git commit --amend --reset-author
[inbre025@tlog2 Grad-Project]$ git remote add origin https://github.com/ghummel91/Grad-Project.git
fatal: remote origin already exists.
[inbre025@tlog2 Grad-Project]$ clear
[inbre025@tlog2 Grad-Project]$ git init
Reinitialized existing Git repository in /pfs/tsfs1/project/inbre-train/inbre025/project/Grad-Project/.git/
[inbre025@tlog2 Grad-Project]$ ls -l
total 0
-rw-rw-r-- 1 inbre025 inbre-train 105 Dec  9 15:44 Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git commit -m "first commit"
# On branch master
nothing to commit, working directory clean
[inbre025@tlog2 Grad-Project]$ git init
Reinitialized existing Git repository in /pfs/tsfs1/project/inbre-train/inbre025/project/Grad-Project/.git/
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git commit -m "first commit"
# On branch master
nothing to commit, working directory clean
[inbre025@tlog2 Grad-Project]$ git remote add origin https://github.com/ghummel91/Grad-Project.git
fatal: remote origin already exists.
[inbre025@tlog2 Grad-Project]$ git push -u origin master

(gnome-ssh-askpass:1795): Gtk-WARNING **: 15:52:35.564: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Username for 'https://github.com': git init

(gnome-ssh-askpass:2305): Gtk-WARNING **: 15:54:25.066: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Password for 'https://git init@github.com':
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/ghummel91/Grad-Project.git/'
[inbre025@tlog2 Grad-Project]$ inbre025
-bash: inbre025: command not found
#Attempt to save history so I could ask for help
[inbre025@tlog2 Grad-Project]$ history > History/problems_github.sh
-bash: History/problems_github.sh: No such file or directory
[inbre025@tlog2 Grad-Project]$ pwd
/project/inbre-train/inbre025/project/Grad-Project
[inbre025@tlog2 Grad-Project]$ cd ..
[inbre025@tlog2 project]$ pwd
/project/inbre-train/inbre025/project
[inbre025@tlog2 project]$ ls -l
total 7027712
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec  9 15:44 Grad-Project
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
[inbre025@tlog2 project]$ rm Grad
rm: cannot remove ‘Grad’: No such file or directory
[inbre025@tlog2 project]$ rm Grad-Project/
rm: cannot remove ‘Grad-Project/’: Is a directory
[inbre025@tlog2 project]$ rm -r Grad-Project/
rm: remove write-protected regular file ‘Grad-Project/.git/objects/4b/fc083ab5bba056ed7afae31f43a84e63cfd4fe’? y
rm: remove write-protected regular file ‘Grad-Project/.git/objects/1b/8c0792429bf3f7d1f21d349e4c33360f719574’? y
rm: remove write-protected regular file ‘Grad-Project/.git/objects/5f/c7eeef45c835ebf65e0ef40e5d80b71e1b0e06’? y
rm: remove write-protected regular file ‘Grad-Project/.git/objects/09/61f6e98b9fca7d6b6c28fc9e6fb2b334261d16’? y
rm: remove write-protected regular file ‘Grad-Project/.git/objects/99/7fa331e5bc194418afae1578349391431d5cd9’? y
rm: remove write-protected regular file ‘Grad-Project/.git/objects/8d/2ab09d39fd6c0edd52236cf0d4d43aa55c2122’? y
[inbre025@tlog2 project]$ ls -l
total 7027712
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
[inbre025@tlog2 project]$ mkdir History
[inbre025@tlog2 project]$ ls -l
total 7027712
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 15:57 History
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
# Fixing the mistakes I made trying to make Git Repository
[inbre025@tlog2 project]$ mkdir Grad-Project
[inbre025@tlog2 project]$ cd Grad-Project/
[inbre025@tlog2 Grad-Project]$ pwd
/project/inbre-train/inbre025/project/Grad-Project
# Trying again
[inbre025@tlog2 Grad-Project]$ git status
fatal: Not a git repository (or any parent up to mount point /pfs/tsfs1)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
[inbre025@tlog2 Grad-Project]$ touch Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ vim Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ [inbre025@tlog2 Grad-Project]$ git status
fatal: Not a git repository (or any parent up to mount point /pfs/tsfs1)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
[inbre025@tlog2 Grad-Project]$ git init
Initialized empty Git repository in /pfs/tsfs1/project/inbre-train/inbre025/project/Grad-Project/.git/
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git commit -m "first commit"
[master (root-commit) 3f831f9] first commit
 Committer: INBRE Training Account <inbre025@tlog2.cluster>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 7 insertions(+)
 create mode 100644 Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git remote add origin https://github.com/ghummel91/Grad-Project.git
[inbre025@tlog2 Grad-Project]$ git push -u origin master

(gnome-ssh-askpass:4717): Gtk-WARNING **: 16:02:01.538: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Username for 'https://github.com': ghummel91

(gnome-ssh-askpass:4747): Gtk-WARNING **: 16:02:08.274: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Password for 'https://ghummel91@github.com':
Counting objects: 3, done.
Delta compression using up to 56 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 345 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/ghummel91/Grad-Project.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
[inbre025@tlog2 Grad-Project]$ ls -l
total 0
-rw-rw-r-- 1 inbre025 inbre-train 114 Dec  9 16:00 Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ cd ..
[inbre025@tlog2 project]$ ls -l
total 7027712
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec  9 16:00 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 15:57 History
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
# Got it! Commit appeared in Github webpage
