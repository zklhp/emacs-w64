### PURPOSE

For years I have searched the Internet for the 64-bit GNU Emacs binary distribution for MS-Windows. Indeed there do have 64-Bit Emacs for MS-Windows, but I don't like them. Most of them are modified, outdated, or just part of some big system. So I try to compile a up-to-date native 64-bit GNU Emacs from source. Now what you see is my work.

Note that now there are official 64-bit versions for MS-Windows on the [GNU FTP](https://ftp.gnu.org/gnu/emacs/windows/) (they are named as `emacs-25.2-x86_64.zip` or `emacs-25.1-x86_64-w64-mingw32.zip`). Don’t forget the dependency DLLs (for example `emacs-25-x86_64-deps.zip`).

### FEATURE

+ 100% unmodified source code from git master and release version.
+ Native 64-Bit binary for MS-Windows.
+ Compiled with optimization.
+ With JPEG, GIF, PNG, TIFF, SVG, XML2, and GnuTLS support.

### SYSTEM REQUIREMENT

Only x86-64 version of MS Windows (Windows XP, 7, 8, 8.1, and 10) are supported. IA-64 version of Windows are not support. Note that it is only tested on my laptop running Winsows 8.1. 

### USAGES

1. Find and download the version you want on [releases page](https://github.com/zklhp/emacs-w64/releases).
2. Uncompress with [7-Zip](http://www.7-zip.org/) or other software you like.
3. Double-click the runemacs.exe in emacs/bin.

### TECHNICAL DETAILS

If you are interested in compiling Emacs yourself, you can find the workflow in the [wiki page](https://github.com/zklhp/emacs-w64/wiki/Guideline-for-building-Emacs-in-MSYS2-MinGW-w64-system). Or you may prefer [中文版](http://chriszheng.science/2015/03/19/Chinese-version-of-Emacs-building-guideline/).
