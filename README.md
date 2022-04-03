# T-Zone README

## HOW TO CLONE THE MAIN PROJECT

Please follow theses instructions to clone properly the repository.
The project is composed by a main repository (t-zone-chrome) with 4 submodules (interface, python-api, tzone-website and nestjs-api).
A submodule is a reference to an other repository.

Git commands :
```
git clone git@gitlab.com:t-zone/t-zone-chrome.git
git submodule init
git submodule update
```

## SUBMODULES WORKFLOW EXAMPLE

How to organize your work with submodules

Commands :
```
cd <TO THE SUBMODULE>
git checkout -b <BRANCH NAME>
```

Make the needed changes in the file.
Once you wish to publish your work online, here are the steps to follow.

Commands :
```
git status
git add <FILE NAME>
git commit -m "<YOUR COMMIT MESSAGE>"
git branch
git push

cd ..
git status
git add <.>
git commit -m "<YOUR COMMIT MESSAGE>"
git push
```

## HOW TO PULL THE PROJECT PROPERLY

```
git pull --recurse-submodules
```
