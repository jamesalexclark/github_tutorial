# github_tutorial:
How to use github for the MPCR lab!

## Slide link:

https://docs.google.com/presentation/d/1hGA3yOmr3waBtG7pag54LXoPnijA7sFFRBKznTjhVJc/edit?pli=1#slide=id.p1


# On local computer:
getapp git to download

# gitignore:
use this to list file types (*.whatever) and folders you want to exclude.

Use git status from local folder
can use git add * to add all files
git add readme.md to update only the readme.md file


# After you update a local repository:
you need to give it your name and email:
git config user.email "jamesclark2016"
git config user.name "James Alex Clark"
git push origin master (to send the local changes to the origin on github master branch
it will ask for a login (username and password)

# To update from the web server where new_branch is the name of the thing you want to pull:
git pull origin new_branch

# to switch to master from whereever you are:
git checkout master

# to merge new_branch into master (when you are in master):
git merge new_branch
