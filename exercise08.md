# Exercise 8 - Viewing changes before committing

1. Ensure your working directory is clean

2. Add text to any one of your files

3. Delete different text from another of your files

4. Look at `git status`

5. View all the changes you've made

        git diff

6. Does the following command return anything?

        git diff --staged

        No the following command does not return anything 
7. Add one of your changed files to the index

        git commit add <changed file>

8. What do these commands show?

        git diff
        git diff --staged
        
        Diff shows the difference made in all files 
        While git diff staged shows the differences made in one file that is added 

9. Add the other changed file to the index

        git commit add <other changed file>
        
        

10. What do these commands show?

        git diff
        git diff --staged
        
        diff still shows the file that was changed much like git diff --staged in this case I didn't see any differences 

11. Commit the changes

12. Check that your working directory is clean

13. Create a new file named `clothing.txt`

14. Does the new untracked file show up in git diff?

        git diff
        No it does not show up since it is untracked 
15. Add and commit the new file
