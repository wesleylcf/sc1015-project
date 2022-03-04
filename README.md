# Important Notes

---

### Initial steps

refer to [github collaboration guide](https://medium.com/@jonathanmines/the-ultimate-github-collaboration-guide-df816e98fb67).
There will be one person assigned to review pull requests(changes to the project) before merging them to the remote git repository

### Branches

Branches can be thought of as versions of the project, and they can be merged.

There are two branches, main and dev.
Branches can be thought of as versions of the project, and they can be merged. There are two branches, main and dev.

Only work on the dev branch, as the main branch should always be error-free.

Check the branch you are on using `git branch`

To switch to the dev branch use `git checkout dev`(checkout here is synonymous with "navigate to")

With the exception of the above two branches, each branch should represent a feature of the project, for example authentication.

For the purposes of this project, to create a new branch under dev and checkout to it we will use the following convention:
`git checkout -b dev feature/someFeatureYouAreWorkingOn` (the only part you should change is the text after "feature/")

### Workflow

After making significant updates to your feature run:

1. `git add .`
2. `git commit -m "description of this commit e.g. update User model"`
3. `git push`

Significant here is subjective but for simplicity it is safe to interpret it as one large function(around 15 lines), and the project is bug-free.

Running the above commits changes to whatever branch of the project you are at(which should be feature/someFeature). This will not change the overall dev folder unless you create a pull request, and the person assigned to review pull requests, approves it.
