# Command History in Markdown

## 1. **Directory and Navigation**
   - Create a directory:  
     `mkdir git-for-devops`
   - List files in the directory:  
     `ls`
   - Change to the directory:  
     `cd git-for-devops/`
   - Show the current directory path:  
     `pwd`
   - Clear the terminal:  
     `clear`

## 2. **File Operations**
   - Create or edit a file:  
     `vim Ramesh.txt`
   - Display the content of a file:  
     `cat Ramesh.txt`
   - Create multiple files:  
     `touch Hema.txt`  
     `touch Aadvik.txt`
   - Delete a file:  
     `rm Ramesh.txt`
   - List files with details:  
     `ls -l`
   - Show hidden files:  
     `ls -a`
   - Remove a file from the staging area (cached):  
     `git rm --cached Hema.txt`
   - Remove a file:  
     `git rm --Hema.txt`
   - Restore a deleted file:  
     `git restore Hema.txt`

## 3. **Git Initialization**
   - Initialize a Git repository:  
     `git init`

## 4. **Git Configuration**
   - Set the global Git username:  
     `git config --global user.name "Ramesh1892"`
   - Set the global Git email:  
     `git config --global user.email "rameshvutukurii@gmail.com"`

## 5. **Viewing Git Status**
   - Check the status of the working directory and staging area:  
     `git status`

## 6. **Staging and Committing Changes**
   - Add files to the staging area:  
     `git add Hema.txt`  
     `git add Aadvik.txt`  
     `git add tinku.txt`
   - Commit changes to the repository:  
     `git commit -m "adding Hema Aadvik"`  
     `git commit -m "added changes in Hema file"`  
     `git commit -m "added tinku"`

## 7. **Branching**
   - Create a new branch:  
     `git checkout -b dev`
   - Switch between branches:  
     `git checkout master`  
     `git checkout dev`
   - List all branches:  
     `git branch`

## 8. **Viewing Logs and History**
   - View the commit history:  
     `git log`
   - View a concise commit history (oneline):  
     `git log --oneline`
   - Show command history:  
     `history`

## 9. **Other Operations**
   - Show system uptime:  
     `uptime`
   - Show the current date and time:  
     `date`
   - Show current working directory:  
     `pwd`
