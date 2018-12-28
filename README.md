# phoenicis-wine-dosbox_support
This tool creates a hybrid wine+dosbox installation that behave consistently with wine prefixes:
When running wine executable.exe, it will: 
* analyse the .EXE file
* if it is a Win32 executable, it will run wine 
* if it is a MS-DOS executable, it will prepare a dosbox environement with all the wine drives mounted. It will then execute the file inside DosBOX

It supports macOS and linux wine builds

Pre-built binaries are available here: http://playonlinux.com/wine/.

This tool is mainly meant to be used by phoenicis-winebuild. We advise you to use it to get consistent and working builds. 

## Usage: 
* Patch a wine version: bash patch-wine.sh /path/of/wine/installation 
* Install dosbox on you system, or place the binary inside /path/of/wine/installation/bin, and the dynamic librairies inside /path/of/wine/installation/lib 

## Disclaimer: 
This tool is meant to patch standalone wine builds. Do not use this tool as root, or with any system-wide wine installation! 
