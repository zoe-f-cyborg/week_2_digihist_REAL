# WGET CHEAT SHEET

These are all the commands for using wget that seem relevant to me, organized in such a way that they are easier for me to remember/come back to:

### `pwd`
- checks where you currently are on your computer (which file or "directory" you are working within and which anything you pull will end up)
- `~` means you are in the most general section, the "main users folder," and you almsot definitely do not want to be there becuase you almost definitely will not be able to find that file again.

### `cd [file name]`
- this takes you to whichever directory you want to go to.
- for some reason, when you are in a subfile of a file (i.e. Documents/digital-history/week-1), `cd [file name]` (i.e. cd digital-history) will not take you to the main file. Going `cd ~`and then `cd [main file name]` (i.e. Documents/digital-history) resolves this. Then, just `cd [subfile name]` (i.e. cd week-2) will work perfectly. 

### `mkdir [file name]`
- this creates a new file
- make sure you are where you want to be for this-- i.e. digital-history

### `wget [url]`
- collects a single url

### `wget -r -np -w 2 --limit-rate=20k [url]`
- collects all of the subfiles within that url (powerful; dangerous; forbidden) 

### `wget -i urls.txt -r --no-parent -nd -w 2 --limit-rate=100k`
- collects all of the urls listed in a text file called "urls.txt," which can be swapped out for any file name (just make sure it has ONLY urls in it)
