# Git Hooks

## Steps:
1. Create a new directory.
2. Open terminal and navigate to that directory.
3. Enter `git init`.
4. Create a "post-commit" file in `.git/hooks/`.
5. Inside the file enter the following bash script:  
    `#!/bin/bash`  
    `open https://www.ncsu.edu/`   
    `exit 0`  
6. Save and exit.
7. Give this file executive permission using `chmod +x .git/hooks/post-commit`.
8. Commit and see the post-commit hook in action!
9. Shell script is in file named `post-commit.sh`.

