# paconvert
Makes converting PKGBUILDS into pacscripts easier
### Paconvert will only substitute the names of variables and functions, not the dependencies which needs to be replaced with its corrosponding Ubuntu packages.
Syntax:
`paconvert <flag> <package name> ...`

options:
- -a --aur, Grab PKGBUILD from the AUR
- -m --mpr, Grab PKGBUILD from the MPR
- -l --local, Convert local PKGBUILD
- -h --help, Display this message
