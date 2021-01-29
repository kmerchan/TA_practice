# 0x03-git
This directory contains initial work with git:

## Learning Objectives:
* What is source code management
* What is Git
* What is GitHub
* What is the difference between Git and GitHub
* How to create a repository
* What is a README
* How to write good READMEs
* How to commit
* How to write helpful commit messages
* How to push code
* How to pull updates
* How to create a branch
* How to merge branches
* How to work as collaborators on a project
* Which files should and which files should not appear in your repo

## Mandatory Tasks
0. [Repo-session](/0x03-git)
* Create a new directory called `0x03-git` in your `holbertonschool-zero_day` repo and include `README.md`
1. [Coding fury road](/0x03-git)
* Create these directories at the root of the project:
  * [bash](/0x03-git/bash)
  * [c](/0x03-git/c)
  * [js](/0x03-git/js)
* Create these empty files:
  * [c/c_is_fun.c](/0x03-git/c/c_is_fun.c)
  * [js/main.js](/0x03-git/js/main.js)
  * [js/index.js](/0x03-git/js/index.js)
* Create file [bash/holberton](/0x03-git/bash/holberton) with the two lines `#!/bin/bash` and `echo "Holberton"`
* Create file [bash/school](/0x03-git/bash/school) with the two lines `#!/bin/bash` and `echo "School"`
* Add all new files to git with the commit message "Starting to code today, so cool!"
2. [Collaboration is the base of a company](/0x03-git)
* Create a branch `update_script` and do the following:
  * Create empty file [bash/98](/0x03-git/bash/98)
  * Update [bash/holberton] by replacing `echo "Holberton"` with `echo "Holberton School"`
  * Update [bash/school] by replacing `echo "School"` with `echo "The school is open!"`
  * Add these changes with the commit message "My personal work"
* Change branch back to `main` and do the following:
  * Update the file [bash/holberon](0x03-git/bash/holberton) by replacing `echo "Holberton"` with echo `"Holberton School os so cool!"`
  * Delete the directory [js](/0x03-git/js)
  * Add these changes with the commit message "Hot fix"
