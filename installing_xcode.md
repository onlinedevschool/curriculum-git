## Installing the Xcode Command Line Tools

There are some prerequisites that need taking care of first. One of these prerequisites is the `Xcode Command Line Tools`. To ensure they are installed open your `Terminal` app (on OSX use command-space and then type 'terminal' and hit enter)

One your terminal window is open, perform the following command. Don't copy and paste the `$` character though, that is just representing your `prompt`.

```sh
$ xcode-select -p
```

If the `Xcode command line tools` you will see a response like so:

```sh
/Library/Developer/CommandLineTools
```

Then you already have the tools installed.

However if you see the following

```sh
xcode-select: note: install requested for command line developer tools
```

Then a window will come up instructing you to install the `Xcode command line tools`. Note that you click the `Install` button not the `Get Xcode` button!

![Install Xcode alert](/media/installing_the_git_prerequisites_mac-install-xcode.png)

When that process is finished, verify that you've successfully installed the `Xcode command line tools`:

```sh
$ xcode-select -p
/Library/Developer/CommandLineTools
```

