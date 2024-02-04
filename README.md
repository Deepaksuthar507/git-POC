# git-POC

1. Remove the Sensitive File Locally:
Delete the sensitive file ( .env) from your local working directory.
---------
command =====>   git rm --cached .env
---------

2. Update .gitignore:
Make sure to add or update your .gitignore file to exclude the sensitive file. Open .gitignore in a text editor and add the line:
---------
command =====>   .env
---------

3. Commit and Push Changes:
Commit the changes to your local repository.
---------
command =====>   git commit -m "Remove sensitive .env file"
---------

4. Then, push the changes to the remote repository.

git push origin <branch-name>







