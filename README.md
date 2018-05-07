# sublime-text-settings
Backup Sublime Text settings

## Setup on new machine
1. Install Sublime Text
2. Install Package Control
3. Clone repository
    ```
    cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/
    git init
    git remote add origin https://github.com/<github name>/<repo name>.git
    rm Package\ Control.sublime-settings
    git fetch
    git checkout --track origin/master
    ```
