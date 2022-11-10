# Remove sections of lines of text (cut)
```bash
**$ grep /home /etc/passwd | cut -d':' -f6 -**
/home/chris
/home/joe
```

This command outputs the home directory of users in the machine.

The grep command line pipes a list of regular users from the /etc/passwd file and displays the sixth field (*-f6*) as delimited by a colon (*-d':'*). The hyphen at the end tells *cut* to read from standard input (from the pipe).