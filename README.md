# Explain version control?

Version control also known as source control, is the practice of tracking and managing changes to software codes. it helps software teams keep track of every modification to the code in a special kind of database.

# Explain difference between git and github.

    ## git
    It is a tool to track and implement version contorl changes to files
    It is a version control system designed to handle everything from small to large projects with speed and efficiency.
    ## github
    It is a site that provides hostings for repositories (documents) and several tools for working with them.

# Explain the difference between git fetch and git pull. 

    ## git fetch
    It downloads the content but not update the local repositories working state, leaving the currrent work intact.
    It is what you do when you want to see what everybody else has been working on.
    ## git pull
    It downloads the remote content for the active local branch and immediately execute git merge to create a merge commit for the new remote content.

# Explain in simple terms git rebase and the command for it.

It is an action in git that rewrite commits from one git branch to another branch. It deletes commit from one branch and adding them to another.
 ## git rebase commands.
    1. git rebase base: Performs the standard rebase.
    2.  git rebase – interactive :Performs the interactive rebase.
    3. git rebase -- d: The commit gets discarded from the final combined commit block during playback.
    4. git rebase -- p: This leaves the commit alone, not modifying the content or message, and keeping it as an individual commit in the branches’ history.
    5. git rebase -- x: This executes a command line shell script for each marked commit during playback.
    6. git status:Checks the rebase status.
    7. git rebase -- continue: Continue with the changes that you made.
    8. git rebase --skip: Skips the changes.
    9. git add <project file>: Adds your branch to the repository.
    10:git commit -m "new commit for <branch name>.":   Commits the changes. 
# Explain in simple terms git cherry pick and the command for it.
   ## git cherry pick
    git cherry-pick in git means choosing a commit from one branch and applying it to another branch.
   ## git cherry commans 
    1. git cherry-pick: Basic Cherry-Pick.
    2. git cherry-pick -m feature-branch: Cherry-Picking to a Different Branch.
    3. git cherry-pick --no-commit: Applying Changes Without Committing.
    4. git cherry-pick --skip: Skipping a Cherry-Pick
    5. git cherry-pick --abort: Abort a Cherry-Pick. 
       
