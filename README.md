#Welcome to the Git Tutorial Sandbox Repo
Feel free to do whatever you like!

##Git Bash Instructions

###Step 0:
- [Download Git](https://git-scm.com/).

- Open Git Bash

###Step 1:

Clone the repo.
```
git clone https://github.com/SaddlebackCSS/Git_Tutorial.git
```

###Step 2:
Change directory into the newly cloned repo
```
cd Git_Tutorial
```

###Step 3:
Make some changes.

###Step 4:
Add newly created files:
```
git add <filename>
```

Add only changes to files already on the repository
```
git add -u
```

Add all changes (regardless of new file or not):
```
git add -A
```

Check status of staging area:
```
git status
```

View log of commits:
```
git log
```

###Step 5:
Create your commit:
```
git commit -m <your commit message>
```

###Step 6:
Pull changes (just in case):
```
git pull
```

Push your changes (yay!):
```
git push
```


For more information:
[Git Documentation](https://git-scm.com/documentation)