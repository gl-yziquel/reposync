rsync wrapper to mirror OpenBSD cvs tree on Linux.
==================================================

This repository is forked from [Stuart Henderson's repository][sthen]
on GitHub, which makes available the `reposync` script used to mirror
OpenBSD sources.

[sthen]: https://github.com/sthen/reposync

As it stands, a few minor quirks make it unsuitable for execution on
a Linux system. Two, mainly: the location of `rsync`, and the
formatting argument syntax to the `stat` command. This has here been
fixed, and, as such, the author of this `README.md` has indeed been
able to mirror OpenBSD sources using this script on a Linux box.

Making it available with, of course, no warranty of any kind, in the
sole hope that it will enable people to avoid wasting precious time.
