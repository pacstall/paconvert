# paconvert
Makes converting PKGBUILDS into pacscripts easier
### Paconvert will only substitute the names of variables and functions, not the dependencies which needs to be replaced with its corrosponding Ubuntu packages.
Syntax:
`paconvert <flag> <package name> ...`

##### Installation
```bash
wget -q -O /bin/paconvert https://raw.githubusercontent.com/pacstall/paconvert/main/paconvert && sudo chmod +x /bin/paconvert
```

Options:
- -a --aur, Grab PKGBUILD from the AUR
- -m --mpr, Grab PKGBUILD from the MPR
- -l --local, Convert local PKGBUILD
- -h --help, Display this message
