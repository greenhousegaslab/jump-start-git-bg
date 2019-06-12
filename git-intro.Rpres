Getting Started with Git
========================================================
author: Leyang Feng
date: June 12, 2019
autosize: true

A workshop covering reproducibility; version control; basic git workflows. 

Reproducibility
========================================================
type: section


Reproducibility
========================================================

We are in the era of 'big data', but even if you work with 'little data' you have to acquire some skills to deal with those data.

**Most fundamentally, your results have to be reproducible.**

>Your most important collaborator is your future self. It’s important to make a workflow that you can use time and time again, and even pass on to others in such a way that you don’t have to be there to walk them through it. [Source](http://berkeleysciencereview.com/reproducible-collaborative-data-science/)

Reproducibility means *scripts* or *programs* tied to *open source software*.


You can't reproduce
========================================================
...what doesn't exist.
- Gozilla ate my computer
+ backup
+ ideally *continuous*
- Godzilla ate my office
+ cloud

***

<img src="git-intro-figure/godzilla.jpg" width="400" />


You can't reproduce
========================================================

...what you've lost. What if you need access to a file as it existed 1, 10, or 100, or 1000 days ago?
- Incremental backups (minimum)
- Version control (better). A *repository* holds files and tracks changes

***

<img src="git-intro-figure/tardis.jpg" width="400" />

Version control
========================================================
type: section


What on earth did I do???
========================================================

<img src="git-intro-figure/history.png" width="800" />

Git and GitHub
========================================================

**Git** (and website **GitHub**) are the most popular version control tools for use with R, and many other languages:
- version control
- sharing code with collaborators
- issue tracking
- social coding

***

<img src="git-intro-figure/github.png" width="400" />


Git
=======================================================

- a version control software (stand along)
- standard installation for most Unix/Linux distributions 
- standard installation for Mac OSX with Xcode developer tools 
- create snaphot for changed file in your folder/repository. 

***

<img src="git-intro-figure/git-logo.png" width="400" />
<img src="git-intro-figure/git-hidden-file.png" width="400" />


Git workflow
======================================================

- set up your working directory (folder)
- initialize git in your folder 
- file operations in your folder (create/change/delete)

    *just remember **git is watching you***
- commit then changes so that the git can create current snapshot of your folder

***

<img src="git-intro-figure/history.png" width="800" />


Git to GitHub
======================================================

Using Git, now you have version control, but you still have:

- Godzilla
- hard disk failure 
- ...

Or, your want to:

- collaborate with others that you cannot just transfer the code with a thumb drive
- simply show-off your cool/fancy/geniusly written code  

<img src="git-intro-figure/cool-code.png" width="400" />

GitHub
=======================================================

- a platform that provides remote repository storage
- integration with git to track code change
- built-in tools for collaboration
- monitor stats of your repository

<img src="git-intro-figure/repo-stats.png" width="800" />

Basic GitHub workflow
=======================================================

- *start/clone a repository from GitHub* (creating folder and initialize git)
- file operations in your folder (create/change/delete)
- commit then changes so that the git can create current snapshot of your folder
- *push the changes to GitHub repository*

<img src="git-intro-figure/repository-network.png" width="600" />


Team Work (or not) on GitHub -- Branching
=======================================================

<img src="git-intro-figure/github-workflow.png" width="800" />

pull requests...


Pull Request
=======================================================
- propose to merge branch to master 
- forum style discussion board 

<img src="git-intro-figure/pull-request.png" width="600" />

Putting all together
=======================================================
type: section


Reproducible research example
========================================================

A typical project/paper directory for me:
```
1-download.R
2-process_data.R
3-analyze_data.R
4-make_graphs.R
logs/
output/
rawdata/
```

This directory is backed up both *locally* and *remotely*, and is under *version control*, so it's easy to track changes over time.

Reproducible research example
========================================================

- Sequentially numbered R scripts (`0-download.R`, `1-process_data.R`, ...)
- Each script depends on the previous one
- Each has a discrete, logical task
- Each produces a *log file* including date/time, what R version was used, etc.
- This analytical chain starts with raw data
- ...and ends with figures and tables for ms
+ *or the ms itself!* This presentation, for example, was generated directly from an R file

Using git
========================================================
type: section

- GUI client
- CLI

GUI client
========================================================

* GitHub desktop

<img src="git-intro-figure/desktop-screenshot.png" width="600" />

* SourceTree

CLI
=========================================================

<img src="git-intro-figure/git-cli.png" width="800" />

Other Resources 
==========================================================

[Getting Started with Git](https://www.linode.com/docs/development/version-control/how-to-configure-git/)

[GitHub Desktop tutorials](https://help.github.com/en/desktop)

[Git Pro](https://github.com/progit)




