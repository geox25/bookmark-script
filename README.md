# bookmark-script
Easy scripts for managing bookmarks in Linux

## Installation:
To use these scripts, make sure you have the directory ``~/store/cache/`` with the file ``snippets.txt``.
This is the text file where all of the snippets will be stored.

If you are using dwm, you can bind these scripts to key combinations in your ``config.h``. It should work
in most environments, however the process will vary depending on your window manager or desktop environment.

## Usage:
- ``markthis``: Bookmarks whatever text you have selected
- ``listmarks``: Echos the contents of ``~/store/cache/snippets.txt``
- ``getmark``: Types out the snippet you select
- ``getdel``: Deletes the snippet you select

Additionally, when creating a bookmark/snippet you are given the option to
add metadata (not included when selecting a bookmark/snippet) which may be
helpful to group certain snippets together for easier searching.

## Dependencies:
- xclip
- dmenu
- xdotool
- notify-send

Almost all of the programs used should be included by default in all Linux distros, however the above you will
likely need to install.
