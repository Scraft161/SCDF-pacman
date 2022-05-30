# SCDF-pacman
custom repository for my arch packages

This is a custom repository for me to host and distribute custom packages for Arch Linux.  
Most of these are custom versions of existing programs, others are AUR packages.

official builds are x86_64 only, but most packages have a `${pkgname}-src` version too which should compile locally.

## Add to your system
add the following to your `/etc/pacman.conf`:
```conf
# SCDF-pacman repository
[SCDF-pacman]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/Scraft161/$repo/master/$arch/
```

note that if you run a 32-bit or arm version of arch that you might not see any packages.

## Contributing packages
As of now we do not accept contributed packages as we are still getting our own packages and build system online.
Please be patient while we do so.
