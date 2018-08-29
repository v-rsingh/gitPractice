# Git Document
https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control

# gitPractice
This repository is used for GitHub practice and learn how to use GIT

https://github.com/forcedotcom/sfdx-simple
# To know Git Version
$ git --version

# Setting your Git username for every repository on your computer
1. Open Git Bash
2. Set a Git username:

  $ git config --global user.name "Ranjeet Singh"
  
3. Confirm that you have set the Git username correctly:

  $git config --global user.name
  
Note: You will see user name

# Setting your Git username for a single repository
1. Open Git Bash.
2. Change the current working directory to the local repository where you want to configure the name that is associated with your Git commits.
3. Set a Git username: 

   $git config user.name "Ranjeet Singh"
   
4. Confirm that you have set the Git username correctly

   $git config user.Name

# Setting your email address for every repository on your computer
1. Open Git Bash.
2. Set an email address in Git. You can use your GitHub-provided no-reply email address or any email address.

   $git config --global user.email "email@example.com"
   
3. Confirm that you have set the email address correctly in Git.

   $git config --global user.email

# Setting your email address for a single repository
1. Open Git Bash.
2. Set an email address in Git. You can use your GitHub-provided no-reply email address or any email address.

   $git config user.email "email@example.com"
   
3. Confirm that you have set the email address correctly in Git.

   $git config user.email
   
# Verify SSH key Install or not in your system.
1. Open Git Bash
2. Run below script

  $ls -al ~/.ssh
  
# Lists the files in your .ssh directory, if they exist

# Checking Your Settings
If you want to check your configuration settings, you can use the git config --list command to list all the settings Git can find at that point:

$ git config --list

# Git help
$ git help


# Git Command*****************************************************

# Cloning an Existing Repository
using HTTP URL:

$ git clone https://github.com/salesforcemph/gitPractice.git

         OR
SSH:

$ git clone git@github.com:salesforcemph/gitPractice.git

# Checking the Status of Your Files

$ git status

# Checking out Tags
1. To checkout 

   $ git checkout
  
  2. Pull Latest Changes
   
   $ git pull
    
2. If you want to create a new branch to retain commits you create

   $ git checkout -b new-branch-Name
   
3. To switch between branch
  $ git checkout BranchNameORMaster
  
# Staging single Modified Files/ Add single Modified file to staging
$ git add File_Name

Example:
File added or Modified : CONTRIBUTING.md
$ git add CONTRIBUTING.md

#  -A, --all add changes from all tracked and untracked files
$ git add -A

# Commiting your changes 
$ git commit -m "User_StoryName OR Comment"

          OR
          
$ git commit -m "Initial Commit with Apex Classes"


# Push the changes
$git push

# To push the current branch and set the remote as upstream, use
  Here logicForUserInfo is new local branch
  
   $ git push --set-upstream origin logicForUserInfo

# Clear Git Bash Screen
$ Clear
# ********************************************************************

