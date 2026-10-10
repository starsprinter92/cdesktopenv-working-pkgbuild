# Working PKGBUILD for CDE

A working Arch Linux PKGBUILD for the Common Desktop Environment (CDE).

## Requirements

- Arch Linux
- `git`
- `base-devel`
- The dependencies required by the PKGBUILD

## How to Build and Install

```bash
mkdir -p ~/.cdesktopenv
cd ~/.cdesktopenv

curl -o PKGBUILD https://raw.githubusercontent.com/starsprinter92/cdesktopenv-working-pkgbuild/refs/heads/main/PKGBUILD

makepkg -si
```

## Why?

I'm getting a ThinkPad soon and want to be able to install CDE easily without having to troubleshoot the same build errors again.

CDE's current PKGBUILD is missing flags required for the build to compile successfully. This repository contains a modified PKGBUILD with the necessary flags added.

## Why CDE?

Because I like using old stuff on modern-ish hardware.

