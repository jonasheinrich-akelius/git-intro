## 2023-03-28

- checkout main
- pull the latest changes
- create your own branch in the git-intro repo
- find the latest commit in the log
- look at the latest commit (including the changes)
- create a textfile and enter something into it
- commit that file with a (meaningful ;) ) message
- find the commit in the log/history and look at the author etc
- change the textfile
- commit the changes
- change the textfile again
- amend the previous commit
- push your changes to the remote
- checkout main
- create yet another branch
- create a textfile with the same name but add different content
- commit it and push the branch to the remote
- go back to your first branch
- merge the second branch and push the changes to the remote (merge conflict should happen, solve it ;) )

## older

- Explain in pseudo code (that is: text) what is happening when a commit created
- How is a commit stored?
- Explain in pseudo code (that is: text) what is happening when you checkout a different branch
- Does it matter on which branch git fetch is called? What commands are independent from the branch they are called on?
- What params does fetch take?
- What is a remote?
- Why is there the branch dev and origin/dev?
- What branch gets updated by fetch and what by pull?
- How do you undo a change to a file?
- How do you switch a branch?
- Show the content of the last commit
- Show the history and read the last 3 commit hashes
- Show the content of the previous commit
- Show the content of the 3rd-previous commit
- Show all branches
- Show all branches including remote branches
- Create a local branch from a remote branch
- Checkout a commit from the history
- Create a branch from the 3rd-previous commit
- Remove a commit but leave the file changes there
    - Show the file changes
    - Commit only a part of the file changes
    - Remove the other file changes
- Cherry-pick a commit to a new branch



- Move a commit to a new branch
    - branch: split-me-into-two
    - Move change from test2.txt to "another-branch"
    - How does the history of another-branch look like
    - Move change from test.txt to "another-branch-2"
    - How does the history of another-branch-2 look like?
- Resolve merge conflict
    - branch: branch-with-conflict
    - Merge branch merge-me-softly
    - Keep all changes
- Undo a merge
    - branch: branch-with-merge
    - Revert the merge from merge-me-softly
