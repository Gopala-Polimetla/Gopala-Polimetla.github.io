---
layout: page
title: Github
permalink: /github/
---
### What is GIT ?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Git allows and encourages you to have multiple local branches that can be entirely independent of each other. The creation, merging, and deletion of those lines of development takes seconds.


#### Difference between Git and GitHub

> - Git is an open-source tool developers install locally   to manage source code.
> - GitHub is an online service to which developers who use Git can connect and upload or download resources.

### Follow the steps to SignUp for GitHub free account.

Please follow below stepts to SignUp for the GitHub.

-  Open [https://github.com/](https://github.com/), enter your email id as shown in the below diagram and click on continue.

![singup Image](./images/signup1.png)

-  Enter password and username of your choice as shown in the below diagram.

![singup Image](./images/signup2.png)

-  provide the option for product update y/n and click on start puzzle to verify the account and click on create account .

-  Enter the GITHUB launch code received to your email id .

-  Select **team size** of your choice and select **Student** and click on continue as shown in the below image.

![singup Image](./images/signup3.png)

-  Select all the features and click on continue as shown in the below image.

![singup Image](./images/signup4.png)

-  Slect the Free subscription and click on Continue for free as shown in the below image.

![singup Image](./images/signup5.png)

### GitHub Commands

| Syntax             | Description     |
| ------------------ | --------------- |
| git --version      | This command will tell<br> you the version of Git you installed |
| git init           | Git initialization |
| git add            | Add file contents to the index |
| git status         | Will Show the working tree status|
| git diff           | Show changes between commits, commit and working tree, etc |
| git commit         | Record changes to the repository |
| git rm             | Remove files from the working tree and from the index |
| git mv             | Move or rename a file, a directory |
| git clone          | Clone a repository into a new directory |
| git branch         | List, create, or delete branches |
| git checkout       | Switch branches or restore working tree files |
| git switch         | Switch branches |
| git merge          | Join two or more development histories together |
| git log            | Show commit logs |
| git stash          | Stash the changes in a dirty working directory away |
| git tag            | Create, list, delete or verify a tag object signed with GPG |
| git pull           | Fetch from and integrate with another repository or a local branch |
| git push           | Push the changes/Updates to remote repository |
| git ls-files       | Show information about files in the index and the working tree |


#### Basic Interview questions

1. What is Git ?

    Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

    Git allows and encourages you to have multiple local branches that can be entirely independent of each other. The creation, merging, and deletion of those lines of development takes seconds.

    Unlike the other systems, Git has something called the "staging area" or "index". This is an intermediate area where commits can be formatted and reviewed before completing the commit.

    [Git Official Document](https://git-scm.com/book/en/v2)

2. What is Git Merge ?

    The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.

    Note that all of the commands presented below merge into the current branch. The current branch will be updated to reflect the merge, but the target branch will be completely unaffected. Again, this means that git merge is often used in conjunction with git checkout for selecting the current branch and git branch -d for deleting the obsolete target branch.

    Git merge will combine multiple sequences of commits into one unified history. In the most frequent use cases, git merge is used to combine two branches. The following examples in this document will focus on this branch merging pattern. In these scenarios, git merge takes two commit pointers, usually the branch tips, and will find a common base commit between them. Once Git finds a common base commit it will create a new "merge commit" that combines the changes of each queued merge commit sequence.

    [Git Official Document](https://www.atlassian.com/git/tutorials/using-branches/git-merge)


