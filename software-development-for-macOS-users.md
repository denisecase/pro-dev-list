## Software Development for macOS Users - a Few Pointers
 
macOS is based on UNIX, from which Linux is derived. To access it on the command line, use
the Terminal: the app is in the Applications > Utilities folder, or you can find it with Spotlight.
Apple's official guide to using the Terminal is here, and worth reading in its entirety. If you are
unfamiliar with UNIX/Linux commands (e.g., ls, cd, pwd, rm, rmdkir, mkdir, touch, etc.), an
excellent, Terminal-specific one, is [here](https://scriptingosx.com/2017/07/first-steps-in-terminal/).
 
## Pointers:
 
1. First, the basics:
   1. Configure the Dock so that it automatically hides (System Preferences >> Dock)
   1. Show file name extensions (Finder Preferences >> Advanced)
   1. Drag commonly-used folders to a Finder window sidebar
   1. Drag commonly-used applications to a Finder window toolbar
   1. Change the Terminal profile to something cool (like Homebrew): Terminal >>
Preferences >> Profiles >> Homebrew (or whatever profile strikes your fancy), then
click on Default
 
1. To go back and forth between the Terminal and Finder is easy:
   1. In the Terminal, type open . to open the current directory as a folder in the Finder
   1. Right click on a folder in the Finder and choose Services >> New Terminal At Folder
to open a terminal in directory that corresponds to the folder
 
1. The default shell on Terminal is zsh, so if you spend a lot of time in the Terminal (as you
should!) check out [this discussion](https://scriptingosx.com/2019/06/moving-to-zsh/) 
 
1. If you visit any of these sites on a Mac, you will get a Mac binary (otherwise just go to
downloads)
   1. [Visual Studio Code](https://code.visualstudio.com)
   1. [git](https://git-scm.com/download/mac)
   1. [node.js](https://nodejs.org/en/)
 
1. Drag Visual Studio Code to a Finder window toolbar. Then, to open up any other folder, just
drag it over the Visual Studio Code Icon
 
1. Install Xcode - it comes with some helpful development toolchains
