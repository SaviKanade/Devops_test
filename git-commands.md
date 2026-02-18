**************************************************************************************************************************************************
Setup & Config :

Create a new directory.
            $ mkdir git-practice

git init - Tells that the directory is now a git repository.
            $git init

git config --global user.name - Changes the commit user name.
            $ git config --global user.name "savikanade123"

git config --global user.email - Changes the commit user mail.
            $ git config --global user.name "savikanade123@gmail.com"


**************************************************************************************************************************************************
Basic workflow :

Either copy a file from other directory or create a new file.

New file in repo.
            $ touch test.txt

git add - Adds the file in staged mode of git repo.
            $ git add test.txt

git commit - This line commits the changes in your git repo with a meaningful message.
            $ git commit -m "Initial Commit"


**************************************************************************************************************************************************
Viewing Changes :

git status - This command shows the update/changes/status of your git repo.
            $ git repo

git log - It shows all the information regarding your repo such as who has commited (username & email), Head (in which branches changes has been done & i points to the latest branch).
            $ git log



**************************************************************************************************************************************************
