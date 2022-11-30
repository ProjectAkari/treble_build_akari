# Community

* IRC: irc://irc.freenode.net/#phh-treble
* WebIRC: http://webchat.freenode.net/?channels=%23phh-treble&uio=d4
* Matrix: [#phh-treble:matrix.org](https://matrix.to/#/#phh-treble:matrix.org)
* Telegram https://t.me/phhtreble
* xda-developers threads: https://forum.xda-developers.com/search.php?do=finduser&u=1915408&starteronly=1

# How to build

* clone this repository
* call the build scripts from a separate directory

For example:

    git clone https://github.com/ProjectAkari/treble_build_akari
    mkdir ProjectAkari; cd ProjectAkari
    bash ../treble_build_akari/build.sh

# Conventions for commit messages:

* `[UGLY]` Please make this patch disappear as soon as possible
* `[master]` tag means that the commit should be dropped in a future
  rebase
* `[device]` tag means this change is device-specific workaround
* `::device name::` will try to describe which devices are concerned
  by this change
* `[userfriendly]` This commit is NOT used for hardware support, but
  to make the rom more user friendly
