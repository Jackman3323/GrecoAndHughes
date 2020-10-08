# GrecoAndHughes
For Assignments

Q1 - What does clone set the variable origin to represent?

- Clone sets origin to represent the remote repository

Q2 - What does the command git push --set-upstream origin master do? What does remote tracking mean in this context?

- This command pushes whatever we've done locally to the origin repo on it's master branch. Upstream tracking means that we sort of tie the local master branch to the remote master branch so that the remote one tracks changes from the local one.

Q3 - Explain and illustrate what's happening in the commit tree when this command executes.

- This command pulls stuff from remote master, merges it with local master.

Q4 - Are your commits overwritten by the remote master?

- No, we don't think so. It merges instead of deletes.

Q5 - Is this a merge or a rebase?

- It is a merge bc the merge command is like part of pull.

Q6 - Person B: checkout the local master branch. Is it updated as well, or still behind remote master?

- Ok i did this local master was behind, I fixed it.

Q7 - Run git branch. Did your local copy of your branch delete when Person A deleted the remote branch? If not, delete the local copy of the branch using git branch -d BRANCHNAME

- Greco hereby confirms that he deleted extra branches.

Q8 - Use git log --graph --all to view the branching structure and copy and paste the result into the README.md formatted as a code segment (see markdown cheatsheet).

