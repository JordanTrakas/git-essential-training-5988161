## This is a header

- I am writing some notes in this file.

Remote repository
-----------------
Local repository (.git)
Staging area
Local folder (C:\Code)

Commands:
git push -> publish local commits to remote repository
git commit -m "Repository structure refresher" -> commit to local repository
git add . OR git add <filename> -> add to staging area/update what will be committed
git restore --staged <filename> -> remove from staging area
git status -> status of repository

if we delete example2.md from PyCharm we can find the status and see that it was deleted.
Then we commit our change (deletion)

We can rename a file. Say we rename this from example.md to new_name.md

Renamed README.md to READUS.md by using **git mv** <old name> <new name>

Note that git does not track empty folders. We can make sure that Git recognizes an empty folder by adding a .gitkeep file