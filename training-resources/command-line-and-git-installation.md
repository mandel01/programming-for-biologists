# Installation instructions for bash shell and git

**Note, the Windows instructions did not work on many FSM-owned computers due to lack of administrative privileges.**

## The Bash Shell

Bash is a commonly-used shell that gives you the power to do simple tasks more quickly.

#### Windows

Download the Git for Windows [installer](https://git-for-windows.github.io/). Run the installer. This will provide you with both Git and Bash in the Git Bash program. Important: on the 6th page of the installation wizard (the page titled `Configuring the terminal emulator...`) select `Use Windows' default console window`. If you do not, programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.

###### Software Carpentry Installer

This installer requires an active internet connection.

After Git Bash:

- Download the [installer](http://software-carpentry.org/workshops/setup.html).
- Double click on the file to run it.
Information about the SWC Windows Installer, including the source code, can be found at https://github.com/swcarpentry/windows-installer.

#### Mac OS X

The default shell in all versions of Mac OS X is bash, so no need to install anything. You access bash from the Terminal (found in `/Applications/Utilities`). You may want to keep Terminal in your dock for this workshop.

#### Linux

The default shell is usually `bash`, but if your machine is set up differently you can run it by opening a terminal and typing `bash`. There is no need to install anything.

## Git

Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on http://github.com.

#### Windows

Git should be installed on your computer as part of your Bash install (described above).

#### Mac OS X

For OS X 10.8 and higher, install Git for Mac by downloading and running the [installer](http://sourceforge.net/projects/git-osx-installer/files/latest/download). After installing Git, there will not be anything in your `/Applications` folder, as Git is a command line program. For older versions of OS X (10.5-10.7) use the most recent available installer for your OS available [here](http://sourceforge.net/projects/git-osx-installer/files/). Use the Leopard installer for 10.5 and the Snow Leopard installer for 10.6-10.7.

#### Linux

If Git is not already available on your machine you can try to install it via your distro's package manager. For Debian/Ubuntu run `sudo apt-get install git` and for Fedora run `sudo yum install git`.


## Text Editor – Optional (if you prefer to use something other than nano)
When you're writing code, it's nice to have a text editor that is optimized for writing code, with features like automatic color-coding of key words.

#### Windows

nano is the editor installed by the Software Carpentry Installer, it is a basic editor integrated into the lesson material.

If you are not using nano, [Notepad++](http://notepad-plus-plus.org/) is a popular free code editor for Windows. Be aware that you must add its installation directory to your system path in order to launch it from the command line (or have other tools like Git launch it for you). Please ask your instructor to help you do this.

#### Mac OS X

We will be using nano in this lesson, so no need to install anything. You can use another text editor if you like, such as [Text Wrangler](http://www.barebones.com/products/textwrangler/) or [Sublime Text](http://www.sublimetext.com/).

#### Linux

For this lesson, we will use nano, which should be pre-installed. [Kate](http://kate-editor.org/) is another option for Linux users.
