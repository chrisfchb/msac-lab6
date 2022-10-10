 # Exercise 1 - Setting up your first repository

1. Create a new, empty directory

        mkdir my_repository

2. `cd` into it

        cd my_repository

3. Initialize it as a git repository.

        git init

4. Where are the internals of the repository stored? Paste the output of the following command on macOS & Linux.

        ls -lA
So - I think what's meant is the directory created when the folder is initialized:  
.git file in the directory, now containing several files and folders, this includes hooks, info, objects, refs folders, and config, description and HEAD folders
