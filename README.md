# About

Repo for the tooling needed for R bootcamps at BU's Questrom School of Business.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Btibert3/qst-r-bootcamp/master)

> With the inclusion of RStudio below, will need to rebuild the Binder just in case the commands broke the setup.


## RStudio Cloud

The clone doesn't install, so to create an environment that can be shared, once the project is spun up (in your private repo)

```
source("install.R")
```

The code above will install all of the packages, but this will be your environment moving forward.


### Bizarre / Bug?

Steps to repeat:

1.  Create a repo with a folder and a readme
2.  Create a new Project
3.  Confirm that the files and subfolders exist
4.  Add another folder to the gh repo (folder 2) with another readme
5.  Create a new project from the same repo, updated master
6.  New folder exists
7.  Click Workspace
8.  Go back to previous project with only 1 subfolder (not 2)
9.  Subfolders are totally gone


