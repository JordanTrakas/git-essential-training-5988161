## Solving Merge Conflicts

- Merge conflicts are a common problem in git when multiple people work on the same file
- Example (creating and solving merge conflict):
  - Submit a change with a file in GitHub
  - Commit a change with git with the same filename
  - Git rejects the push and says that a pull must be performed before a push
  - Git says branches are divergent. There are three configurations to do this
    1. git config pull.rebase false # merge
    2. git config pull.rebase true # rebase
    3. git config pull.ff only # fast-forward only