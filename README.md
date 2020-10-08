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

*   commit aaf9448537700f3a8b41c8e123e38f4f9cdbe28a (HEAD -> master, origin/master)
|\  Merge: 5012366 0e7269c
| | Author: Jackman3323 <jhughes22@kentdenver.org>
| | Date:   Thu Oct 8 10:20:32 2020 -0600
| | 
| |     Merge pull request #3 from Jackman3323/Feature2
| |     
| |     Greco chose my feature and resolved conflict.
| |   
| *   commit 0e7269c24a84b52a0b02e4b58be6bfe0eb8e63f1
| |\  Merge: d6f08d1 5012366
| |/  Author: jgecko11 <jgreco22@kentdenver.org>
|/|   Date:   Thu Oct 8 10:20:14 2020 -0600
| |   
| |       Merge branch 'master' into Feature2
| | 
* | commit 501236660c57dfedac0de8ede53db414fb053d8c
| | Author: jgecko11 <jgreco22@kentdenver.org>
| | Date:   Thu Oct 8 10:17:29 2020 -0600
| | 
| |     testing for merge error
| | 
| * commit d6f08d199669181ebc71e25f14bb542b43105b38 (origin/Feature2)
|/  Author: Jackman3323 <jhughes22@kentdenver.org>
|   Date:   Thu Oct 8 10:17:46 2020 -0600
|   
|       Epic Feature added to TextFile
|   
*   commit 113d90c2cbfb440a46f984298b44ab3c5ca00c4d
|\  Merge: 4b216cf c418d7d
| | Author: Jackman3323 <jhughes22@kentdenver.org>
| | Date:   Thu Oct 8 10:11:41 2020 -0600
| | 
| |     Merge pull request #2 from Jackman3323/newBranch
| |     
| |     RESOLVED. Feature added to main.
| |   
| *   commit c418d7dee85e62d6cc1042e92ab238118622a2c5
| |\  Merge: 841f5b2 4b216cf
| |/  Author: jgecko11 <jgreco22@kentdenver.org>
|/|   Date:   Thu Oct 8 09:59:51 2020 -0600
| |   
| |       deleted
| | 
* | commit 4b216cfca3a965f85126025bc6c11bbee5a330fb
| | Author: Jackman3323 <jhughes22@kentdenver.org>
| | Date:   Thu Oct 8 09:51:17 2020 -0600
| | 
| |     Formatting
| | 
| * commit 841f5b29b1579f8ccf5e704db8ddbf31ce192f78
|/  Author: jgecko11 <jgreco22@kentdenver.org>
|   Date:   Thu Oct 8 09:54:33 2020 -0600
|   
|       new file
| 
* commit b8542a055d4dbbf6a0e799b4602f3a83a05d34d9
| Author: Jackman3323 <jhughes22@kentdenver.org>
| Date:   Thu Oct 8 09:49:14 2020 -0600
| 
|     Added TextFile.
| 
* commit b165e6b4a0f0cd13412e3569fa4ffc3feb12d12c
| Author: Jackman3323 <jhughes22@kentdenver.org>
| Date:   Thu Oct 8 09:42:04 2020 -0600
| 
|     Create README.md
| 
* commit 1dce8994f1ebad9fb18944eae0078e5149c6e423
  Author: Jackman3323 <jhughes22@kentdenver.org>
  Date:   Thu Oct 8 09:36:06 2020 -0600
  
      Initial Commit

