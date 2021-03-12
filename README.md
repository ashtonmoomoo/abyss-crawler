# abyss-crawler
Why don't musicians use a VCS for managing sheet music while writing? Let's find out!

## The reason why
The file extension used by Guitar Pro 7, `.gp` is basically a zip of some other stuff, binaries and config etc. 
There is a file found in there which has extension `.gpif` but is secretly an `xml` file. This is the file you'd mostly want to track.
It's not really human readable, but does contain the song, in some sense.
The issue is however, that if you tracked the extracted contents of the `.gp` file, there is no way to go back to a `.gp` file which is able to be opened by Guitar Pro 7.
