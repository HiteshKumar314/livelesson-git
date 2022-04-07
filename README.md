- `git init`: initialize current folder as a git repository
- `git clone <URL>`: brings the git repo from <URL> to current folder
- `git status`: tells us what we need to know about our repository

- `git add <FILE>`: adds <FILE> to the staging area
- `git commit`: open a text editor to write commit message
    - `git commit -m "MESSAGE"`: writes MESSAGE as a commit without a text editor

- `git log`: shows the log (history) of our commits
    - `git log --oneline`: shows the shorter oneline commit

- `git diff`: compare current uncommited state with last known git state
    - `git diff --staged`: runs git diff between the staging area and last known state
- `git diff HEAD~<NUMBER>`: compares HEAD with commit <NUMBER> ago (relative)
- `git diff <HASH>`: compare HEAD with the comit in <HASH>

- `git restore --source <HASH or HEAD~> <File>`: restore file to <HASH or HEAD~>
    - `git checkout <HASH or HEAD~> <FILE>`: restore file to <HASH or HEAD~>
    - `git checkout <HASH or HEAD~>`: if you forget the file you end up in dteached HEAD state
    - `git checkout main`: go back to main
    - `git switch main`: go back to main 
