# I have sucessfully uploaded my Local file into Github.</br>
</br>
Here is my steps--</br>
Step 1: Create the Local folder(ignore if it is alredy there)</br>
        to create a folder from terminal.</br>
        COMMAND : mkdir LocalRepo(filename)</br>

Step 2: After creating the folder we need to initialise the folder to Github[basically we need to introduce the folder to github by ading .git file(hidden file) in the folder]</br>
        COMMAND : git init</br>

Step 3: Make any changes like adding new file(index.html etc) </br>

Step 4: Stage those chnages.</br>
        COMMAND : git add . </br>
        (use '.' to add all the file otherwise instead of '.' put file name)</br>

Step 5: Commit those changes.</br>
        COMMAND : git commit -m "Relatable message"</br>

Step 6: Create a new Repository in Github where you want to put all the local files and copy the HTTPS link of the Repo. Now we will link our local folder to the Github Repo.
</br>
        COMMAND : git remote add origin 'paste link here'

Step 7: Check that folder is successfully linked or not.</br>
        COMMAND : git remote -v</br>
        v for verify.</br>
    
Step 8: Now we have to push, before push we need to check the Branch we are on[git branch] and if we see that we are on Master branch, need to rename it to Main.</br>
        COMMAND : git branch -M main(branch name)</br>

Step 9 : Again check the branch to make sure branch name is changed Master to Main[git branch]. After confirming that we are on Main branch, we are ready to push normally.
</br>
        COMMAND : git push origin main
