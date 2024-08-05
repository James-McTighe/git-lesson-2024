# Git Lesson

This lesson covers the basics of git for version control.

This lesson is for the first day of the MSSE bootcamp (Chem 280).

To make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make Changes to your projec that you would like to keep.
2. When you have your changes, tell `git` you are ready to create a checkpoint of the file using the `git add FILENAME` command.
3. Create a checkpoint of your file using `git commit -m "message about what you did"`.

## Adding features

features should be developed on branches.
To create and switch to a branch, use the commmand.

`git switch -c NEW_BRANCH_NAME`

to switch to an existing branch, use

`git switch BRANCH_NAME`
