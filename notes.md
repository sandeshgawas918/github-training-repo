Steps
1. git config

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

