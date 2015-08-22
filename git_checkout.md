# Git checkout

This command can be used in at least two ways. The first is to create or checkout a `branch`. Right now we should be on the `master` branch, as that is the only branch at the moment. Let's change that using `checkout`.

# Copying this branch into a new one

A common workflow in Git is to create a `topic branch` for a feature. This way every change and addition to the software for this specific feature can all be together, for better or for worse.

We do this by adding the `-b` command flag to out `git checkout`:

```sh
git checkout -b new_branch
```

Now whatever the commit state is on our master branch has been copied over to a new Git branch called `new_branch`. Additionally, we have been moved to the new branch.

## Using git checkout to reset a file

Sometimes you edit a file and somehow it gets to the point where you just want to _throw it away and start fresh_. You can accomplish with a checkout as well, except instead of checking out a branch or creating a new branch and checking it out, you just reset the one file you want reverted back to the last commit state:

```sh
git checkout readme.md
```

Now the changed made to the `readme.md` file will be lost and it will revert back to the state it was before you fucked it up. Way to go!
