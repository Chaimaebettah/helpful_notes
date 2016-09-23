#Notes for Git and GitHub Operations for Code Fellows Code 201:

***

## Create Repository

1. Go to your GitHub Profile Page
2. Click '+' drop down menu in upper right
3. Select 'New Repository'
4. Enter name for your new repository
5. Add optional description
6. Ensure repository is marked public
7. Check 'Initialize this repository with a README' box
8. Select 'MIT' from Add License drop down menu.
9. Click 'Create Repository'

***

## Clone Repository to Your Computer

1. Navigate to repository page on GitHub
2. Copy Link to Repository from GitHub by clicking on green 'Clone or Download'
drop down menu and click on the clipboard to copy link to clipboard
3. Open Terminal
4. Navigate to desired directory
5. Enter command 'git clone ' and then paste the copied link

        Example:
        git clone https://GitHub.com/midfies/helpful_notes.git

***

## Add, Commit, and Push changes to GitHub (ACP)

1. Ensure all changes to be saved to GitHub are saved in editor
2. Open Terminal
3. Enter command 'git add ' and then the file to be staged for commit.  The command ' git add .' will stage all files for commit.

        Example:
        git add gitNotes.md
4. Enter command 'git commit -m "commit message"' to prepare commit.  -m tag is used to add note/message to the commit on GitHub. Text inside of quotes is the message to be added.

        Note: Multiple commits can be used before moving to the next step.

5. Finally, enter command 'git push origin master' to push changes GitHub.  Master here defines the branch you are pushing to.

***

## Fork From Another Users Repository, Edit and Submit Pull Request

1. Go to repository page on GitHub that you want to clone
2. Click on fork button in the top right. This will take you to the page of the new fork.
3. Follow above instructions for cloning repository to your computer.
4. Make edits
5. Follow above instructions for ACP
6. Return to forked repository page and click on 'New Pull Request'
7. Ensure there is a green check and says 'Able to Merge'
8. Click green 'Create Pull Request'
9. Add optional comments
10. Click 'Submit Pull Request'
11. From this point, the owner of the repository must accept pull Request and
pull changes to their computer.

***

## Working With Branches

1. Open Terminal
2. Navigate to repository directory you wish to branch
3. Enter command 'git pull origin master' to ensure you have the most recent version of master
4. Enter command 'git checkout -b branchName' where branchName is the name of the branch you are creating
5. Make edits
6. Follow above instructions for ACP with the following exception: Step 5 should be changed to 'git push origin branchName' in order to push the changes to the new branch
7. Go to branch repository on GitHub
8. Click green 'Compare & Pull Request' button
9. Ensure there is a green check and says 'Able to Merge'
10. Add optional comments
11. Click green 'Create Pull Request' button
12. Click green 'Merge Pull Request' button
13. Click green 'Confirm' button
14. Return to Terminal
15. Enter command 'git checkout master' to return to master branch
16. Enter command 'git pull origin master' to refresh master branch on your computer
