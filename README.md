# Branching Off Main to Implement a Feature:

1. Make a new branch.
    * `git branch BRANCH-NAME`
2. Checkout to the branch.
    * `git checkout BRANCH-NAME`
3. Write some code.
    * You know what to do. 😉
4. Stage the code for a commit.
    * `git add .`
5. Make a commit.
    * `git commit -m "COMMIT MESSAGE"`
6. Checkout to main branch.
    * `git checkout main`
7. Merge the feature branch into main.
    * `git merge --no-ff BRANCH-NAME`