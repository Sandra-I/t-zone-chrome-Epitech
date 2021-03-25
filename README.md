# T-Zone README

## HOW TO CLONE THE MAIN PROJECT

Please follow theses instructions to clone properly the repository.
The project is composed by a main repository (t-zone-chrome) with 2 submodules (interface and python-api).
A submodule is a reference to an other repository.

Git commands :
```
git clone git@gitlab.com:t-zone/t-zone-chrome.git
git submodule init
git submodule update
```

## SUBMODULES WORKFLOW EXAMPLE

Comment organiser son travail avec les submodules

Commands :
```
cd <TO THE SUBMODULE>
git checkout -b <BRANCH NAME>
```

Faire les modifications souhaitées dans le dossier.
Une fois que vous souhaitez, publier votre travail en ligne voici les étapes à suivre.

Commands :
```
git status
git add <FILE NAME>
git commit -m "<YOUR COMMIT MESSAGE>"
git branch

cd ..
git status
git add <.>
git commit -m "<YOUR COMMIT MESSAGE>"
git push
```
