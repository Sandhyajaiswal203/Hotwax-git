# GIT ASSIGNMENT - 1

#  My Git Repository : Hotwax-git
#  First file name is git1.txt.
#  Second file name is git2.txt.

# I had performed the following commands in this files.

# COMMANDS :-

# git --version                              : To check the version of installed git .
# mkdir Hotwax-git                           : Make new directory.
# cd Hotwax-git                              : Entering into the new directory.
# git init                                   : Initialize  empty git repository.

# CONFIGURING GIT :-

# git config --global  user.name "Sandhyajaiswal203"              : This command is used to set name of the account in which we want to change. 
# git config --global  user.email "sandhyajaiswal2005@gmail.com"  : This command is used to set email address of the account in which we want to change.

# git config --list                          : Gives the list of configure files and gives through which user and email it configured.
# git status                                 : Gives the current status of the files/code (It may be tracked,untracked or modifieds files).
# git clone <-link->                         : Cloning a repository on our local machine.
# git add git1.txt                           : Adding changes made (It may called that file is staged).
# git commit -m "new change in git1.txt"     : Used to save  changes.
# git commit -amend                          : To add last commit with current commit.
# git log                                    : Gives history of files(last commit history).
# git diff                                   : This command compares commits in the files.
# git diff git2.txt                          : This command gives difference between last and previous changes on that particular file.
# git diff -staged                           : This command list out the changes betwwen the staged area and our last commit.
# git branch                                 : To check branch name.
# git branch -M main                         : To rename  the existing branch(Master) to  branch (main).
# git branch feature1                        : To create a new branch.
# git branch feature2                        : To create a new branch.
# git push -u origin main                    : Pushing changes made from local to github.
# git checkout feature1                      : Switching from main branch to feature1 branch.
# git branch -d feature2                     : To delete branch.
# git merge feature1                         : Used for merging two branches (Merging feature1 with main).