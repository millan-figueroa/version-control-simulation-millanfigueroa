First I created a main branch and pushed index.html with boilerplate code.
Then created a header feature branch and added header code, commited, and pushed to that branch.
Switched back to main and created a feature/footer branch. Added footer code, then committed and pushed to that branch.
Next, I switched back to my header branch. I added a footer to create a merge conflict. This time i committed, then switched back to main without pushing.
Once back on main, I tried merging the footer branch and got an error saying "Auto-merging index.html
CONFLICT (content): Merge conflict in index.html
Automatic merge failed; fix conflicts and then commit the result."
At this point I was able to fix the merge conflict using the merge editor. Accepted incoming changes, then committed.
Next I pushed everything to main.
Created readme.md, committed and pushed to main.
I notice I am seeing compare & pull request button when im on main branch on the remote repo.
