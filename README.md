# Introduction to Git and Github

## Git Basic Commands
 
### Angular Commit Type 

Must be one of the following:
- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- **ci**: Changes to our CI configuration files and scripts (example scopes: Circle, BrowserStack, SauceLabs)
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **perf**: A code change that improves performance
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **test**: Adding missing tests or correcting existing tests

# Git reset and undo changes
- git reset --soft <commit>: Keep changes in the staging area, this can help  
to combining multiple commit into one or rename our commit message  
- git reset --mixed <commit>: Commits changes to working directory, this can  also help us to reorganize changes before commiting our code
- git reset --hard <commit>: Delete all uncommited, ATTENTION: Changes are lost forever, use it if you add by mistake some secrets (like hardcode password or api key, or token...) in your code, recommanded methode is to delet definitly that branch and recreate 

# Excercise:
- first move to local main branch and pull latest code 
- Add /create a new branch.
- add 3 commits and use `git reset --soft` to combine that into one comit 
- Explain git `reset --soft`
