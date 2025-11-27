## Undo your changes

---
Sometimes we want to undo changes and go back to the previous commit.
Let's add this to the stage with *git add .* and then commit it.

- use "git restore --staged <file>..." to unstage. Note that the directory name is needed as well
- use "git restore --staged ." to unstage all files
- use "git restore ." to eliminate all changes

---

- **git log** shows all commit history. This is why it is important to write clear commit messages
- git log also allows the exploration of history
  - Copying the checksum (the long string) shows more details about specific commits
  - Press **Q** to exit the log without needing to scroll to the bottom
- **git show checksum** shows all changes that were made in a specific commit 
---
- **git log --oneline** shortens the log
- **git log --grep='<str>'** shows all the commits with files with that specific string
