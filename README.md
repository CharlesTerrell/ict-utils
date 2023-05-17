# ict-utils

This is a collection of short utility programs that I wrote for my own use. Most are in perl, python, and/or bash. I offer them here in case anyone else finds them useful.

**unz** - Unzips zip archives listed on the command line. Each extracts to its own folder/dir named after the archive. Skips any files that do not end in ".zip". Example: "unz 2023*_data.zip"

**firestorm** - Generates a local web page and opens it many times in firefox. The purpose is to test system performance under memory pressure, using a reasonably realistic simulation of typical web content. Requires firefox (or another web browser that can be launched from the command line), figlet, pango-view, and access to /usr/share/dict/words or a similar dictionary file.
