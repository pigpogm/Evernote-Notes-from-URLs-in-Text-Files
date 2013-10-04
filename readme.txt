A very simple script, that takes the text file passed as 'thisFile', and for each
line, attempts to create a new Evernote note from that URL.  No checking, so don't
pass it things that aren't URLs.

How I use it:

Drafts on iOS writes to files in Dropbox.  Hazel picks up new text files in that
folder, and runs this script against them.  Each URL gets turned into a new note
in Evernote.