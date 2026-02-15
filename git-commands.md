Git Hub Commands

1)Connect to server- “ssh -i key name or path to key user@Server name

ssh -i "Josh-Batch10-Super-key.pem" ubuntu@ec2-100-52-225-139.compute-1.amazonaws.com

2) Check for git version --  “ git --version”

3) if Git is not installed, install git.
a) update package-“ sudo apt-get update”
b) install git, “sudo apt install git”

4) now lets make git repository which is nothing but a folder
“mkdir git-repository”
Go in the folder and initialize git which means we are making this folder as git repository
“git init”

5) Check status in git
“ git status”.    
Note: this command will tell git status only if you are in git repository. (how to tell if it is a git repository- run “ls -a” and if it returns .git that means it is a git repository.

If you run command “ git status” in any other folder, it won’t tell git status.


6)Files stay untracked until you add and commit

“ git add”, “git commit -m ‘some message’”

7) to check logs “git log”

8)To create branch --- “git branch -b “give branch name”. 
Branches keep different version of files”










