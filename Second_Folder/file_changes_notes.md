## Undo your changes

---
Sometimes we want to undo changes and go back to the previous commit.
Let's add this to the stage with *git add .* and then commit it.

- use "git restore --staged <file>..." to unstage. Note that the directory name is needed as well
- use "git restore --staged ." to unstage all files
- use "git restore ." to eliminate all changes