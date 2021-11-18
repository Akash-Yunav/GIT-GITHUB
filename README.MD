# The Git is an Version Control Tool for Developers';

# Git & GITHUB are not the same, You can use GIT without GITHUB, but vice versa is not true;

# GITHUB is website that make tools which integrate with GIT

# GITHUB, BitBucket, & GitLAB are "remotes" for The GIT;

## Some Basic Command Line

- cd "folderName" : to access the folder present in current path
- cd.. : to move out of the current folder(dir)
- dir: to see folderList

## Creating a local GIT repository ( repo )

- git init : Initializes an empty git repository.

  Initialized empty Git repository in D:/DEVELOPER BOOST/GIT & GITHUB/.git/

- git add <file> : to add the file to the git repo
- git add . : to add all files to the git repo
- git status : to check the files which git is tracking(or present) in the git repo

  The commits haven't been made yet,"git add <file>" just add the files to the git repo, and leave them as "Changes to be commited"[which means they are about to be commited] so we will use "commit" command to commit our changes.

- git commit -m "defining the changes you made with this commit"

- git remote add origin https://github.com/Akash-Yunav/Curriculum-Authoring-Toolgit: adding GITHUB repo origin to push our local GIT repo to.
- git push -u origin master : pushing our local GIT repo to GITHUB Repo of above added origin.
