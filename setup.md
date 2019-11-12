---
layout: page
title: Setup
permalink: /setup/
---

There are several pieces of software you will wish to install before the workshop.
Though installation help will be provided at the workshop, 
we recommend that these tools are installed (or at least downloaded) beforehand.

## bash Shell

To participate in an HPC Carpentry workshop, you will need access to a bash shell. Please make sure to install everything (or at least to download the installers) before the start of your workshop. In addition, you will need an up-to-date web browser.

We maintain a list of common issues that occur during installation as a reference for instructors that may be useful on the [Configuration Problems and Solutions wiki page](https://github.com/swcarpentry/workshop-template/wiki/Configuration-Problems-and-Solutions).

### Windows

  - [Video Tutorial](https://www.youtube.com/watch?v=339AEqk9c-8)

1. Download the [Git for Windows installer](https://git-for-windows.github.io/)
2. Run the installer and follow the steps below:
   a. Click on "Next".
   b. Click on "Next".
   c. Keep "Use Git from the Windows Command Prompt" selected and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option. dlick on "Next".
   d. Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
   e. Keep "Use Windows' default console window" selected and click on "Next".
   f. Click on "Install".
   g. Click on "Finish".
3. If your "HOME" environment variable is not set (or you don't know what this is):
   a. Open command prompt (Open Start Menu then type cmd and press [Enter])
   b. Type the following line into the command prompt window exactly as shown: `setx HOME "%USERPROFILE%`
   c. Press `[Enter]`, you should see `SUCCESS: Specified value was saved.`
   d. Quit command prompt by typing exit then pressing `[Enter]`

This will provide you with bash (and SSH) in the Git Bash program.

### MacOS

The default shell in all versions of Mac OS X is Bash, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities). You may want to keep Terminal in your dock for this workshop.

### Linux

The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash. There is no need to install anything.

## SSH

All students should have an SSH client installed.
SSH is a tool that allows us to connect to and use a remote computer as our own.
Please follow the directions below to install an SSH client for your system.

**Windows**

You should have SSH available in Git Bash after you installed it according to the instructions above.

An alternative is to install MobaXterm from [http://mobaxterm.mobatek.net](http://mobaxterm.mobatek.net). You will want to get the Home edition (Installer edition). However, if Git Bash works, you do not need this.

**macOS**

macOS comes with SSH pre-installed, so you should not need to install anything.

**Linux**

Linux users do not need to install anything, you should be set!
