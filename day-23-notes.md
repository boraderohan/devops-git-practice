## Task: Understanding branches 


1)What is branch in Git?

Ans: Git branch is a separate workspace used to make changes without affecting the main project.

Once the work is complete, the changes can be merged back into the main or master branch.

2)Why do we use branches instead of committing everything to main?

Ans: Working on a branch keeps your experimental or incomplete changes separate from the main codebase.

If something goes wrong -like a bug or a failed feature- you can discard the branch without affecting the stable main branch.

3)What is HEAD in Git?

Ans: HEAD is a reference to the current check-out commit in your repository.

It is basically a pointer or symbolic reference to the latest commit in your branch.

Every time you swithch branches or check out a specific commit, HEAD moves accordingly to point the relevant commit.

4)What happens to your files when you switch branches?
Ans: When you switch branches in Git, your working directory files are automatically updaed to match the target branch's latest commit.

If you have uncommited changes that conflict with commit them first.

5)What is the difference between origin and upstream?

Ans: Origin: The default name for the remote repository you cloned from your repo on GitHub 
Upstream: A conventional name for the original source repository you forked from. 
It is not set automatically, you add it manually.
