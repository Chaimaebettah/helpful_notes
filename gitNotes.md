#Notes for Git and Git hub Operations for Code Fellows Code 201:

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
        git clone https://github.com/midfies/helpful_notes.git

***

## Add, Commit, and Push changes to GitHub (ACP)

1. Ensure all changes to be saved to GitHub are saved in editor
2. Open Terminal
3. Enter command 'git add ' and then the file to be staged for commit.  The command ' git add .' will stage all files for commit.

        Example:
        git add gitNotes.md
4. Enter command 'git commit -m "commit message"' to prepare commit.  -m tag is used to add note/message to the commit on gitHub. Text inside of quotes is the message to be added.

        Note: Multiple commits can be used before moving to the next step.

5. Finally, enter command 'git push origin master' to push changes gitHub.  Master here defines the branch you are pushing to.

***

## Fork From Another Users Repository, Edit and Submit Pull Request

1.
2.
3.
