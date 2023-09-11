# 2023-09-11-dsci_521_class_3
dsci_521_class_3

- `add FILENAME`: brings `FILENAME` to staging area
- `commit` or `commit -m "MESSAGE`: commits everything with a message in the staging area, saves the file and checks if there are new changes
- `push <WHERE> <WHAT>`: pushes the history/commits (uploads) `FILENAME` to the remote repository, using the commits from the specified branch
- `pull <WHERE> <WHAT>`: pulls/updates the local repository with contents in the remote repository (where) using the inofrmation in the specified branch (what)

`log`: shows the log
    - `log --online`: shows the log in condensed form
    - this may open a terminal program called `less` that lets you scroll
        - use `q` to quit out of that and then get back to regular 

- `diff`: stands for difference, shows the "difference" between your changes and the last known git stage
- `git diff --staged`: shows you the difference 

- `retore --staged <FILE>`: unstages <FILE> 

- `touch <FILE>`: creates a timestamp if the file exists, if not then it creates a new file with that name




- init (creates brand new folder on your computer, not so common in practice)

- download zip (downloads the files exactly as they are without any history)
- clone (better since it has data on the history of the files)

