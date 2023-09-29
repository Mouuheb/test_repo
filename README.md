# test_repo
this is test repo

# clean version

# git help
mouheb@DESKTOP-GTB441P MINGW64 ~
$ git -h

# clean the cmd
mouheb@DESKTOP-GTB441P MINGW64 ~
$ clear

# configure username and email
mouheb@DESKTOP-GTB441P MINGW64 ~
$ git config --global user.name "mouuheb"

mouheb@DESKTOP-GTB441P MINGW64 ~
$ git config --global user.email "mouhebhatiwch101@gmail.com"

# create repo
mouheb@DESKTOP-GTB441P MINGW64 ~
$ git init "git project"

# know the directery
mouheb@DESKTOP-GTB441P MINGW64 ~
$ ls

# enter into the project
mouheb@DESKTOP-GTB441P MINGW64 ~
$ cd "git project"

# see the hiden file
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ ls -a

# know your status
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git status

# create file with cmd
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ touch index.html

# add the file to the stage
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git add index.html

# add the file to the repo
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git commit -m"Create index.html"

# know the history of the repo
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git log

# go back to the last version
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git checkout f07f113100c63e272e9938c6040559568a588fd8

# know the branch
mouheb@DESKTOP-GTB441P MINGW64 ~/git project ((429a0d8...))
$ git branch

# change your branch
mouheb@DESKTOP-GTB441P MINGW64 ~/git project ((429a0d8...))
$ git checkout master

# create now branch
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git branch secound

# mix your curent branch with an other branch
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git merge secound

# see your sourse
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git remote -v

# link your repo to github
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git remote add origin https://github.com/Mouuheb/test_repo.git

# push your repo to github 
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git push -u origin master

# update your repo
mouheb@DESKTOP-GTB441P MINGW64 ~/git project (master)
$ git pull origin master
