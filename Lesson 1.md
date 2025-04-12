
===========================================================================================================

#Git Commands

git init: "Creates a new Git repository"

git status: "Inspects the contents of the working directory and the staging area"

git add: "Adds the files from the working directory to the staging area."

git diff: "Shows the difference between the working directory and the staging area"

git commit: "Permanetly stores file changes from the staging area in the repository"

git log: "Shows a list of all previous commits"

===========================================================================================================

Other snippets from GitHub:

1st: #Code to set up this repository on your desktop/laptop using either HTTPS or SSH.

<span>git@github</span>.com:TheKingOfAncients/Git-Hub-Training-Part-1-.git


===========================================================================================================

2nd: #Script to create a new repository from the command line.

echo "# Git-Hub-Training-Part-1-" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin <span>git@github</span>.com:TheKingOfAncients/Git-Hub-Training-Part-1-.git

git push -u origin main


===========================================================================================================

3rd: #Script to push an existing repository from the command line.

git remote add origin <span>git@github</span>.com:TheKingOfAncients/Git-Hub-Training-Part-1-.git

git branch -M main

git push -u origin main



===========================================================================================================

Tip:
- One shoudl **keep** the URL created at the beginnging of the formation of the repository.
- This is becase of the fact that it can be placed into remote system to connect to it.



===========================================================================================================




From Codecademy: 

![image](https://github.com/user-attachments/assets/8fc1d048-09bb-4ffa-9d67-e4f0bd77940f)
