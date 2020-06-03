# echo-star-to-dot-gitignore

This is a nice 'trick' or 'hack' I'm using often <!--(all the time)--> when I have a folder I want to ignore inside the repo, but don't want to add a line in the global .gitignore file.
It is useful remedy in the middle of rebase or merges, but could be for temporary files, note taking, todos, big data folders etc.

So, without further ado - run this from your new temporary folder:
```
echo "*" > .gitignore
```
