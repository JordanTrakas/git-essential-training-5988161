# Reverting Commit Notes

- I am committing this line

I was having trouble reverting something so I asked Copilot about it. Here is the response.

📝 What happens when you run git revert -s 60c5729
Git creates a new commit that undoes the changes from commit 60c5729.

Before finalizing, it opens the Vim editor so you can edit the commit message.
If you don’t know how to exit Vim properly, Git thinks you canceled or failed the revert.

🚪 How to exit Vim and save the revert message
Inside Vim:
- Press Esc (to make sure you’re not in insert mode).
- Type :wq and press Enter. :wq means write (save) and quit.
- Git will then finish the revert and create the new commit.

Other useful commands:
:q! → quit without saving (aborts the revert).
i → enter insert mode if you want to edit the message.
Esc → leave insert mode.

ALTERNATIVE WAY:
git revert -s 60c5729 -m "Revert commit 60c5729"