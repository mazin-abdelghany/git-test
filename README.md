# Odin Project Git testing
This is a test repository that was created while learning Git via the Odin project. This file was created and edited on my local machine and the command line was used to commit and push the changes to GitHub.

Testing Git via the Odin Project  

Hello Odin!

### Here are some useful Git commands
- Commands related to a remote repository:
	- `git clone git@github.com:USER-NAME/REPOSITORY-NAME.git`
	- `git push` or `git push origin main` (Both accomplish the same goal in this context)
- Commands related to the workflow:
	- `git add .`
	- `git commit -m "A message describing what you have done to make this snapshot different"`
- Commands related to checking status or log history
	- `git status`
	- `git log`  

The basic Git syntax is `program | action | destination`.

For example,  
- `git add .` is read as `git | add | .`, where the period represents everything in the current directory;  
- `git commit -m "message"` is read as `git | commit -m | "message"`; and
- `git status` is read as `git | status | (no destination)`.

### Here is a Git best practice
- Perform **atomic commits**&mdash;a commit that includes changes related to only one feature or task of your program.
	- if something you change turns out to cause some problems, it is easy to revert the specific change without losing other changes.
	- enables you to write better commit messages

### Changing the Git commit message editor
- `git commit` without an `-m` flag opens `nano` to write the commit message.
- The following command will make Visual Studio Code open a new tab with the ability to write the commit message and an optional description below it:
	- `git config --global core.editor "code --wait"`