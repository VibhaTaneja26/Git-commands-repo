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

9) How to tell which branch we are in - " git branch"


10) how to push local git repository to git hub

a) First create git repository in github.
b) create origin in local
       "git remote add origin "URL HTTPS/SSH"   "
       "Git branch -m main"
       "git push origin main"

       to update origin-  "git remote set-url origin "URL"


11) hoe to bring git repo from github to local.
if repo is not just there in local then we can clone.

"git clone "URL"   URL - it is HTTPS 

12)How to put new changes from github(remote) to local

"git pull"

13) how to create ssh key pair
 go to ssh folder " cd .ssh"
 "ssh-keygen"

copy public key and put in github "setting-SSH keys- create new key and copy this public key there" 







