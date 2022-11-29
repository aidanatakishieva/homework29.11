# homework29.11
A gitignore file specifies intentionally untracked files that Git should ignore. Files already tracked by Git are not affected; see the NOTES below for details.
The purpose of gitignore files is to ensure that certain files not tracked by Git remain untracked.

To stop tracking a file that is currently tracked, use git rm --cached.

Git does not follow symbolic links when accessing a .gitignore file in the working tree. This keeps behavior consistent when the file is accessed from the index or a tree versus from the filesystem.
