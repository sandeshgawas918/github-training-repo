Steps
1. git config
    git config --global user.name "FIRST_NAME LAST_NAME"

2. git add . / git add <filename>

3. git commit -m 'your message'

4. git status
    On branch master
    nothing to commit, working tree clean

5. Make changes to file
    $ git status
    On branch master
    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
        modified:   index.
        
6. git add .
    $ git status
    On branch master
    Changes to be committed:
    (use "git restore --staged <file>..." to unstage)
            modified:   index.html

7. git restore -- index.html

8. git restore .

9. git rm <filename>

10. git diff

11. git log / git log --oneline

12. git branch
    git switch -c <new branch>

13. git merge <branch name> 

14. git branch -d <branch name>



*******GITHUB*********

1. git remote add origin <repo name> 

2. git add .

3. git commit -m 'message'

4. git push --all

5. Modifying Repo from Github
    -> Make changes
    -> Commit
    -> new branch
    -> create pull request
    -> Accept request and merge with master branch

6. git clone <repo name> **to clone remote repo on local machine**

7. git fetch   **to get all changes**

8. git branch -a **this shows all the present branch**

9. git pull
    There is no tracking information for the current branch.
    Please specify which branch you want to merge with.
    See git-pull(1) for details.

        git pull <remote> <branch>

    If you wish to set tracking information for this branch you can do so with:

        git branch --set-upstream-to=origin/<branch> master

10. git branch --set-upstream-to=origin/master master
    **branch 'master' set up to track 'origin/master'.**

11. git pull

12. git switch -c <new branch> **to create new branch on local**

13. git switch <branch name> **to togle between branches**



