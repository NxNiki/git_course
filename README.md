
# Resources:

## git online course
notes of git course on data camp：https://app.datacamp.com/learn/courses/introduction-to-git

## git guide:
https://rogerdudler.github.io/git-guide/

## book:
https://git-scm.com/book/en/v2

Git has three main states that your files can reside in: modified, staged, and committed:
- Modified: the file is changed but not committed to your database yet.
- Staged: you have marked a modified file in its current version to go into your next commit snapshot.
- Committed: the data is safely stored in your local database.


`git diff`: compares the working directory (Modified) with the staging area (Staged).

`git diff --staged`: compares your staged changes to your last commit.


`git commit -a -m 'Add new benchmarks'`: commit without adding files to the staging area.

`git rm <file>`: remove the file from the working directory. You will be able to commit this change. If you run `rm <file>`, the change is not added to the staging area.

`git rm -f <file>`: remove the modified file or file in the staging area.

`git rm --cached <file>`: remove files from the staging area but keep them in the working directory (hard drive).



