# ICES GitHub Guidelines

ICES provides four GitHub areas to facilitate scientific collaboration in marine
research:

1. Expert Groups<br>
https://github.com/ices-eg

2. Tools under development<br>
https://github.com/ices-tools-dev

3. Tools maintained by ICES<br>
https://github.com/ices-tools-prod

4. Transparent Assessment Framework<br>
https://github.com/ices-taf

5. ICES Publications<br>
https://github.com/ices-publications

The code in these repositories can be browsed and downloaded. To apply for write
access to specific repositories, please send an email to github@ices.dk.

The distinction between tools-prod and tools-dev is that
github.com/**ices-tools-prod** contains software that is operational and
maintained by the ICES Secretariat, while github.com/**ices-tools-dev** contains
everything else (operational software maintained by scientists outside the
Secretariat, experimental projects, etc.)

github.com/**ices-publications** contains the text and source files necessary to 
generate some ICES publications.

***

The main guidelines for working in the ICES GitHub areas are:

- Users should provide their full name in their GitHub profile
  (https://github.com/settings/profile).

- Users should register their GitHub username at https://taf.ices.dk/github.
  This allows you to be added as a member of your ICES Working Groups on GitHub
  and get write access to repositories.

- Repositories should be kept under 1 GB and should mainly contain code and
  configuration files. Large datasets, images, and documents are better stored
  elsewhere.

- Expert Group chairs may recommend a certain GitHub workflow for that group.

***

### Introduction to GitHub

Most ICES scientists connect to their GitHub repositories inside RStudio. The
very first steps for beginning users are then to install the required software
(R, RStudio, Git), create a username on https://github.com, and register their
username on https://taf.ices.dk/github.

To work on a repository in RStudio, select `File - New Project - Version
Control - Git`, then paste the URL (e.g. https://github.com/ices-eg/wg_HAWG) and
create the project. This action is called to *clone* a repository, creating a
special directory on the hard drive that is linked to the GitHub repository.

A Git tab will now appear in the upper-right window, containing the following
commands:

Command  | Purpose
-------- | ---------------------------------------------
`Commit` | Write a log message about changes in files
`Pull`   | Get the newest updates from GitHub repository
`Push`   | Submit committed changes to GitHub repository

It is always recommended to *pull* the newest updates before editing files,
*committing*, and *pushing* them to GitHub. Right-clicking a file in the Git
window will show useful commands to *diff* and *revert* changes.

***

### Useful links

The main GitHub help page can be found at:<br>
https://help.github.com

A hello world tutorial can be found at:<br>
https://guides.github.com/activities/hello-world/

A very usefull guide on how to get yourself out of a fix and many other helpful 
git commands can be found here:<br>
https://github.com/k88hudson/git-flight-rules

Other help resources, including the Git book, are listed in the R development
guidelines used by the ICES Secretariat:<br>
https://github.com/ices-tools-prod/doc#62-development-tools
