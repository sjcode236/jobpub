


🟣 The Ultimate GIT 5-day Challenge :- https://www.udemy.com/course/the-ultimate-git-5-day-challenge/    
🟣 Learn git concepts, not commands :-  https://dev.to/unseenwizzard/learn-git-concepts-not-commands-4gjc     
🟣 Learn Git Branching :- https://learngitbranching.js.org/   


Github  Example:-    
```
$ mkdir sfguide-terraform-sample && cd sfguide-terraform-sample
$ echo "# sfguide-terraform-sample" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin git@github.com:YOUR_GITHUB_USERNAME/sfguide-terraform-sample.git
$ git push -u origin main
```

▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄     
══════════════════════════════════════════   
git Not3es from vagrant leanrning from page    
https://github.com/sjcode236/puppet/blob/master/git-vagrantNotes.py          

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









