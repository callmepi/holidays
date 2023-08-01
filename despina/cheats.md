# A simple cheat-sheet for GIT
----

## Glossary

_`Branch`: Branches represent soecific versiond of a repository that "branch out" from the main project._ 

_`Commit`: A commit represents a specific point in your project history._ 

_`Checkout`: Use the git checkout sommand to switch between branches._ 

_`Origin`: The origin refers to the default version of a repository. Origin also serves as a system alias for communicating with the master branch._ 

_`Pull`: Pull requests represent suggestions for changes to the branch that we work on it._ 

_`Push`: The git push command is used to update remote branches with the latest changes you or your team'members have commited._ 



## Commands

- _only the most important/basic commands_

> __``git init``__:
> Create an empty repository in the project folder

> __``git status``__:
> Display the status of modified files.

> __``git add .``__:
> Add all directory changes to staging.

> __``git log``__:
> Show the history of changes.

> __``git checkout <sub>[branch-name]</sub>``__:
> Switch to a branch.

> __``git checkout -b <sub>[branch-name]</sub>``__:
> Make a new branch and switch to it.

_is the same as .._
> __``git branch <sub>[branch-name]</sub>``__
> Make a new branch and switch to it.

> __``git branch``__:
> Display a list of all branches.

> __``git branch <sub>[branch-name]</sub>``__:
> Make a new branch and switch to it.

> __``git branch -d <sub>[branch-name]</sub>``__:
> Delete a branch.

> __``git merge <sub>[branch]</sub>``__:
> Merge a different branch with your active branch.

> __``git push``__:
> Push changes to origin.

> __``git pull``__:
> Retrieve the most recent changes from origin and merge.

> __``git commit [-m] <sub>"message"</sub>``__:
> Commit changes along with a custom message.
