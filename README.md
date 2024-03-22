### Step-by-step instructions on how to create GitHub repository for 'new-project'.

1. Create local repository
    1. Create directory\
       `mkdir new-project`
    2. Move into directory\
       `cd new-project`
    3. Create empty repository\
       `git init`
    4. Set user name\
       `git config user.name "Your Name"`
    5. Set user email\
       `git config user.email "your_email@example.com"`
    6. Create README.md\
       `touch README.md`
    7. Update README.md\
       `nano README.md`
    8. Add file to index\
       `git add .`
    9. Commit file with message\
       `git commit -m 'init'`
    10. Сreate and switch to the 'development' branch\
        `git checkout -b development`
    11. Update README.md\
        `nano README.md`
    12. Add file to index and commit file with message\
        `git commit -am 'update README.md'`
    13. Move on main branch\
        `git checkout main`
    14. Merge branch developer to main\
        `git merge developer`
    15. Check repository status\
        `git status`
    16. Make final commit\
        `git commit -am 'finish creation'`
2. Create repository on github\
    1. Open a web browser and go to https://github.com;
    2. Sign in to your GitHub account if you're not already signed in;
    3. On the GitHub page, move to "Repositories" and click the "New" button in the upper right corner;
    4. Enter the name of the repository 'new-project' in the "Repository name" field;
    5. Choose Public visibility of the repository;
    6. Click the "Create repository" button at the bottom of the page;
3. Push an existing repository to github\
   `git remote add origin https://github.com/lytvynov-kostiantyn/new-project.git` \
   `git branch -M main` \
   `git push -u origin main` 