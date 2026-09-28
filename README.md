# omarchy-mobile packages

The official pacman repository of [omarchy-mobile](https://github.com/turbineBMW),
Omarchy on the OnePlus 6T: signed packages for Arch Linux ARM (aarch64).
They are the assets of the release `repo`; this repository holds nothing else.

Every package and the database are signed with the project key:

    C76926E739B7DE883C42C90775CB3AFFF3820E8D

Phones trust it through the `omarchy-mobile-keyring` package. Their
`/etc/pacman.conf` lists the repository above Arch Linux ARM's:

    [omarchy-mobile]
    SigLevel = Required
    Include = /etc/pacman.d/omarchy-mobile-mirrorlist

with

    Server = https://github.com/turbineBMW/omarchy-mobile-packages/releases/download/repo
