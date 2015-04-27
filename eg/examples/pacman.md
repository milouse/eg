# pacman

Install a new package from repositories:

    pacman -S <package>

Install a previously downloaded package to `path`:

    pacman -U <path>

Search packages by name in repositories:

    pacman -Ss <package>

Search already installed packages by name:

    pacman -Qs <package>

Synchronize repositories and upgrade all previously installed packages:

    pacman -Syu

Remove a package and all its dependancies:

    pacman -Rsn <package>
