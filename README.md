# Beginner-Repo
This repository is made for the beginners to get started with git contribution

## Setup Git
- git config --global user.name "John_Doe"
- git config --global user.email "john@example.com"

## Git commands you are going to use

1. git clone url (by cloning all the files in that repo will be available to your local machine + before cloning make sure to fork the repo to your acount)
2. git add filename.txt (after changing a particular file )
3. git add . (too add everything)
4. git commit -m "message"  (it is recommended to commit with a message to tell what are the things you have changed)
5. git push (push it to the main branch now it will be available in github)
> git push origin branch_name (it will push your code from local branch to the master branch) 
e.g __git push origin devsg__ ( it will push branch devsg( local branch) to original repo's master branch , henceforth creating a PR)
6. git config --global https.proxy 172.16.102.28:8080
7. git config --global http.proxy 172.16.102.28:8080
8. git config --global --get-regexp http.*
9. git config --global --unset https.proxy
10. git config --global --unset http.proxy
