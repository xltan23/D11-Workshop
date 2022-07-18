# Workshop 11 Instruction

### Maven commands
1. mvnw
2. mvnw compile
3. mvnw package
4. mvnw clean package
5. mvnw clean
6. mvnw clean package spring-boot:run (remove all packages and repackage them and run local web server)
7. mvnw spring-boot:run

### Git commands
git init

git remote add origin https://github.com/xltan23/<projectname>.git

git add *

git status

git commit -m "message details"

git push -u origin master

git pull

git branch -a

git checkout -b develop master (Switch to develop branch)

git commit -m "" (Add to develop branch)

git push -u origin develop (push to remote git develop branch)

### Working in develop branch

git checkout master

git merge develop (merge changes done in develop branch into master branch)

git push -u origin master 

// Make changes in master, and need to synchronise change to develop branch
git checkout develop

git merge master (merge changes done in master branch into develop branch)

git push -u origin develop