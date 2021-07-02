# *task1.1*

* ## Change my global configs
![before-fix](/images/change_user_email.png)
* ## Create new private repo on GitHub
![before-fix](/images/git_repo.png)
* ## The list of commands that I executed to do this task
```
git clone git@github.com:vi140584ovn/DevOps_online_Vinnytsia_2021Q2.git
cd DevOps_online_Vinnytsia_2021Q2
mkdir task1.1
cd task1.1
touch readme.txt
git add .
git status
git commit -m "add readme.txt"
git checkout -b develop
touch index.html
git add .
git commit -m "add index.html"
git checkout -b images
mkdir images
cd images/
wget https://www.epam-group.ru/etc/designs/epam-core/images/common/logo.png
cd ..
git add .
git status
git commit -m "add image"
vim index.html 
git add .
git commit -m "change index.html"
git checkout develop
git checkout -b styles
mkdir styles
cd styles/
vim main.css
cd ..
git add .
git commit -m "add style file"
vim index.html 
git add .
git commit -m "chnage index.html"
git checkout develop
git merge images
git merge styles
vim index.html 
git status
git commit -m "fix conflict"
git add .
git status
git commit -m "fix conflict"
git checkout master
git merge develop
git log
git log --help
git push origin --all
git reflog > task1.1_GIT.txt
git add task1.1_GIT.txt 
git commit -m "add task1.1_GIT.txt"
git push
```

### index.html before fix
![before-fix](/images/before_fix.png)

### index.html after fix
![after-fix](/images/after_fix.png)

* ## What DevOps is? 

DevOps is an integration of specialist for development, 
testing and exploitation in order to provide a quality product. 
To be short, it is a set of tools and commands for effective organization to create and update program services and products. 1234
