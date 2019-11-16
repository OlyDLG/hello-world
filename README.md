# hello-world
My hello-world github project
A little bit about myself

Notes from Learning Git

Observation/question: to participate in a group project, I will want to start by creating my own branch off of Master, yes?  Question: do I do this in the main repository, or do I clone the repository to my machine, and then branch Master on my machine?  
ANSWER: clone, then branch, then "checkout" to make that the working branch: From the [Handbook](https://guides.github.com/introduction/git-handbook/):

    # download a repository on GitHub.com to our machine
    git clone https://github.com/me/repo.git
    
    # change into the `repo` directory
    cd repo
    
    # create a new branch to store any new changes
    git branch my-branch

    # switch to that branch (line of development)
    git checkout my-branch

    # make changes, for example, edit `file1.md` and `file2.md` using the text editor

    # stage the changed files
    git add file1.md file2.md

    # take a snapshot of the staging area (anything that's been added)
    git commit -m "my snapshot"

    # push changes to github
    git push --set-upstream origin my-branch

What's the difference between the "Fork-and-Pull" model and the "Shared Repository" model?

