# phoenicis-wine-dosbox_support
This tool creates a hybrid wine+dosbox installation that behave consistently with wine prefixes. It supports macOS and linux wine builds
Pre-built binaries are available here: http://playonlinux.com/wine/.
This tool is mainly meant to be used by phoenicis-winebuild. We advise you to use it to get consistent and working builds. 

## Usage: 
* Patch a wine version: bash patch-wine.sh /path/of/wine/installation 
* Install dosbox on you system, or place the binary inside /path/of/wine/installation/bin, and the dynamic librairies inside /path/of/wine/installation/lib 

## Disclaimer: 
This tool is meant to patch standalone wine builds. Do not use this tool as root, or with any system-wide wine installation! 
