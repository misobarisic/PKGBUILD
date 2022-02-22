# PKGBUILD

This repository contains all of my AUR packages as git submodules.


## Git clone

Git submodules do not get fetched automatically when using `git clone`, meaning you'll have to do `git submodule update --init --recursive` after using a bare clone.
If you want the previous step, run: `git clone --recurse-submodules https://github.com/misobarisic/PKGBUILD`.
