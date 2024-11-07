## Quick note on windows cmd lines
| Command   | Description                       | Example           |
|---------- |----------                         |----------         |
| `cd`        | changing file directory           | cd mafolder       |
| `touch`     | creating a file                   | touch mafile.html    |
| `rm`        | removing a file                   | rm mafile.html    |
| `mkdir`     | creating a directory              | mkdir mafolder    |
| `rmdir`     | removing a directory              | rmdir mafolder    |
| `ls`        | listing items in the directory    | listing           |

[**Download Git Here**](https://git-scm.com/)  
Check if the installment suceeded.

## Set up your account
| Command   | Description                       | Example           |
|---------- |----------                         |----------         |
| `git config --global user.name`        | set up your name for every repository in the future           | git config --global user.name "maname"       |
| `git config --global user.email`        | set up your email for every repository in the future    | git config --global user.email "maemail@mail.com"           |

Remove `--global` to just setup identity in that repository.

## Git Cheat Sheets
| Command   | Description                       | Example           |
|---------- |----------                         |----------         |
| `git init`        | initializing git repository           | git init       |
| `git status`        | check on what you are on currently           | git status       |
| `git add`     | to save the file in record in staging area  [use "." for all files]                   | git add mafile.html    |
| `git commit -m`        | to save it in memory [-m for message or title]                   | git commit -m "this is mamessage"    |
| `git log`     | to see logs [type q for exiting log page]              | git log    |
| `git checkout`     | to bring back a file from previous commit [uses the hashed lines from the log]              | git checkout c961efbe8ea66a7ce5d6cc147794dead75e068c2     |
| `git checkout`     | checkout can also switch to other branch              | git checkout mabranch     |
| `git add README.md`        | adds a README.md file to your repository [create README.md with touch first]    | git add README.md           |
| `git branch`        | checking what branch you are right now [`*` means you are currently there]    | git branch           |
| `git branch`        | creating branch    | git branch mabranch           |
| `git branch -m`        | renaming current branch [recommended to use main as your default branch]    | git branch -m mabranch           |
| `git merge`        |merging a specific branch after the command to your current branch    | git merge mabranch           |
| `git branch -d`        | deleting a specific branch after the command [deleting a repository that has been merge will keep your workspace clean]    | git branch -d mabranch           |
| `git remote add maremote`        | setting the repository to place our pushed codes    | git remote add origin https://github.com/rd0lph/gitlearning.git           |
| `git push maremote`        | pushed a branch to the repository branching    | git push origin mabranch           |
| `git pull maremote`        | pulls the branch to your device    | git pull origin mabranch           |

## Git + GitHub Cheat Sheets
| Command   | Description                       | Example           |
|---------- |----------                         |----------         |
| `git fetch maremote` | notifies user with new commits or branches| git fetch origin|
|`git status` | gives more information about what has changed in the remote | git status|
|`git log maorigin/mabranch` | gives more information again | git log origin/master|
|`git diff maorigin/mabranch`| gives comparison between other remote with your current remote| git diff origin/master|
|`git merge maorigin/mabranch` | merge current branch with the specified branch | git merge origin/master|
|`git pull maorigin` | combination of fetch and merge, pulls the whole remote repository to your current branch| git pull origin|
|`git branch -a` | checks on your local and remote branches | git branch -a|
|`git branch -r` | checks on your remote branches only | git branch --r|

