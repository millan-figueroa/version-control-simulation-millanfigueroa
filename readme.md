1. Created a **main** branch and pushed `index.html` with boilerplate code.
2. Created a **header** feature branch, added header code, committed, and pushed to that branch.
3. Switched back to **main** and created a **footer** feature branch. Added footer code, then committed and pushed to that branch.
4. Switched back to the **header** branch. Added a footer to intentionally create a merge conflict, committed, then switched back to **main** (without pushing).
5. On **main**, tried merging the **footer** branch and got an error: Auto-merging index.html
   CONFLICT (content): Merge conflict in index.html
   Automatic merge failed; fix conflicts and then commit the result.
6. Fixed the merge conflict using the merge editor, accepted incoming changes, and committed.
7. Pushed everything to **main**.
8. Created `README.md`, committed, and pushed to **main**.
9. Noticed the **Compare & Pull Request** button when on the remote repo’s main branch. Once i finished the first version of the readme, i did a 'git push -u origin main' and the 'compare & pull request' button disappeared.
