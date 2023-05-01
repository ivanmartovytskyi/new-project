# README

1. Create new dir "new-project":
> mkdir new-project
 
2. Switch to dir "new-project":
> cd new-project/

3. Init new repository for "new-project":
> git init

4. Create README.md and add initial text(use your prefered editor):
> nano README.md

5. Stage README.md:
> git add README.md

6. Commit changes:
> git commit -am "init"

7. Create "development" branch:
> git checkout -b development

8. Add instructions to README.md and commit changes:
> nano README.md
> git commit -am "changed README.md"

9. Add changes from "development" to "main":
> git checkout main
> git merge development

10. Check status:
> git status
 
11. Add remote repository:
> git remote add origin git@github.com:yourname/new-project.git

12. Upload changes to repository:
> git push --set-upstream origin main
