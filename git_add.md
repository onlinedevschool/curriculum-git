# Git add

Before we can commit these changes into Git we need to `add` them into Git. Right now the folder and file you created are _in_ this folder, but they are not being `tracked` by Git.

```sh
git add filename
```

You can also use wildcards and `command flags`:

```sh
git add .
```

Will add everything not specified by the `.gitignore` file (more on that later).

```sh
git add --all
```

Will `stage` all changes into the commit we are preparing, but it will not add files not already being tracked by the repository

But my personal favorite is:

```sh
git add --all -p
```

Which does the `--all` bit, but it also let's me decide change by change if I really want to include it in this commit. Sometimes you have changes that were made, but I don't actually want them wrapped up in the current commit.
