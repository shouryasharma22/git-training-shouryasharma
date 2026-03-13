Commands-

git start save-your-work
git stash
(Now I manually fixed the bug in the file using nano and removing the line with the bug)
git add bug.txt
git commit -m "Fixed the bug"
git stash pop
echo "Finally, finished it!" >> bug.txt
git add bug.txt
git commit -m "Finished the work"
