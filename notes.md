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