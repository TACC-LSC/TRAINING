# Intro to High Performance Computing for Life Sciences

* **Course Location:** UT Health Science Center – Houston, Basic Sciences Research Building, Room S3.8112 (GSBS Computer Lab)
* **Date and Time:** Thursday, September 10th, 2015, 1:00pm - 4:00pm
* **Presenter:** Joe Allen (wallen [at] tacc.utexas.edu)

### Course Objectives 

This workshop is designed to introduce skills required to perform computational research in the life sciences. First, an overview of different compute and storage resources are described, with a focus on those available at TACC or MD Anderson. Students will learn and practice commands in a Linux terminal, the text editor VIM, and basic shell scripting. The workshop will also cover essential topics for the life sciences in high performance computing including environment variables, modules, and batch job submission. This ~3-hour workshop is intended for people who have little to no experience with a command line interface, but intend to use a Linux workstation or HPC cluster for life science research.

This workshop is divided into four modules:

 1. [Overview of Compute and Storage Resources](#mod1) (15 min)
 2. [Linux Command Line Basics](#mod2) (45 min)
 3. [Text Editing with VIM](#mod3) (30 min)
 4. [Environment, Modules, Job Submission](#mod4) (30 min)


### Instructional Objectives

This course is taught as an interactive workshop. Students will actively engage in course discussion, and participate with working examples in a Linux terminal. As such, it is necessary that students have access to a command line interface for the course. It should be taught in a room equipped with computers and internet access. Rooms not equipped with computers will work if the students bring their own laptops and have internet access. Students should also have an existing allocation on a TACC or Host Institution resource. Students without an allocation can still participate in most components of the workshop if they have a Mac / Linux laptop, or a Windows laptop with Putty installed and access to a Linux server.



### Specific Learning Objectives

| <a name="mod1"></a>Module 1: Overview of TACC / MD Anderson Compute and Storage Resources (15 min) |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> What is high performance computing and why is it useful? </li><li> Compute resources at TACC (Lonestar, Stampede, Maverick, Corral, Ranch). </li><li> Compute resources at MD Anderson (Shark, Nautilus). </li></ul> |
| **Students should be able to...** |
| <ul><li> Describe possible applications for HPC in the life sciences. </li><li> Choose the correct resource at TACC for their research needs. </li><li> Choose the correct resource at MD Anderson for their research needs. </li></ul> |
| **Assessment activities:** |
| <ul><li> Discussion: How will HPC help your research project? </li><li> Go to the TACC User Portal and MD Anderson HPCWeb: Find and record the process for asking questions and getting help. </li><li> Log on to a cluster or server and read the welcome text. </li></ul> |

<br/>

| <a name="mod2"></a>Module 2: Linux Command Line Basics (60 min) |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> Brief introduction to the Linux operating system. </li><li> Looking and moving around (`pwd`, `ls`, `mkdir`, `cd`, `rmdir`). </li><li> Creating and manipulating files (`touch`, `rm`, `mv`, `cp`, `vim`). </li><li> Looking at the contents of files (`cat`, `more`, `less`, `head`, `tail`). </li><li> More files commands (`ln`, `chmod`, `grep`, `tar`, `gzip`). </li><li> Network and file transfers (`hostname`, `whoami`, `ssh`, `scp`, `rsync`). </li><li> Miscellaneous commands (`man`, `which`, `diff`, `df`, `du`, `date`, `history`, `logout`). </li><li> Shortcuts (`Tab`, `Up Arrow`, `Ctrl+c`, `Ctrl+d`, `./`, `../`, `~/`, `>`, `>>`, `*`, `|`, `&`). </li></ul> |
| **Students should be able to...** |
| <ul><li> List benefits and capabilities of a command line interface. </li><li> Use all of the commands covered in this module. </li><li> Find documentation for unknown commands and flags. </li></ul> |
| **Assessment activities:** |
| <ul><li> `Lab01.tar:` Naming and renaming directories for better organization. </li><li> `Lab02.tar:` Exploring large files (word lists and fasta). </li><li> `Lab03.tar:` Determine how to use previously unknown commands. </li></ul> |

<br/>
**BREAK (5 min)**
<br/><br/>

| <a name="mod3"></a>Module 3: Text Editing with VIM (30 min) |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> Switching back and forth between insert mode (IM) vs. normal mode (NM) (`i`, `o`, `O`, `Esc`). </li><li> IM: Entering text as a typical text editor. </li><li> NM: Navigating a file (`<arrow keys>`, `hjkl`, `0`, `$`, `gg`, `G`, `Ctrl+u`, `Ctrl+d`). </li><li> NM: Deleting, coping, and pasting text (`x`, `dw`, `dd`, `yy`, `p`, `P`, `<number><command>`). </li><li> NM: Searching for text (`/pattern`, `n`, `N`). </li><li> NM: The command line (`:`, `:<line number>`, `:%s/find/replace/gc`, `:read <file>`). </li><li> NM: Saving and quitting (`:w`, `:wq`, `:q`, `:q!`). </li><li> NM: Other useful things to know (`u`, `Ctrl+r`, `.`). </li></ul> |
| **Students should be able to...** |
| <ul><li> Open, edit, and save documents with VIM. </li><li> Switch back and forth between insert mode and normal mode. </li><li> Navigate to different parts of a file quickly. </li><li> Search for a specific string of text. </li><li> Find and replace text. </li></ul> |
| **Assessment activities:** |
| <ul><li> `Lab04.tar:` Curating gene sequence files for analysis. </li><li> Learn by practice! Dive headfirst into Module 3! </li><li> Other practice tools available: `vimtutor`, vim-adventures.com, openvim.org. </li></ul> |

<br>

| <a name="mod4"></a>Module 4: Environment, Modules, and Batch Job Submission (45 min) |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> Environment variables – purpose, printing, and defining (echo, env, export). </li><li> Modules – listing, loading, and unloading. </li><li> Automating environment variables, module commands, and aliases in .bash_profile. </li><li> Batch job submission, commands dependent on system (qsub, showq, qdel). </li></ul> |
| **Students should be able to...** |
| <ul><li> Display their current environment variables. </li><li> Change existing and create new environment variables. </li><li> List modules currently loaded in their environment. </li><li> Load and unloaded modules. </li><li> Describe the effects of a module load command. </li><li> Automate module and environment commands in the .bash_profile. </li><li> Write batch job submission scripts. </li><li> Submit jobs to a queue. </li><li> Monitor jobs in a queue and delete jobs from a queue. </li></ul> |
| **Assessment activities:** |
| <ul><li> Display a list of all available modules. </li><li> Read the module description for packages you use. </li><li> `Lab09.tar:` Complete a batch submission script and submit. </li><li> Submit your first batch job. (This is dependent on system and allocation). </li></ul> |


<br>

&copy; 2015 Texas Advanced Computing Center


