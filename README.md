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
