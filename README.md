# Data Version Control Tutorial

Example repository for the [Data Version Control With Python and DVC](https://realpython.com/python-data-version-control/) article on [Real Python](https://realpython.com/).

To use this repo as part of the tutorial, you first need to get your own copy. Click the _Fork_ button in the top-right corner of the screen, and select your private account in the window that pops up. GitHub will create a forked copy of the repository under your account.

Clone the forked repository to your computer with the `git clone` command

```console
git clone git@github.com:YourUsername/data-version-control.git
```

Make sure to replace `YourUsername` in the above command with your actual GitHub username.

Happy coding!


Set the remote storeage with
dvc remote add -d $NAME $URL
here -d sets $NAME as the default storage


dvc add does three things
1: Adds the target to .gitignore
2: creates the target.dvc file
3: copies the target to staging area

the target.dvc files point to the files in the remote storage
