From the Git Cheat Sheet:
Install git
GitHub for Windows: https//windows.github.com
GitHub for Mac: https://mac.github.com

Git for All Platforms:
http://git-scm.com

CONFIGURE TOOLING:
$ git config --global user.name "[name]"
sets the name you want attached to your commit transactions
$ git config --global user.email "[email address]"
sets the email you want attached to your commit transactions

CREATE REPOSITORIES!
make them from scratch:
$ git init [project-name]
download a project and its version history to contribute to a shared project that already exists:
$ git clone [url] 
     you can find the url on GitHub! Woohoo!
     
MAKE CHANGES
Review edits and craft a commit transaction
$ git status
if you type this into your terminal, it will show all new or modified files to be committed (within the directory you are in!)
$ git diff
shows the differences not yet staged (meaning changes you've done on your computer (origin) and have not yet put into the master version (the one on GitHub!))
$ git add [file]
snapshots the file in preparation for versioning
$ git reset [file]
unstages the file, but preserves its contents (takes it back so you can fix it! backsies!)
$ git commit -m "[descriptive message]"
Records file snapshops permanently in version history
Git is great because it won't let you commit without saying why. That message is KEY! you must label your changes!
