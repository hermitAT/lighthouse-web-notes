### Lecture Notes

Working with git:
Remembers the history of our code, documents changes with commit messages, listing the authors of changes, etc.

`git init` creates a .git folder which enables that local repository and all the git information.

Working directory -> staging area -> local repo -> remote repo;

Staging area can be compared to an airlock within a spaceship, an intermediary area to ensure you are satisfied with the conditions before sending them out into space (the local repo).

`git add .` will add all files that have been changed to your staging area. Adding specific files can be called by reference.

`-m` is adding an inline message to your commits, without it you are brought to VIM and required to manually edit files. Don't forget your message!

`git push` will automatically confirm the defaults of `origin master`, so can be used as shorthand.

`git checkout -b "name"` will switch to a new branch and it will be given the name used with "name".

Pushing your work copies what you have on the local repository to the remote repository.

#### Incremental Code

Work closely with problem descriptions and add them as comments to enable readability and clarity.

Break a larger problem into sub-problems, and even create individual functions for each sub-problem.

##### process.argv

An array with two initial pieces containing the environement/program to be used on (ie. Node) and the file (ie. a sum-function.js). Additional pieces are added to the array when command line arguments are passed.

Can use `process.argv.slice(2)` to access the array of command line arguments ONLY. Best used when saved into a new variable (within an array).

`NaN` is `falsey` and can be used for `if ()` statements pretty easily.
