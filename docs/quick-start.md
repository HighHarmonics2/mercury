# 🏃 Quick Start

This quick start guide is meant for people who are confident in working with the computer and have some experience with (creative) coding, music technology and music theory.

# 💻 Install Mercury

Read the [system requirements](./../README.md#-system-requirements) first before getting started.

1. Download and install Max8 via any of the links below. At the moment Mercury seems to run best in Max8.0.8. **You do not need to buy a license in order to use Mercury!** 😎

- [Windows](https://akiaj5esl75o5wbdcv2a-maxmspjitter.s3.amazonaws.com/Max808_x64_190808.zip)
- [Mac](https://akiaj5esl75o5wbdcv2a-maxmspjitter.s3.amazonaws.com/Max808_190808.dmg)
- If links are not working you can go to [https://cycling74.com/downloads/older](https://cycling74.com/downloads/older)

2. Launch Max8 when the installation is done. A Max8 folder is created in your Documents. Locate the Projects folder under `~/Documents/Max 8/Projects`

3. Download the latest [Release](https://github.com/tmhglnd/mercury/releases)
	```
	Download zip and unpack in ~/Documents/Max 8/Projects
	```
	Or **clone/fork** the project
	```
	$ cd ~/Documents/Max\ 8/Projects
	$ git clone http://github.com/tmhglnd/mercury
	```

# 🚀 Launch Mercury

Launch Mercury by double clicking `mercury_ide.maxproj` or 

```
$ cd mercury
$ open mercury_ide/mercury_ide.maxproj
```

- ⏳ Give it some time to load.

- ⚠ **Mac 10.14+ Users**: Make sure you give permissions under Security & Privacy Preferences.

In the `_mercury_main` window:

- 📺 Turn the **Rendering on**
- 🔈 Turn the **Audio on**

In the `mercury` code editor:

- 💻 Type the following code 

	```java
	set tempo 110

	new sample kick_house time(1/4)
	```

- 🔊 Hit `alt + return` or `Menubar > File > Execute Code` 
	- *Mac users: Disable the Alert Volume in `System Preferences > Sounds` to disable the error sound when using shortkeys*

Adjust settings under `Menubar > Settings` for:
- Audio
- Visuals
- Editor
- Shortkeys

You are now ready to start coding your first sounds! 🎶💻🎶

# 🎲 Play!

Now go ahead and play all you want! For further information on the syntax and code see:

- [Tutorial](./tutorial.md)
- [Documentation](./README.md) 

# ⚠ Troubleshooting

Run into an issue?

- First check the [Troubleshooting]() page
- Check if your problem was already reported in the [Issues](https://github.com/tmhglnd/mercury/issues)
- File a [new issue](https://github.com/tmhglnd/mercury/issues/new)
- Fix it yourself and send a pull request! :pray:
