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
[inbre025@tlog2 project]$ ls -l Grad-Project/
total 0
-rw-rw-r-- 1 inbre025 inbre-train 114 Dec  9 16:00 Project_Writeup.md
# Working through the FastQC files to generate my HTML files
[inbre025@tlog2 project]$ module load gcc fastqc
[inbre025@tlog2 project]$ fastqc -h

            FastQC - A high throughput sequence QC analysis tool

SYNOPSIS

        fastqc seqfile1 seqfile2 .. seqfileN

    fastqc [-o output dir] [--(no)extract] [-f fastq|bam|sam]
           [-c contaminant file] seqfile1 .. seqfileN

DESCRIPTION

    FastQC reads a set of sequence files and produces from each one a quality
    control report consisting of a number of different modules, each one of
    which will help to identify a different potential type of problem in your
    data.

    If no files to process are specified on the command line then the program
    will start as an interactive graphical application.  If files are provided
    on the command line then the program will run with no user interaction
    required.  In this mode it is suitable for inclusion into a standardised
    analysis pipeline.

    The options for the program as as follows:

    -h --help       Print this help file and exit

    -v --version    Print the version of the program and exit

    -o --outdir     Create all output files in the specified output directory.
                    Please note that this directory must exist as the program
                    will not create it.  If this option is not set then the
                    output file for each sequence file is created in the same
                    directory as the sequence file which was processed.

    --casava        Files come from raw casava output. Files in the same sample
                    group (differing only by the group number) will be analysed
                    as a set rather than individually. Sequences with the filter
                    flag set in the header will be excluded from the analysis.
                    Files must have the same names given to them by casava
                    (including being gzipped and ending with .gz) otherwise they
                    won't be grouped together correctly.

    --nano          Files come from naopore sequences and are in fast5 format. In
                    this mode you can pass in directories to process and the program
                    will take in all fast5 files within those directories and produce
                    a single output file from the sequences found in all files.

    --nofilter      If running with --casava then don't remove read flagged by
                    casava as poor quality when performing the QC analysis.

    --extract       If set then the zipped output file will be uncompressed in
                    the same directory after it has been created.  By default
                    this option will be set if fastqc is run in non-interactive
                    mode.

    -j --java       Provides the full path to the java binary you want to use to
                    launch fastqc. If not supplied then java is assumed to be in
                    your path.

    --noextract     Do not uncompress the output file after creating it.  You
                    should set this option if you do not wish to uncompress
                    the output when running in non-interactive mode.

    --nogroup       Disable grouping of bases for reads >50bp. All reports will
                    show data for every base in the read.  WARNING: Using this
                    option will cause fastqc to crash and burn if you use it on
                    really long reads, and your plots may end up a ridiculous size.
                    You have been warned!

    --min_length    Sets an artificial lower limit on the length of the sequence
                    to be shown in the report.  As long as you set this to a value
                    greater or equal to your longest read length then this will be
                    the sequence length used to create your read groups.  This can
                    be useful for making directly comaparable statistics from
                    datasets with somewhat variable read lengths.

    -f --format     Bypasses the normal sequence file format detection and
                    forces the program to use the specified format.  Valid
                    formats are bam,sam,bam_mapped,sam_mapped and fastq

    -t --threads    Specifies the number of files which can be processed
                    simultaneously.  Each thread will be allocated 250MB of
                    memory so you shouldn't run more threads than your
                    available memory will cope with, and not more than
                    6 threads on a 32 bit machine

    -c              Specifies a non-default file which contains the list of
    --contaminants  contaminants to screen overrepresented sequences against.
                    The file must contain sets of named contaminants in the
                    form name[tab]sequence.  Lines prefixed with a hash will
                    be ignored.

    -a              Specifies a non-default file which contains the list of
    --adapters      adapter sequences which will be explicity searched against
                    the library. The file must contain sets of named adapters
                    in the form name[tab]sequence.  Lines prefixed with a hash
                    will be ignored.

    -l              Specifies a non-default file which contains a set of criteria
    --limits        which will be used to determine the warn/error limits for the
                    various modules.  This file can also be used to selectively
                    remove some modules from the output all together.  The format
                    needs to mirror the default limits.txt file found in the
                    Configuration folder.

   -k --kmers       Specifies the length of Kmer to look for in the Kmer content
                    module. Specified Kmer length must be between 2 and 10. Default
                    length is 7 if not specified.

   -q --quiet       Supress all progress messages on stdout and only report errors.

   -d --dir         Selects a directory to be used for temporary files written when
                    generating report images. Defaults to system temp directory if
                    not specified.

BUGS

    Any bugs in fastqc should be reported either to simon.andrews@babraham.ac.uk
    or in www.bioinformatics.babraham.ac.uk/bugzilla/

    [inbre025@tlog2 project]$ vi RNAfastqc1.sh
[inbre025@tlog2 project]$ vi RNAfastqc1.sh
[inbre025@tlog2 project]$ sbatch RNAfastqc1.sh
Submitted batch job 3634212
[inbre025@tlog2 project]$ sbatch --test-only RNAfastqc1.sh
sbatch: Job 3634213 to start at 2019-12-09T16:39:10 using 4 processors on nodes mhm01 in partition inv-inbre
[inbre025@tlog2 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec  9 16:00 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 15:57 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
[inbre025@tlog2 project]$ pwd
/project/inbre-train/inbre025/project
[inbre025@tlog2 project]$ pwd
[inbre025@tlog2 project]$
# The bash worked! Here is the scp command I utilized from my local terminal
C:\Users\User> scp inbre025@teton.uwyo.edu:/project/inbre-train/inbre025/project C:\Users\User\Downloads

                              NOTICE TO USERS
=============================================================================
This is a University of Wyoming computer system, which may be accessed and
used only for authorized business by authorized personnel. Unauthorized
access or use of this computer system may subject violators to criminal,
civil, and/or administrative action. All information on this computer
system may be intercepted, recorded, read, copied, and disclosed by and to
authorized personnel for any purpose. Access or use of this computer system
by any person, whether authorized or unauthorized, constitutes consent to
these terms. There is no right of privacy in this system. Discontinue access
immediately if you do not agree with the conditions stated in this notice.
=============================================================================

                         TWO-FACTOR AUTHENTICATION
=============================================================================
This system requires two-factor authentication.

The password requirement is your UWYO domain password.

The token can be generated by your registered YubiKey or manually input with
the Duo mobile app. If you have questions about using this implementation of
two-factor authentication, contact the ARCC team at arcc-help@uwyo.edu

Please enter the two-factor password the in the form:

                            <password>,<token>

=============================================================================


Password:
Resetting modules to system default
scp: /project/inbre-train/inbre025/project: not a regular file
# I realized this didn't work because I didn't have a file name included. The following secure copies followed the correct pathways

C:\Users\User> scp inbre025@teton.uwyo.edu:/project/inbre-train/inbre025/project/PedCon1_R1_fastqc.html C:\Users\User\Downloads


                              NOTICE TO USERS
=============================================================================
This is a University of Wyoming computer system, which may be accessed and
used only for authorized business by authorized personnel. Unauthorized
access or use of this computer system may subject violators to criminal,
civil, and/or administrative action. All information on this computer
system may be intercepted, recorded, read, copied, and disclosed by and to
authorized personnel for any purpose. Access or use of this computer system
by any person, whether authorized or unauthorized, constitutes consent to
these terms. There is no right of privacy in this system. Discontinue access
immediately if you do not agree with the conditions stated in this notice.
=============================================================================

                         TWO-FACTOR AUTHENTICATION
=============================================================================
This system requires two-factor authentication.

The password requirement is your UWYO domain password.

The token can be generated by your registered YubiKey or manually input with
the Duo mobile app. If you have questions about using this implementation of
two-factor authentication, contact the ARCC team at arcc-help@uwyo.edu

Please enter the two-factor password the in the form:

                            <password>,<token>

=============================================================================


Password:
Resetting modules to system default
PedCon1_R1_fastqc.html                                                                100%  255KB 616.5KB/s   00:00

C:\Users\User> scp inbre025@teton.uwyo.edu:/project/inbre-train/inbre025/project/PedCon1_R2_fastqc.html C:\Users\User\Downloads


                              NOTICE TO USERS
=============================================================================
This is a University of Wyoming computer system, which may be accessed and
used only for authorized business by authorized personnel. Unauthorized
access or use of this computer system may subject violators to criminal,
civil, and/or administrative action. All information on this computer
system may be intercepted, recorded, read, copied, and disclosed by and to
authorized personnel for any purpose. Access or use of this computer system
by any person, whether authorized or unauthorized, constitutes consent to
these terms. There is no right of privacy in this system. Discontinue access
immediately if you do not agree with the conditions stated in this notice.
=============================================================================

                         TWO-FACTOR AUTHENTICATION
=============================================================================
This system requires two-factor authentication.

The password requirement is your UWYO domain password.

The token can be generated by your registered YubiKey or manually input with
the Duo mobile app. If you have questions about using this implementation of
two-factor authentication, contact the ARCC team at arcc-help@uwyo.edu

Please enter the two-factor password the in the form:

                            <password>,<token>

=============================================================================


Password:
Resetting modules to system default
PedCon1_R2_fastqc.html                                                                100%  265KB 668.5KB/s   00:00
# Back to the teton remote terminal
[inbre025@tlog2 project]$ cd Grad-Project/
[inbre025@tlog2 Grad-Project]$ ls -l
total 0
-rw-rw-r-- 1 inbre025 inbre-train 114 Dec  9 16:00 Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ vim Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ [inbre025@tlog2 Grad-Project]$ vim Project_Writeup.md
# I answered Question 1 in the Project_Writeup file I started earlier
# I attempted to push Project_Writeup to Github
[inbre025@tlog2 Grad-Project]$ git remote add origin https://github.com/ghummel91/Grad-Project
fatal: remote origin already exists.
[inbre025@tlog2 Grad-Project]$ git config --list
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
remote.origin.url=https://github.com/ghummel91/Grad-Project.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.master.remote=origin
branch.master.merge=refs/heads/master
[inbre025@tlog2 Grad-Project]$ git push -u origin master

(gnome-ssh-askpass:42636): Gtk-WARNING **: 17:44:54.864: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Username for 'https://github.com': ghummel91

(gnome-ssh-askpass:42660): Gtk-WARNING **: 17:45:00.035: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Password for 'https://ghummel91@github.com':
To https://github.com/ghummel91/Grad-Project.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/ghummel91/Grad-Project.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first merge the remote changes (e.g.,
hint: 'git pull') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
# I did not pull this README.md file to my terminal, and did this here
[inbre025@tlog2 Grad-Project]$ git pull origin master
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 9 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (9/9), done.
From https://github.com/ghummel91/Grad-Project
 * branch            master     -> FETCH_HEAD
Updating 3f831f9..fc6a973
Fast-forward
 README.md | 519 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 519 insertions(+)
 create mode 100644 README.md
[inbre025@tlog2 Grad-Project]$ ls -l
total 64
-rw-rw-r-- 1 inbre025 inbre-train  3026 Dec  9 17:42 Project_Writeup.md
-rw-rw-r-- 1 inbre025 inbre-train 25869 Dec  9 17:45 README.md
[inbre025@tlog2 Grad-Project]$ vi Project_Writeup.md

[2]+  Stopped                 vim Project_Writeup.md
[inbre025@tlog2 Grad-Project]$
[2]+  Stopped                 vim Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git add Project_Writeup.md
[inbre025@tlog2 Grad-Project]$ git commit -m "Question 1"
[master ec4d052] Question 1
 Committer: INBRE Training Account <inbre025@tlog2.cluster>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 7 insertions(+), 1 deletion(-)
[inbre025@tlog2 Grad-Project]$ git push origin master

(gnome-ssh-askpass:43092): Gtk-WARNING **: 17:46:26.708: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Username for 'https://github.com': ghummel91

(gnome-ssh-askpass:43101): Gtk-WARNING **: 17:46:30.197: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Password for 'https://ghummel91@github.com':
Counting objects: 5, done.
Delta compression using up to 56 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.38 KiB | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/ghummel91/Grad-Project.git
   fc6a973..ec4d052  master -> master
   # Despite these errors, I was able to successfully push my Project_Writeup changes to Github. I verified that this push worked by checking my GIthub repository.
[inbre025@tlog2 Grad-Project]$ history >History/Project_session1.sh
-bash: History/Project_session1.sh: No such file or directory
[inbre025@tlog2 Grad-Project]$ cd ..
[inbre025@tlog2 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec  9 17:45 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 15:57 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
[inbre025@tlog2 project]$ history > History/Project_session1.sh
[inbre025@tlog2 project]$ cd History/
[inbre025@tlog2 History]$ ls -l
total 64
-rw-rw-r-- 1 inbre025 inbre-train 14134 Dec  9 17:48 Project_session1.sh
[inbre025@tlog2 History]$
# It took a few tries, but I was able to save my history like we did in class to a History folder within the inbre025 training account.
#
# Begin session 2
esetting modules to system default
[inbre025@tlog1 ~]$ pwd
/home/inbre025
[inbre025@tlog1 ~]$ ls -l
total 0
[inbre025@tlog1 ~]$ ls
[inbre025@tlog1 ~]$ cd ..
[inbre025@tlog1 home]$ ls -l
pwd
[inbre025@tlog1 home]$ pwd
/home
[inbre025@tlog1 home]$ cd inbre025
[inbre025@tlog1 ~]$ ls
[inbre025@tlog1 ~]$ mkdir History
[inbre025@tlog1 ~]$ ls
History
[inbre025@tlog1 ~]$ cd inbre-train/inbre025
-bash: cd: inbre-train/inbre025: No such file or directory
[inbre025@tlog1 ~]$ cd /project
[inbre025@tlog1 project]$ cd inbre-train/inbre025
[inbre025@tlog1 inbre025]$ pwd
/project/inbre-train/inbre025
[inbre025@tlog1 inbre025]$ ls
LearnLinux  project
[inbre025@tlog1 inbre025]$ cd project/
[inbre025@tlog1 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec  9 17:55 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
[inbre025@tlog1 project]$ cd Grad-Project/
[inbre025@tlog1 Grad-Project]$ git pull origin master
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/ghummel91/Grad-Project
 * branch            master     -> FETCH_HEAD
Updating ec4d052..b2a8b39
Fast-forward
 README.md | 115 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 1 file changed, 114 insertions(+), 1 deletion(-)
[inbre025@tlog1 Grad-Project]$ ls -l
total 64
-rw-rw-r-- 1 inbre025 inbre-train  3026 Dec  9 17:42 Project_Writeup.md
-rw-rw-r-- 1 inbre025 inbre-train 31776 Dec 14 21:13 README.md
[inbre025@tlog1 Grad-Project]$ vim Project_Writeup.md
[inbre025@tlog1 Grad-Project]$ vim README.md

[1]+  Stopped                 vim README.md
[inbre025@tlog1 Grad-Project]$
[1]+  Stopped                 vim README.md
[inbre025@tlog1 Grad-Project]$ vim README.md
[inbre025@tlog1 Grad-Project]$ git push origin master

(gnome-ssh-askpass:14595): Gtk-WARNING **: 21:24:01.005: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Username for 'https://github.com': ghummel91

(gnome-ssh-askpass:14638): Gtk-WARNING **: 21:24:09.436: cannot open display:
error: unable to read askpass response from '/usr/libexec/openssh/gnome-ssh-askpass'
Password for 'https://ghummel91@github.com':
Everything up-to-date
[inbre025@tlog1 Grad-Project]$ ls *fastqc*
ls: cannot access *fastqc*: No such file or directory
[inbre025@tlog1 Grad-Project]$ ls -l
total 128
-rw-rw-r-- 1 inbre025 inbre-train 25625 Dec 14 21:23 1
-rw-rw-r-- 1 inbre025 inbre-train  3026 Dec 14 21:15 Project_Writeup.md
-rw-rw-r-- 1 inbre025 inbre-train 31776 Dec 14 21:23 README.md
[inbre025@tlog1 Grad-Project]$ rm 1
[inbre025@tlog1 Grad-Project]$ ls
Project_Writeup.md  README.md
[inbre025@tlog1 Grad-Project]$ cd ..
[inbre025@tlog1 project]$ ls
Grad-Project  PedCon1_R1_fastqc.html  PedCon1_R1.fastq.gz     PedCon1_R2_fastqc.zip  RNAfastqc1.sh
History       PedCon1_R1_fastqc.zip   PedCon1_R2_fastqc.html  PedCon1_R2.fastq.gz    slurm-3634212.out
[inbre025@tlog1 project]$ ls*fastqc*
-bash: ls*fastqc*: command not found
# It took me a little while to figure out where I was, and re-establish my connection with my GIT repository
[inbre025@tlog1 project]$ vim Trim.sh
[inbre025@tlog1 project]$ vim Trim.sh
[inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652070
#
# First attempt at trimming
[inbre025@tlog1 project]$ sbatch --test-only Trim.sh
sbatch: Job 3652071 to start at 2019-12-14T22:04:09 using 4 processors on nodes mhm01 in partition inv-inbre
[inbre025@tlog1 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        388 Dec 14 22:01 Trim.sh
[inbre025@tlog1 project]$ sbatch --test-only Trim.sh
sbatch: Job 3652072 to start at 2019-12-14T22:09:33 using 4 processors on nodes mhm01 in partition inv-inbre
[inbre025@tlog1 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        388 Dec 14 22:01 Trim.sh
[inbre025@tlog1 project]$ cat slurm-3652070.out
starting up
module loaded
Unknown option --threads
Usage:
       PE [-version] [-threads <threads>] [-phred33|-phred64] [-trimlog <trimLogFile>] [-quiet] [-validatePairs] [-basein <inputBase> | <inputFile1> <inputFile2>] [-baseout <outputBase> | <outputFile1P> <outputFile1U> <outputFile2P> <outputFile2U>] <trimmer1>...
   or:
       SE [-version] [-threads <threads>] [-phred33|-phred64] [-trimlog <trimLogFile>] [-quiet] <inputFile> <outputFile> <trimmer1>...
   or:
       -version
finished
 # Once I had my reads downloaded through scp with the same protocol utilized in session 1 I visualized my .html file but didn't see a difference in my trims
 # No difference detected. I ran the Trim.sh file a few times before realizing I missed an essential part of my code
 inbre025@tlog1 project]$ vi Trim.sh
[inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652073
[inbre025@tlog1 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        403 Dec 14 22:20 Trim.sh
[inbre025@tlog1 project]$ vi Trim.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652074
[inbre025@tlog1 project]$ cd Grad-Project/
[inbre025@tlog1 Grad-Project]$ ls -l
total 64
-rw-rw-r-- 1 inbre025 inbre-train  3026 Dec 14 21:15 Project_Writeup.md
-rw-rw-r-- 1 inbre025 inbre-train 31776 Dec 14 21:23 README.md
[inbre025@tlog1 Grad-Project]$ cd ..
[inbre025@tlog1 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        368 Dec 14 22:28 Trim.sh
[inbre025@tlog1 project]$ cat slurm-3652074
cat: slurm-3652074: No such file or directory
[inbre025@tlog1 project]$ cat slurm-3652073.out
starting up
module loaded
Unknown option --threads
Usage:
       PE [-version] [-threads <threads>] [-phred33|-phred64] [-trimlog <trimLogFile>] [-quiet] [-validatePairs] [-basein <inputBase> | <inputFile1> <inputFile2>] [-baseout <outputBase> | <outputFile1P> <outputFile1U> <outputFile2P> <outputFile2U>] <trimmer1>...
   or:
       SE [-version] [-threads <threads>] [-phred33|-phred64] [-trimlog <trimLogFile>] [-quiet] <inputFile> <outputFile> <trimmer1>...
   or:
       -version
finished
 [inbre025@tlog1 project]$ vi Trim.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652075
[inbre025@tlog1 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        450 Dec 14 22:35 Trim.sh
[inbre025@tlog1 project]$ cat slurm-3652075.out
starting up
module loaded
Unknown option --threads
Usage:
       PE [-version] [-threads <threads>] [-phred33|-phred64] [-trimlog <trimLogFile>] [-quiet] [-validatePairs] [-basein <inputBase> | <inputFile1> <inputFile2>] [-baseout <outputBase> | <outputFile1P> <outputFile1U> <outputFile2P> <outputFile2U>] <trimmer1>...
   or:
       SE [-version] [-threads <threads>] [-phred33|-phred64] [-trimlog <trimLogFile>] [-quiet] <inputFile> <outputFile> <trimmer1>...
   or:
       -version
finished
[inbre025@tlog1 project]$ vi Trim.sh
[inbre025@tlog1 project]$ vi Trim.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652076
[inbre025@tlog1 project]$ ls -l Grad-Project/
total 64
-rw-rw-r-- 1 inbre025 inbre-train  3026 Dec 14 21:15 Project_Writeup.md
-rw-rw-r-- 1 inbre025 inbre-train 31776 Dec 14 21:23 README.md
[inbre025@tlog1 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        465 Dec 14 22:54 Trim.sh
[inbre025@tlog1 project]$ ls -l
total 7029824
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        465 Dec 14 22:54 Trim.sh
[inbre025@tlog1 project]$ vi Trim.sh
[inbre025@tlog1 project]$ nano Trim.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652077
[inbre025@tlog1 project]$ cd History/
[inbre025@tlog1 History]$ ls -l
total 64
-rw-rw-r-- 1 inbre025 inbre-train 14134 Dec  9 17:48 Project_session1.sh
[inbre025@tlog1 History]$ cd ..
[inbre025@tlog1 project]$ ls -l
total 14935744
 # Many attempts later, I realized my errors in generating the trimmed files were due to a problem with my .sh file. I had an extra hyphen in one line that messed up everything, but finally found it.
-rw-rw-r-- 1 inbre025 inbre-train 3901218816 Dec 14 23:10 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  194338816 Dec 14 23:10 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train 3830177792 Dec 14 23:10 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  169828352 Dec 14 23:10 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train        465 Dec 14 23:08 Trim.sh
[inbre025@tlog1 project]$ cat Trim,sh
cat: Trim,sh: No such file or directory
[inbre025@tlog1 project]$ cat Trim.sh
#!/bin/bash
#SBATCH -J Trim
#SBATCH -n 1
#SBATCH --cpus-per-task=4
#SBATCH -t 30:00
#SBATCH --mail-type=ALL
#SBATCH --mail-user=ghummel@uwyo.edu

#SBATCH --account=inbre-train

echo "starting up"

module load swset gcc
module load trimmomatic

echo "modules loaded"

trimmomatic PE \
-threads 4 \
PedCon1_R1.fastq.gz PedCon1_R2.fastq.gz \
./fwd_pair.fq ./fwd_unpair.fq ./rev_pair.fq ./rev_unpair.fq \
HEADCROP:10 \
SLIDINGWINDOW:4:24 \
MINLEN:80
echo "finished."
[inbre025@tlog1 project]$ module load gcc fastqc
[inbre025@tlog1 project]$ vim FwRev.sh

[2]+  Stopped                 vim FwRev.sh
[inbre025@tlog1 project]$
[2]+  Stopped                 vim FwRev.sh
[inbre025@tlog1 project]$ vim FwRev.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ vim FqRev.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ vim FqRev.sh
[inbre025@tlog1 project]$ blast FqRev.sh
-bash: blast: command not found
[inbre025@tlog1 project]$ sbatch FqRev.sh
Submitted batch job 3652078
[inbre025@tlog1 project]$ ls -l
total 14935744
-rw-rw-r-- 1 inbre025 inbre-train        312 Dec 14 23:26 FqRev.sh
-rw-rw-r-- 1 inbre025 inbre-train 3901218816 Dec 14 23:10 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  194338816 Dec 14 23:10 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train 3830177792 Dec 14 23:10 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  169828352 Dec 14 23:10 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train         59 Dec 14 23:26 slurm-3652078.out
-rw-rw-r-- 1 inbre025 inbre-train        465 Dec 14 23:08 Trim.sh
# I messed up my time allotment in the code, and running the FastQC on my paired reads didn't work at first
[inbre025@tlog1 project]$ ls -l
total 14935744
-rw-rw-r-- 1 inbre025 inbre-train        312 Dec 14 23:26 FqRev.sh
-rw-rw-r-- 1 inbre025 inbre-train 3901218816 Dec 14 23:10 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  194338816 Dec 14 23:10 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train 3830177792 Dec 14 23:10 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  169828352 Dec 14 23:10 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train       1123 Dec 14 23:27 slurm-3652078.out
-rw-rw-r-- 1 inbre025 inbre-train        465 Dec 14 23:08 Trim.sh
[inbre025@tlog1 project]$ vim FqRev.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ sbatch FqRev.sh
Submitted batch job 3652079
[inbre025@tlog1 project]$ ls -l
total 14936384
-rw-rw-r-- 1 inbre025 inbre-train        316 Dec 14 23:34 FqRev.sh
-rw-rw-r-- 1 inbre025 inbre-train 3901218816 Dec 14 23:10 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  194338816 Dec 14 23:10 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     254527 Dec 14 23:36 rev_pair_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     378985 Dec 14 23:36 rev_pair_fastqc.zip
-rw-rw-r-- 1 inbre025 inbre-train 3830177792 Dec 14 23:10 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  169828352 Dec 14 23:10 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train       1123 Dec 14 23:27 slurm-3652078.out
-rw-rw-r-- 1 inbre025 inbre-train       1973 Dec 14 23:36 slurm-3652079.out
-rw-rw-r-- 1 inbre025 inbre-train        465 Dec 14 23:08 Trim.sh
# This only generated one of my FastQC html files (rev), and it wasn't to the trim specifications I wanted, but matched what we did in class to try to get my code to run at all. I at least got that far! 
[inbre025@tlog1 project]$ vim FqRev.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ vim Trim.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652080
# I edited the Trim.sh file to match my trim specifications (SLIDINGWINDOW:4:28)
[inbre025@tlog1 project]$ ls -l
total 14936384
-rw-rw-r-- 1 inbre025 inbre-train        316 Dec 14 23:42 FqRev.sh
-rw-rw-r-- 1 inbre025 inbre-train 3901218816 Dec 14 23:10 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  194338816 Dec 14 23:10 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     254527 Dec 14 23:36 rev_pair_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     378985 Dec 14 23:36 rev_pair_fastqc.zip
-rw-rw-r-- 1 inbre025 inbre-train 3830177792 Dec 14 23:10 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train  169828352 Dec 14 23:10 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train       1123 Dec 14 23:27 slurm-3652078.out
-rw-rw-r-- 1 inbre025 inbre-train       1973 Dec 14 23:36 slurm-3652079.out
-rw-rw-r-- 1 inbre025 inbre-train        593 Dec 14 23:43 slurm-3652080.out
-rw-rw-r-- 1 inbre025 inbre-train        439 Dec 14 23:43 Trim.sh
[inbre025@tlog1 project]$ cat slurm-3652080.out
starting up
modules loaded
TrimmomaticPE: Started with arguments:
 -threads 4 PedCon1_R1.fastq.gz PedCon1_R2.fastq.gz ./fwd_pair.fq ./fwd_unpair.fq ./rev_pair.fq ./rev_unpair.fq SLIDINGWINDOW:4:28 echo finished.
Exception in thread "main" java.lang.RuntimeException: Unknown trimmer: echo
        at org.usadellab.trimmomatic.trim.TrimmerFactory.makeTrimmer(TrimmerFactory.java:70)
        at org.usadellab.trimmomatic.Trimmomatic.createTrimmers(Trimmomatic.java:59)
        at org.usadellab.trimmomatic.TrimmomaticPE.run(TrimmomaticPE.java:536)
        at org.usadellab.trimmomatic.Trimmomatic.main(Trimmomatic.java:80)
[inbre025@tlog1 project]$ sbatch FqRev.sh
Submitted batch job 3652082
# This appeared to have run and overwritten my previous files, so I attempted to run the FqRev.sh file again as well
[inbre025@tlog1 project]$ scancel slurm-3652082.out
scancel: error: Invalid job id slurm-3652082.out
[inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652083
[inbre025@tlog1 project]$ ls -l
total 10045120
-rw-rw-r-- 1 inbre025 inbre-train        316 Dec 14 23:42 FqRev.sh
-rw-rw-r-- 1 inbre025 inbre-train 1553293312 Dec 14 23:57 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train   22700032 Dec 14 23:57 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     254527 Dec 14 23:54 rev_pair_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     378985 Dec 14 23:54 rev_pair_fastqc.zip
-rw-rw-r-- 1 inbre025 inbre-train 1499709440 Dec 14 23:57 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train   15228928 Dec 14 23:57 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train       1123 Dec 14 23:27 slurm-3652078.out
-rw-rw-r-- 1 inbre025 inbre-train       1973 Dec 14 23:36 slurm-3652079.out
-rw-rw-r-- 1 inbre025 inbre-train        593 Dec 14 23:43 slurm-3652080.out
-rw-rw-r-- 1 inbre025 inbre-train       1973 Dec 14 23:54 slurm-3652082.out
-rw-rw-r-- 1 inbre025 inbre-train        234 Dec 14 23:57 slurm-3652083.out
-rw-rw-r-- 1 inbre025 inbre-train        440 Dec 14 23:54 Trim.sh
# It didn't work. There must have been an issue in my echo command, tried to cancel slurm job, and edited Trim.sh again.
[inbre025@tlog1 project]$ ls -l
total 10045120
-rw-rw-r-- 1 inbre025 inbre-train        316 Dec 14 23:42 FqRev.sh
-rw-rw-r-- 1 inbre025 inbre-train 1553293312 Dec 14 23:57 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train   22700032 Dec 14 23:57 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train       4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train       4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train     260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train 3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train     254527 Dec 14 23:54 rev_pair_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train     378985 Dec 14 23:54 rev_pair_fastqc.zip
-rw-rw-r-- 1 inbre025 inbre-train 1499709440 Dec 14 23:57 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train   15228928 Dec 14 23:57 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train        331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train       1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train        489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train        498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train        499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train        672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train       1123 Dec 14 23:27 slurm-3652078.out
-rw-rw-r-- 1 inbre025 inbre-train       1973 Dec 14 23:36 slurm-3652079.out
-rw-rw-r-- 1 inbre025 inbre-train        593 Dec 14 23:43 slurm-3652080.out
-rw-rw-r-- 1 inbre025 inbre-train       1973 Dec 14 23:54 slurm-3652082.out
-rw-rw-r-- 1 inbre025 inbre-train        234 Dec 14 23:57 slurm-3652083.out
-rw-rw-r-- 1 inbre025 inbre-train        440 Dec 14 23:54 Trim.sh
[inbre025@tlog1 project]$ ls s-l
ls: cannot access s-l: No such file or directory
[inbre025@tlog1 project]$ ls -l
total 35428992
-rw-rw-r-- 1 inbre025 inbre-train         316 Dec 14 23:42 FqRev.sh
-rw-rw-r-- 1 inbre025 inbre-train 14594126086 Dec 14 23:59 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train   252352135 Dec 14 23:59 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train        4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train        4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train      260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train      726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train  3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train      271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train      741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train  3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train      254527 Dec 14 23:54 rev_pair_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train      378985 Dec 14 23:54 rev_pair_fastqc.zip
-rw-rw-r-- 1 inbre025 inbre-train 14057544292 Dec 14 23:59 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train   175918813 Dec 14 23:59 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train         331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train        1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train         498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train         498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train         489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train         498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train         499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train         672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train        1123 Dec 14 23:27 slurm-3652078.out
-rw-rw-r-- 1 inbre025 inbre-train        1973 Dec 14 23:36 slurm-3652079.out
-rw-rw-r-- 1 inbre025 inbre-train         593 Dec 14 23:43 slurm-3652080.out
-rw-rw-r-- 1 inbre025 inbre-train        1973 Dec 14 23:54 slurm-3652082.out
-rw-rw-r-- 1 inbre025 inbre-train         447 Dec 14 23:59 slurm-3652083.out
-rw-rw-r-- 1 inbre025 inbre-train         440 Dec 14 23:54 Trim.sh
[inbre025@tlog1 project]$ vim FqRev.sh
[inbre025@tlog1 project]$ sbatch FqRev.sh
Submitted batch job 3652084
# Trim ran, running FqRev.sh
[inbre025@tlog1 project]$ ls -l
total 35430336
-rw-rw-r-- 1 inbre025 inbre-train         317 Dec 15 00:03 FqRev.sh
-rw-rw-r-- 1 inbre025 inbre-train      251101 Dec 15 00:09 fwd_pair_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train      711186 Dec 15 00:09 fwd_pair_fastqc.zip
-rw-rw-r-- 1 inbre025 inbre-train 14594126086 Dec 14 23:59 fwd_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train   252352135 Dec 14 23:59 fwd_unpair.fq
drwxrwsr-x 3 inbre025 inbre-train        4096 Dec 14 21:37 Grad-Project
drwxrwsr-x 2 inbre025 inbre-train        4096 Dec  9 17:48 History
-rw-rw-r-- 1 inbre025 inbre-train      260638 Dec  9 16:44 PedCon1_R1_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train      726558 Dec  9 16:44 PedCon1_R1_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train  3532577648 Dec  2 10:04 PedCon1_R1.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train      271366 Dec  9 16:44 PedCon1_R2_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train      741959 Dec  9 16:44 PedCon1_R2_fastqc.zip
-rwxr-xr-x 1 vchhatre inbre-train  3663769578 Dec  2 10:04 PedCon1_R2.fastq.gz
-rw-rw-r-- 1 inbre025 inbre-train      257854 Dec 15 00:09 rev_pair_fastqc.html
-rw-rw-r-- 1 inbre025 inbre-train      721086 Dec 15 00:09 rev_pair_fastqc.zip
-rw-rw-r-- 1 inbre025 inbre-train 14057544292 Dec 14 23:59 rev_pair.fq
-rw-rw-r-- 1 inbre025 inbre-train   175918813 Dec 14 23:59 rev_unpair.fq
-rw-rw-r-- 1 inbre025 inbre-train         331 Dec  9 16:35 RNAfastqc1.sh
-rw-rw-r-- 1 inbre025 inbre-train        1869 Dec  9 16:44 slurm-3634212.out
-rw-rw-r-- 1 inbre025 inbre-train         498 Dec 14 22:02 slurm-3652070.out
-rw-rw-r-- 1 inbre025 inbre-train         498 Dec 14 22:20 slurm-3652073.out
-rw-rw-r-- 1 inbre025 inbre-train         489 Dec 14 22:28 slurm-3652074.out
-rw-rw-r-- 1 inbre025 inbre-train         498 Dec 14 22:36 slurm-3652075.out
-rw-rw-r-- 1 inbre025 inbre-train         499 Dec 14 22:54 slurm-3652076.out
-rw-rw-r-- 1 inbre025 inbre-train         672 Dec 14 23:10 slurm-3652077.out
-rw-rw-r-- 1 inbre025 inbre-train        1123 Dec 14 23:27 slurm-3652078.out
-rw-rw-r-- 1 inbre025 inbre-train        1973 Dec 14 23:36 slurm-3652079.out
-rw-rw-r-- 1 inbre025 inbre-train         593 Dec 14 23:43 slurm-3652080.out
-rw-rw-r-- 1 inbre025 inbre-train        1973 Dec 14 23:54 slurm-3652082.out
-rw-rw-r-- 1 inbre025 inbre-train         447 Dec 14 23:59 slurm-3652083.out
-rw-rw-r-- 1 inbre025 inbre-train        1534 Dec 15 00:09 slurm-3652084.out
-rw-rw-r-- 1 inbre025 inbre-train         440 Dec 14 23:54 Trim.sh
# Got both forward and reverse html outputs, ran same scp protocol as the first time (session 1)
[inbre025@tlog1 project]$ vim Trim.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652085
[inbre025@tlog1 project]$ vim Trim.sh
[inbre025@tlog1 project]$ [inbre025@tlog1 project]$ sbatch Trim.sh
Submitted batch job 3652086
# I wanted to add HEADCROP back into my Trim, but it failed at first
# I kept receiving an error in my SLURM email stating I was out of memory. I do not know if this is due to my training account or not, but was unable to add my HEADCROP changes back into the original Trim.sh file
[inbre025@tlog1 project]$ history > History/Project_session2.sh
[inbre025@tlog1 project]$ ls -l History/
total 128
-rw-rw-r-- 1 inbre025 inbre-train 14134 Dec  9 17:48 Project_session1.sh
-rw-rw-r-- 1 inbre025 inbre-train 16061 Dec 15 00:29 Project_session2.sh
[inbre025@tlog1 project]$ scp C:\Users\User\Downloads/Hummel_CompBio_Project inbre@teton.uwyo.edu:/project/inbre-train/inbre025/project/Grad-Project
ssh_exchange_identification: Connection closed by remote host
# Saved history and tried to import my project write up onto Teton server, then realized the server did not allow this.
