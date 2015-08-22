# Installing is easy

On OSX just run the following terminal command:

```sh
brew install git
```

If you are on Ubuntu use:

```sh
sudo apt-get install git
```

## Configuring Git

Git has loads of configuration options but we will just focus on the ones that matter most or ones that give us the most bang for our buck.

**Note** Files that begin with a . character are known as dotfiles. These are hidden by your system (Mac and Linux) as system files. To see them in the terminal use the following form of the `ls` command:

```sh
ls -a
```

Create a file in your home directory `~/` and put these contents into it:

```ini
[color]
diff = auto
status = auto
branch = auto

[color "diff"]
meta = yellow

[core]
excludesfile = ~/.gitignore

[apply]
whitespace = warn

[help]
autocorrect = 1

[branch]
autosetupmerge = true
autosetuprebase = always

[push]
default = current

[merge]
ff = only
```

Then save and close the file.

I won't explain these here, but you can research the options using Google. Now let's set your user info:

```sh
git config --global user.name "Your name here"
git config --global user.email you@email.here
```

We will also set the editor to use Vim: (feel free to use the editor of your choice instead, not everyone is worthly of Mjölnir)

```sh
git config --global core.editor vim
```

Lastly let's just take a gander at the config as it stands:

```sh
git config --list
```
