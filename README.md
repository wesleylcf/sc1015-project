# Important Notes

---

### Initial steps

refer to [github collaboration guide](https://medium.com/@jonathanmines/the-ultimate-github-collaboration-guide-df816e98fb67).
There will be one person assigned to review pull requests(changes to the project) before merging them to the remote git repository

### Branches

There are two branches, main and dev.
Only work on the dev branch.
Check the branch you are on using `git branch`
To switch to the dev branch use `git checkout dev`
With the exception of the above two branches, each branch should represent one feature.
For the purposes of this project, once you have checked-out to the dev branch you can create a new branch and checkout to it under dev following this convention:
git co -b dev feature/someFeatureYouAreWorkingOn

### Workflow

After making changes your project, run:

1. `git add .`
2. `git commit -m "description of this commit e.g. update User model"`
3. `git push`
