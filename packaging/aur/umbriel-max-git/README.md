# Arch package

Build: `makepkg -s`. Install the non-debug package: `sudo pacman -U <package-file>`.

After AUR publication: `paru -S umbriel-max-git`. Enable Paru's `Devel` setting
for source updates through `paru -Syu`.

When PKGBUILD metadata changes, run `makepkg --printsrcinfo > .SRCINFO` before
publishing to AUR. Source-only updates need no AUR commit.
