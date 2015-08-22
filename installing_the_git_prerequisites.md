# Installing the prerequisites

There are some prerequisites that need taking care of first. One of these prerequisites is the Xcode Command Line Tools. To ensure they are installed open your Terminal app (on OSX use command-space and then type 'terminal' and hit enter)

One your terminal window is open, perform the following command. Don't copy and paste the `$` character though, that is just representing your `prompt`.

```sh
$ xcode-select -p
```

If the Xcode command line tools you will see a response like so:

```sh
/Applications/Xcode.app/Contents/Developer
```

or

```sh
/Library/Developer/CommandLineTools
```

Then you already have the tools installed.
