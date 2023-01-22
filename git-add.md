# git add -p

### Want to write meaningfull git message for all chunks of code 
### Or don't want to stage few lines of code
<br>
<img src= "https://www.google.com/url?sa=i&url=https%3A%2F%2Fcupofcode.blog%2Fintro-to-git%2F&psig=AOvVaw2_riT2_dfi4LgxZOOFdYRp&ust=1674450717820000&source=images&cd=vfe&ved=0CA8QjRxqFwoTCPjRrpS12vwCFQAAAAAdAAAAABAh" height = 300 width = 400>
<br>

The git add -p command is used to add changes to the staging area in a more granular way. The -p option
stands for "patch" and it allows you to interactively review and select specific changes that you want to stage.

When you run git add -p, Git will present you with a series of chunks of changes, one at a time, and
prompt you to choose what to do with each chunk. You will have the following options:

- y: stage this chunk of changes
- n: do not stage this chunk of changes
- q: quit the interactive patch selection process
- s: split the chunk into smaller chunks
- e: manually edit the chunk

This is a useful feature when you're working on a feature or bugfix that has multiple changes and you
don't want to stage all the changes at once. For example, you may have added debugging code or commented
out code that you don't want to commit yet. With git add -p you can review the changes before adding them
to the staging area, so you can be sure that you're only adding the changes that you intend to commit.

It is also helpful when you're working on multiple branches, it allows you to stage changes that are
specific to a branch, so you can easily switch between branches without committing changes that are not
related to that branch.


