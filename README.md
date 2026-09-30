# ict-utils

This is a collection of short utility programs that I wrote for my own use. Most are in perl, python, and/or bash. I offer them here in case anyone else finds them useful. Licensed as Apache-2.0 unless specified otherwise; most simple shell scripts are MIT-0 instead due to simplicity.

**sysupd** - Detects and runs common command-line software update tools. Currently looks for apt-get, dnf, snap, and flatpak. Not mutually exclusive: finding snap does not skip flatpak, for example. Requires sudo for apt-get, dnf, and snap. (MIT-0)

**qnaptty** - Connects to QNAP NAS using serial to USB cable. Saves typing by filling in typical parameters such as tty device path. Can override character set so the BIOS config screen looks prettier. (MIT-0)

**dstamp** - Adds current date in format YYYYMMDD to start of file names. Does NOT check for existing date stamps or allow for custom dates or date modified. Those can be added later if there's enough of a need. (MIT-0)

**unz** - Unzips zip archives listed on the command line. Each extracts to its own folder/dir named after the archive. Skips any files that do not end in ".zip". Example: "unz 2023*_data.zip"

**firestorm** - Generates a local web page and opens it many times in firefox. The purpose is to test system performance under memory pressure, using a reasonably realistic simulation of typical web content. Requires firefox (or another web browser that can be launched from the command line), figlet, pango-view, and access to /usr/share/dict/words or a similar dictionary file.
