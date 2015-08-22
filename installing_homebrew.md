## Introducing Homebrew

Homebrew is an awesome package manager for Mac. Essentially it is a list of recipes used to build various C programs that you will run in the Terminal. What can you install with Homebrew? Here are a few common examples:

* PostgreSQL
* Mysql Server
* Redis
* Ruby
* Vim
* Wget
* and many many many more!

## Installing Homebrew

Run this command in your terminal. Remember to not copy the `$` character!

```sh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

In one fell swoop, that command will use curl to download the install file (written in Ruby) and then it will run it in Ruby to run the installer. When it is done Homebrew will be installed.

## Calling a doctor!

You should regularly run a command that will inspect the health of your `Homebrew` program and all the programs you installed with it. It is called `brew doctor` and if anything, it will tell you a bunch about `Homebrew` and your system.

## Seeing what is installed

```sh
brew list
```

## Searching for programs to install

```sh
brew search <program name>
```

## Installing software

```sh
brew install <program name>
```

## Uninstalling software

```sh
brew remove <program name>
```

## Updating Homebrew itself

```sh
brew update
```

## Installed, but WHERE?

By default `Homebrew` uses `Linux` standards as to where it installs the programs on your hard drive. You can find the actual files at:

```sh
/usr/local/Cellar
```

Happy brewing!
