**Development Notes:**

- [Setup.py Quickstart](https://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/quickstart.html)
- [Python - install script to system](https://stackoverflow.com/questions/874521/python-install-script-to-system)
- [Sample PKGBUILD](https://aur.archlinux.org/cgit/aur.git/tree/PKGBUILD?h=tovid)
- [Git commit for package version](https://stackoverflow.com/questions/4916492/git-describe-fails-with-fatal-no-names-found-cannot-describe-anything)
- [Check package sanity](https://wiki.archlinux.org/index.php/creating_packages#Checking_package_sanity)
  - ```$ namcap PKGBUILD```
- [Added AGPLv3 license](https://choosealicense.com/licenses/agpl-3.0/#)
- [Submit package to AUR](https://wiki.archlinux.org/index.php/Arch_User_Repository#Submitting_packages)
  - Generate ```.SRCINFO```; ```$ makepkg --printsrcinfo > .SRCINFO`````