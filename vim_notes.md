Turn off unikey when using VIM, weird stuff happen.

Try the vim tutorial with $ vimtutor

# Skipping around in the file

Ctrl + f: Pages ahead one page at a time.
Ctrl + b: Pages back one page at a time.
Ctrl + d: Pages ahead one-half page at a time.
Ctrl + u: Pages back one-hlaf page at a time.
G: Goes to the last line of the file.
1G: Goes to the first line of the file.
[n]G: Goes to n line number.

# Moving around in the text

# Deleting, copying and changing text

# Exiting vi

ZZ - Save and quit.
:w - Save.
:wq - same as ZZ.
:q - quit only if there is no unsaved changes.
:q! - force quit. 

# Search for text

/[search_key]: search forward for the search_key.
?[search_key]: search backward.

# Using ex mode

# Running command while using vi

!:command - You can run a shell command while you are in vi using :! followed by a shell command name. E.g: :!date