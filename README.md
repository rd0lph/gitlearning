## Quick note on windows cmd lines
| Command   | Description                       | Example           |
|---------- |----------                         |----------         |
| **cd**        | changing file directory           | cd mafolder       |
| **touch**     | creating a file                   | touch mafile.html    |
| **rm**        | removing a file                   | rm mafile.html    |
| **mkdir**     | creating a directory              | mkdir mafolder    |
| **rmdir**     | removing a directory              | rmdir mafolder    |
| **ls**        | listing items in the directory    | listing           |
## Git Basic Cheat Sheets
| Command   | Description                       | Example           |
|---------- |----------                         |----------         |
| **git init**        | initializing git repository           | git init       |
| **git add**     | to save the file in record in staging area  [use "." for all files]                   | git add mafile.html    |
| **git commit**        | to save it in memory [-m for message or title]                   | git commit -m "this is mamessage"    |
| **git log**     | to see logs [type q for exiting log page]              | git log    |
| **git checkout**     | to bring back a file from previous commit [uses the hashed lines from the log]              | git checkout c961efbe8ea66a7ce5d6cc147794dead75e068c2     |
| **git add README.md**        | adds a README.md file to your repository [create README.md with touch first]    | git add README.md           |
| **git branch -m branchname**        | renaming current branch [recommended to use main as your default branch]    | git branch -m mabranch           |
| **git branch -m branchname**        | renaming current branch [recommended to use main as your default branch]    | git branch -m mabranch           |
| **git remote add origin https://github.com/profile/reponame.git**        | setting the repository to place our pushed codes    | git remote add origin https://github.com/rd0lph/gitlearning.git           |
| **git push origin branchname**        | pushed a branch to the repository branching    | git push origin mabranch           |
| **git pull origin branchname**        | pulls the branch to your device    | git pull origin mabranch           |