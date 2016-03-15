# git-training

## Git

###  Create a Repository  

```` 
git init
````

###  Clone a Repository  
````
git clone https://github.com/AuthorizeNet/sdk-java.git
````

### Git Config
````
git config -l  
````
````
git config --add user.email=bmcmanus@visa.com 
````
  
Edit .gitconfig  

````
user.name=brianmc
user.email=bmgtech@gmail.com
http.proxy=http://internet.visa.com:80
https.proxy=http://internet.visa.com:443
````

### Add a file  
````
git add test-brian.txt
````

### Git Status
*** The most used command ***
````
git status
````

### Commit a file
```` 
git commit -a -m "Committing this change"
````

## Remotes (GitHub/Stash/etc)  

### Forking a Repository  

https://github.com/brianmc/git-training  
  
### Cloning a Repository
````
git clone https://github.com/brianmc/git-training.git
````

### Making changes
````
git status
git commit -a -m "Committing this change"
````
### Undoing changes
````
git checkout -- <filename>
````
````
git fetch origin
git reset --hard origin/master
````

### Pushing Changes to your fork
````
git push origin master
````

### Making a Pull Request


### Branching

````
git checkout -b newfeaturebranch
git checkout master
git checkout newfeaturebranch
````
Make some changes in newfeaturebranch
```
git diff master newfeaturebranch
````
git checkout master
git merge newfeaturebranch
````





