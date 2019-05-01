Steps to use git locally.

1. created directory in the terminal (mkdir gittest1)
2. cd into gittest1 and perform: git init.
3. touch some files (e.g. 'touch index.html')
4. add files to stage: git add . (dot is for all changed files)
5. commit changes: git commit -m "message between double quotes"

=====

Steps to connect local repository on my computer with Github.

1. Go to Github.com and sign in.
2. Create a new repository on GitHub.com and perform the second option mentioned (in your terminal): 
    $ git remote add origin git@github.com:username/new_repo
    $ git push -u origin master
4. your local repository is now connected to github!

