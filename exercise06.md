# Exercise 6 - Committing a change (full cycle)

1. Look at git status and ensure you have a clean working directory

        git status

2. Open your `fruits.txt` file  in VS Code, your favorite code editor

3. Add some lines to the file

        apple
        banana
        tomato

4. Save and exit the editor

5. Look at git status

        git status

6. Add the file to the index

        git add fruits.txt

7. Check status

        git status
        On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   equipment/appliances.txt
        new file:   vegetables.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   exercise01.md
        modified:   exercise02.md
        modified:   exercise03.md
        modified:   exercise04.md
        modified:   exercise05.md
        modified:   exercise06.md

PS C:\Users\chris\OneDrive - Trade Customs Logistics\Academics\Mt Sac - CIS\Homework Programs\CISW17\msac-lab6>

8. Commit the changes (short commit message included on command line)

        git commit -m "Added more fruit to the list"

9. Check status

        git status

10. Which of the steps could be omitted?
you could skip steps involving checking status, however...

11. Why might it be a bad idea to omit them?
things always go awry in coding!

12. Repeat the above steps to add a new file with the name `vegetables.txt`


13. Create a subdirectory named `equipment` and a new file named `appliances.txt` in that subdirectory

14. Repeat the above steps to commit the new file and directory

15. Repeat the above steps 1-9, adding data to each of your files a few lines at a time, until you can easily do the steps without referring to the steps. You may want to add vegetables to the vegetables file, and appliances to the appliances - or vice versa

#Very cool exercise here!  Always wanted to learn more about git / github!