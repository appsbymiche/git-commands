# git-commands
Just a reference for GIT commands

Create a branch from main branch. We will create a branch called "dev" from main branch

1. 'git checkout main'
2. 'git pull origin main'
3. 'git branch dev'


Adding commit changes and push. For reference we will use the branch name dev

1. After saving you changes. Open git bash and enter "git add ."
2. Enter 'git commit -m "Describe what you changed in dev".
3. 'git push -u origin dev'


Steps to merge your add your dev changes to your main branch

1. 'git checkout main'
2. 'git pull origin main'
3. 'git merge dev'
4. 'git push origin main'
