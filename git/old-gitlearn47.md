
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄     
══════════════════════════════════════════    
git Notes from vagrant leanrning page  https://github.com/sjcode236/puppet/blob/master/git-vagrantNotes.py     
 

```
===download and install Git-2.18.0-64-bit 
https://git-scm.com/downloads      ==(download from here)
during installation select 
"Use Git and optional Unix tools from the windows Command prompt"
then launch git bash  
start->git->git bash
```   
```
-create a folder -> right click on it -> Git bash here
   touch index.html
   touch app.py
    git init
    git config --global user.name  "lenov lap"
    git config --global user.email "sjbuy25@gmail.com"
    git add  
    git index.html
    git *.html
    git status
    git rm --cached index.html
    git status
    git add .
vi index.html  (add  some text)
git commit -m 'changed  index.html'
```

```
git branch login
$ git checkout login
Switched to branch 'login'
git status
touch login.html ( add some text)
git add .
git status
git commit -m 'login form'
git checkout master
git branch   -->  to see  what branch on now 
git merge login -m 'merging the login branch'
```
```
=====git with github===
on github.com create a repo 'Gitapp1'
echo "# Gitapp1" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/sjcode236/Gitapp1.git
git push -u origin master
```
```
mkdir dir1
mkdir dir2
git commit -m "adding dir1 dir2"
git push
Now all the files will be on github.come
make a change to index.html  on github then
git pull -> will update all local file
```
```
to clone 
git clone https://github.com/sjcode236/Gitapp1.git
```
===install git on centos linux =====     
```
yum install git
git --version
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list
	user.name=Your Name
	user.email=you@example.com

# Set the cache to timeout after 1 hour (setting is in seconds)
git config --global credential.helper 'cache --timeout=3600'
git push origin master 
```
============================    
```
***TO see all branches
git branch --all

***TO see on which branch  now checkout to
[root@puppetmaster envAnirban2]# git branch
  master
  production
  staging
* test

***To delete  remote branch at  github  
git push origin --delete  staging   
```

```
***Deleting a local branch:
git branch --delete <branch>
git branch -d <branch> # Shorter version
git branch -D <branch> # Force delete un-merged branches
***Deleting a local remote-tracking branch:
git branch --delete --remotes <remote>/<branch>
git branch -rd <remote>/<branch> # Shorter
git branch -rd  origin/staging

git fetch <remote> --prune # Delete multiple obsolete tracking branches
git fetch <remote> -p      # Shorter
***Note that this removes all obsolete local remote-tracking branches for any remote branches that no longer exist on the remote:
```




