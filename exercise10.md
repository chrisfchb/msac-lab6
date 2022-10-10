# Exercise 10 - Understanding Commits

1. Look at your commit log

        git log --oneline

2. Choose a commit hash

3. See what type of object that hash names

        git cat-file -t <hash>

4. Examine the contents of that commit closely

        git cat-file -p <hash>

5. Find the parent's hash in the commit log

6. Look at the contents of the tree

        git cat-file -p <hash>
        PS C:\Users\chris\OneDrive - Trade Customs Logistics\Academics\Mt Sac - CIS\Homework Programs\CISW17\msac-lab6> git cat-file -p 88cf350
tree 0b68e9b1db91063662ce3d75c9f441f80087a7de
parent 0b46806d8c4aea7e4d445eedcc8ae2e7797ea477
author Sable Cantus <sable@cantus.us> 1588824579 -0700
committer Sable Cantus <sable@cantus.us> 1588824579 -0700

renamed for style
PS C:\Users\chris\OneDrive - Trade Customs Logistics\Academics\Mt Sac - CIS\Homework Programs\CISW17\msac-lab6>

7. Examine the contents of one of the blobs

8. What type of object does the parent hash represent?

        git cat-file -t <hash>

9. Examine the contents of the parent and its tree

10. Do the trees you looked at have any matching hashes listed?
i shall have to come back to review this material!
