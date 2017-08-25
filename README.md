 This repository contains the files used for a git lesson.
 This is a change to an existing file that git has already tracked.
 This is a third change to the file.
 Git is a version control system that prevents us from having the "final doc" problem.
 So far command git 
      1. git add <filename>
 					2. git commit -m "your messages here"
 					2.1 or just git commit the enter it will pop up sublime text then type message in there and save it all the same then close the sublime 
 					3. git log  to show the messages
 					3.1 git log --oneline to show one line  easy to read
 					4. in typo messages correct by 
 						$ git commit --amend -m "New and correct message"
 					5.git status to read so far we did and will show us a suggest
 					6. git add .  to add everything in shortcut way
 					7.git reset HEAD <file> to unstage
 					8.git diff to see different before commit and then to commit 
 					9.git help to see all commands
 					10.git diff --staged
 					11.git diff HEAD~<fill number stage behind like '4' and print stage all the way to 1 >
 					12. git diff <commit hash>
 					13. git checkout HEAD~1 README.md (delete the last commit line will longer there)   
 					14. git checkout master
 					15. use 'git checkout master README.md' to undelete file(s)
 					16. if git bash more log use arrow down until END and then 'q' to normal 
 					17.  git reset --hard  to removed stage area 
 					18. git reset <hash> <file name>
 					19. change to be comitted use git reset HEAD <file> to unstage
 					20. git push origin master ('origin' is arias name or short name for referring to remote  github  and 'master' is arias name or shor name for referring to local files )
