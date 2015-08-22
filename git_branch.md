# Git branch

But back to this `branch` command, what does it do and why would we need it if we can just create a branch using the checkout command?

Well, because there is more to branches than just creating a new one. In fact branches are the core of Git's form of source control management.

## Listing all the branches

Sometimes we want to see what branches that exist:

```sh
git branch
```

You will notice that whatever branch we are on is bold and has an astrisk next to it. It is a good idea to periodically use this command to make sure you are working on the branch you think you are.

## Deleting branches

You also use the `git branch` command to delete branches locally:

```sh
git branch -d new_branch
```

Or if the branch has not been merged into the upstream (more on that later):

```sh
git branch -D new_branch
```

The `-d` can be translated into _force delete_.
