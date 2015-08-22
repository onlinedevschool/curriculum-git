# Git Repositories

Any folder with a .git folder in it is a Git project. Inside the .git folder there are a number of files that track the changes to your local repository.

## The local repository

This is the copy of the Git project on your computer. It is the copy you work with on a day to day basis, opening, editing, and saving files. It is where you `commit` the changes you make.

Since Git is a distributed source control management system there can be many respositories, but the local repopsitory is mine. Or in this case, yours.

## Remote repositories

Typically there is a specific repository that acts as the `master copy`. It is usually designated as the `origin` remote. What is a `remote`?

A remote is just a remote repository. There can be many more besides the origin. Maybe the web software you build id deployed to the server where it lives on the web by setting a remote called `production` and `pushing` the code there.

We are going to use Github here as our remote origin repository, but we aren't quite ready to go down that rabbit's hole just yet. First let's use Git as God (Linus) intended... locally!

